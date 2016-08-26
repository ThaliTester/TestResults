#### Test 79763830d186b13_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-26 21:10:25.090  6553  6553 D Mms/MmsApp: [end]    initCountryIso consume time = 13.957552
08-26 21:10:25.090  6553  6553 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.082292
--------- beginning of system
08-26 21:10:25.090  1018  1522 D CountryDetector: The first listener is added
08-26 21:10:25.120  6553  6553 D Mms/MmsConfig: before partial update
08-26 21:10:25.140  1660  1736 I art     : Explicit concurrent mark sweep GC freed 10515(514KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.019ms total 43.091ms
08-26 21:10:25.150  1018  1265 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 21:10:25.150  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:25.150  1018  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:25.150  6553  6553 D Mms/MmsConfig: Load Resize quality : 80
08-26 21:10:25.150  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-26 21:10:25.160  6553  6553 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-26 21:10:25.160  6553  6553 D EasySignUpManager_1.0.1: isAuth is false
08-26 21:10:25.160  6553  6553 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-26 21:10:25.180  1483  1657 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6553
08-26 21:10:25.180  1483  1657 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.353 ms
08-26 21:10:25.200  6518  6571 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 484 ms] updated apps [took 484 ms] 
08-26 21:10:25.200  6553  6553 D EasySignUpManager_1.0.1: isAuth is false
08-26 21:10:25.200  6553  6553 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-26 21:10:25.200  6553  6698 D Mms/ArtClassLoader: init [DONE] art
08-26 21:10:25.200  6553  6553 E CscParser: mps_code.dat does not exist
08-26 21:10:25.200  6553  6553 E CscParser: customer_path =/system/csc/customer.xml
08-26 21:10:25.200  6553  6553 E CscParser: fileName + /system/csc/customer.xml
08-26 21:10:25.210  1018  1494 I ActivityManager: Killing 6186:com.google.android.music:main/u0a108 (adj 15): empty #21
08-26 21:10:25.210  6553  6553 E CscParser: mps_code.dat does not exist
08-26 21:10:25.210  6553  6553 E CscParser: customer_path =/system/csc/customer.xml
08-26 21:10:25.210  6553  6553 E CscParser: fileName + /system/csc/customer.xml
08-26 21:10:25.210  1822  6594 I qtaguid : Untagging socket 97
08-26 21:10:25.220  6553  6553 D CscParser: getInstance fileName =/system/csc/customer.xml
08-26 21:10:25.220  6553  6553 D Mms/MmsConfig:  enable multiwindow = false
08-26 21:10:25.230  1822  1822 I ConfigFetchService: fetch service done; releasing wakelock
08-26 21:10:25.230  1822  1822 I ConfigFetchService: stopping self
08-26 21:10:25.240  6553  6553 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-26 21:10:25.240  6553  6553 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-26 21:10:25.250  6553  6553 D Mms/MmsConfig: [end]    init() consume time = 152.930312
08-26 21:10:25.250  6553  6553 D Mms/Contact: [start]    init() consume time = 0.724323
08-26 21:10:25.260  6553  6553 D Mms/Contact: [end]    init consume time = 16.404427
08-26 21:10:25.270  1483  1498 D TP/MmsSmsProvider: query,matched:13, calling pid = 6553
08-26 21:10:25.270  1483  1498 D TP/MmsSmsProvider: match 13:Elapsed time : 1.709 ms
08-26 21:10:25.280  6553  6767 D Mms/DraftCache: [start]    rebuildCache consume time = 12.620625
08-26 21:10:25.290  6553  6553 D Mms/MethodReflector: getSubId is called
08-26 21:10:25.290  6553  6553 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 21:10:25.290  1483  1657 D TP/MmsSmsProvider: query,matched:12, calling pid = 6553
08-26 21:10:25.290  6553  6553 D Mms/MethodReflector: getTelephonyProperty is called
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: auto download without roaming -> true
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 21:10:25.290  6553  6553 D Mms/MethodReflector: getSubId is called
08-26 21:10:25.290  6553  6553 D Mms/MethodReflector: getDefaultSmsSubId is called
08-26 21:10:25.290  6553  6553 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-26 21:10:25.290  6553  6553 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-26 21:10:25.290  1483  1657 D TP/MmsSmsProvider: match 12:Elapsed time : 1.742 ms
08-26 21:10:25.290  6553  6553 D Mms/MethodReflector: getTelephonyProperty is called
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: auto download without roaming -> true
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: auto download during roaming secondary -> false
08-26 21:10:25.290  6553  6553 D Mms/DownloadManager: mAutoDownload ------> true
08-26 21:10:25.290  6553  6767 D Mms/DraftCache: [end]    rebuildCache consume time = 15.371771
08-26 21:10:25.330  6553  6553 D ComposerPerformance: 1472238625335 ms / [DONE] Composer constructor
08-26 21:10:25.330  6553  6553 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-26 21:10:25.330  6553  6553 I Mms/ReservationManager: ReservationManager()
08-26 21:10:25.330  6553  6553 I Mms/ReservationManager: resetAfterConnected()
08-26 21:10:25.330  1483  1498 D TP/MmsSmsProvider: query,matched:7, calling pid = 6553
08-26 21:10:25.330  1483  1498 D TP/MmsSmsProvider: match 7:Elapsed time : 1.908 ms
08-26 21:10:25.340  6553  6768 D Mms/Conversation: [start]    init() consume time = 46.433854
08-26 21:10:25.340  1483  1657 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-26 21:10:25.340  6553  6553 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-26 21:10:25.340  1483  1657 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-26 21:10:25.340  1483  1657 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-26 21:10:25.340  1483  1657 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-26 21:10:25.350  6553  6553 D Mms/MmsApp: [end]    onCreate() consume time = 10.254583
08-26 21:10:25.350  1483  1657 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 21:10:25.350  1483  1657 D TP/MmsSmsProvider: need read changed broadcast:false
08-26 21:10:25.350  6553  6768 D Mms/Conversation: [end]    init consume time = 3.074688
08-26 21:10:25.350  6553  6768 D Mms/MessagingNotification: [start]    init() consume time = 2.942292
08-26 21:10:25.360  6553  6768 D Mms/MessagingNotification: [end]    init consume time = 2.81427
08-26 21:10:25.360  1483  2482 D TP/MmsSmsProvider: query,matched:0, calling pid = 6553
08-26 21:10:25.360  1483  2482 V TP/MmsSmsProvider: getSimpleConversations entered.
08-26 21:10:25.360  1483  2482 D TP/MmsSmsProvider: match 0:Elapsed time : 1.308 ms
08-26 21:10:25.360  6553  6770 D Mms/Synchronizer: [start]    doSync consume time = 7.148334
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-26 21:10:25.370  1483  1498 D TP/MmsSmsProvider: update, matched:300, calling pid = 6553
08-26 21:10:25.370  1483  1498 V TP/MmsSmsProvider: syncDBData start
08-26 21:10:25.370  6553  6553 D Mms/MethodReflector: getSubId is called
08-26 21:10:25.370  6553  6553 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 21:10:25.370  6553  6553 D Mms/MethodReflector: getTelephonyProperty is called
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: auto download without roaming -> true
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 21:10:25.370  6553  6553 D Mms/DownloadManager: mAutoDownload ------> true
08-26 21:10:25.370  1483  1498 V TP/MmsSmsProvider: syncDBData sms end
08-26 21:10:25.370  1483  1498 V TP/MmsSmsProvider: syncDBData mms end
08-26 21:10:25.370  1483  1498 V TP/MmsSmsProvider: syncDBData end
08-26 21:10:25.370  6553  6770 D Mms/Synchronizer: [end]    doSync consume time = 8.739791
08-26 21:10:25.370  1018  1522 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-26 21:10:25.380  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.380  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.380  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.380  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.390  6553  6769 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 12.413438
08-26 21:10:25.390  1018  1522 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6771 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 21:10:25.390  6771  6771 E Zygote  : MountEmulatedStorage()
08-26 21:10:25.400  1483  2482 D TP/MmsSmsProvider: query,matched:400, calling pid = 6553
08-26 21:10:25.400  6771  6771 E Zygote  : v2
08-26 21:10:25.400  6553  6769 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 14.218281
08-26 21:10:25.400  6771  6771 I libpersona: KNOX_SDCARD checking this for 10068
08-26 21:10:25.400  6771  6771 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:25.400  6771  6771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:25.410  6553  6553 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-26 21:10:25.410  1018  1031 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-26 21:10:25.410  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:25.410  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-26 21:10:25.410  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:25.410  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-26 21:10:25.410  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-26 21:10:25.410  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.410  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.410  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.410  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.430  6771  6771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:25.430  1018  1030 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6777 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-26 21:10:25.430  6777  6777 E Zygote  : MountEmulatedStorage()
08-26 21:10:25.430  6777  6777 I libpersona: KNOX_SDCARD checking this for 10042
08-26 21:10:25.430  6777  6777 E Zygote  : v2
08-26 21:10:25.430  6777  6777 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:25.430  6771  6771 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 21:10:25.430  6777  6777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:25.430  6777  6777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:25.430  6777  6777 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-26 21:10:25.460  6762  6762 D AndroidRuntime: 
08-26 21:10:25.460  6762  6762 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 21:10:25.460  6771  6771 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:25.460  6762  6762 D AndroidRuntime: CheckJNI is OFF
08-26 21:10:25.460  6762  6762 D AndroidRuntime: readGMSProperty: start
08-26 21:10:25.460  6762  6762 D AndroidRuntime: readGMSProperty: already setted!!
08-26 21:10:25.460  6762  6762 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 21:10:25.460  6762  6762 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 21:10:25.460  6762  6762 D AndroidRuntime: readGMSProperty: end
08-26 21:10:25.460  6762  6762 D AndroidRuntime: addProductProperty: start
08-26 21:10:25.460  6771  6771 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:25.460  6777  6777 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:25.470  6777  6777 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:25.470  6553  6800 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-26 21:10:25.470  6553  6800 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-26 21:10:25.470  1018  1031 I ActivityManager: Killing 6292:com.android.calendar/u0a131 (adj 15): empty #21
08-26 21:10:25.480  1018  1504 I ActivityManager: Killing 6408:com.android.defcontainer/u0a3 (adj 15): empty #21
08-26 21:10:25.490  1822  6619 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 173.532ms
08-26 21:10:25.490  6777  6777 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 21:10:25.490  6777  6777 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 21:10:25.490  6777  6777 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 21:10:25.620  6762  6762 E AffinityControl: AffinityControl: registerfunction enter
08-26 21:10:25.630  1018  1031 W art     : Suspending all threads took: 6.985ms
08-26 21:10:25.650  6762  6762 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 21:10:25.660  1018  1031 I art     : Explicit concurrent mark sweep GC freed 139012(7MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 22MB/34MB, paused 9.748ms total 177.663ms
08-26 21:10:25.690  6771  6771 D BadgeProvider: onCreate
08-26 21:10:25.690  6771  6771 D BadgeProvider: DatabaseHelper
08-26 21:10:25.710  1018  1265 E PersonaManagerService: inState():  stateMachine is null !!
08-26 21:10:25.710  6553  6768 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 21:10:25.710  1018  1265 I PersonaManagerService: PersonaId don't exist
08-26 21:10:25.710  1018  1265 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 21:10:25.720  1483  1498 D TP/SmsProvider: query,matched:26, calling pid = 6553
08-26 21:10:25.720  1018  1265 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 21:10:25.720  1483  1498 D TP/SmsProvider: match 26:Elapsed time : 2.382 ms
08-26 21:10:25.740  1018  1265 W ActivityManager: mDVFSHelper.acquire()
08-26 21:10:25.740  1018  1320 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 21:10:25.740  1018  1265 D FocusedStackFrame: Set to : 0
08-26 21:10:25.760  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.760  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.760  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.760  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.770  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 21:10:25.770  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 21:10:25.780  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 21:10:25.780  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4205, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 21:10:25.780  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 21:10:25.780  1018  1030 D BatteryService: stay LED for charging
08-26 21:10:25.780  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 21:10:25.790  6812  6812 E Zygote  : MountEmulatedStorage()
08-26 21:10:25.790  6812  6812 E Zygote  : v2
08-26 21:10:25.790  6812  6812 I libpersona: KNOX_SDCARD checking this for 10170
08-26 21:10:25.790  6812  6812 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:25.790  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 21:10:25.790  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 21:10:25.790  6812  6812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:25.790  1018  1265 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6812 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 21:10:25.790  1018  1265 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 21:10:25.790  1018  1265 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 21:10:25.790  6812  6812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:25.790   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 21:10:25.790  6812  6812 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 21:10:25.810  6812  6812 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:25.810  1018  1265 D InputDispatcher: Focused application set to: xxxx
08-26 21:10:25.810  1018  1265 D InputDispatcher: Focus left window: 1505
08-26 21:10:25.810  6762  6762 D AndroidRuntime: Shutting down VM
08-26 21:10:25.820  6812  6812 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:25.820  1018  1018 I MotionRecognitionService: Plugged
08-26 21:10:25.820  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 21:10:25.820  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 21:10:25.820  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 21:10:25.820  6777  6777 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-26 21:10:25.830  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 21:10:25.830  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 21:10:25.830  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 21:10:25.840  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 21:10:25.850  1018  1031 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 21:10:25.850  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 21:10:25.850  3219  3330 D HeadsetStateMachine: Disconnected process message: 10
08-26 21:10:25.850  1018  1018 V ActivityManager: Display changed displayId=0
08-26 21:10:25.860  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 21:10:25.860  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 21:10:25.860  1177  1177 D SViewCoverView: level :100 plugged : 2
08-26 21:10:25.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 21:10:25.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 21:10:25.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 21:10:25.880  1018  1031 D PersonaManager: isKioskContainerExistOnDevice
08-26 21:10:25.880   259   438 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-26 21:10:25.890   259   817 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-26 21:10:25.890  1018  1139 I ActivityManager: Killing 6157:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-26 21:10:25.890  1018  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-26 21:10:25.890  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 21:10:25.890  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.890  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.890  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.890  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.910  1505  1505 D Launcher: onTrimMemory. Level: 20
08-26 21:10:25.910  1505  1505 V ActivityThread: updateVisibility : ActivityRecord{2907dcf token=android.os.BinderProxy@13ec551a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 21:10:25.910  6829  6829 E Zygote  : MountEmulatedStorage()
08-26 21:10:25.910  6829  6829 E Zygote  : v2
08-26 21:10:25.910  6829  6829 I libpersona: KNOX_SDCARD checking this for 10003
08-26 21:10:25.910  6829  6829 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:25.910  6829  6829 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:25.920  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6829 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 21:10:25.920  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 21:10:25.920  6829  6829 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:25.920  6829  6829 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:25.950  1483  2482 D TP/MmsSmsProvider: query,matched:6, calling pid = 6553
08-26 21:10:25.950  1483  2482 D TP/MmsSmsProvider: match 6:Elapsed time : 1.234 ms
08-26 21:10:25.950  6829  6829 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:25.950  6829  6829 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:25.990  1018  1320 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-26 21:10:25.990  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.990  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.990  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:25.990  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.000  1018  1320 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6845 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-26 21:10:26.000  6845  6845 E Zygote  : MountEmulatedStorage()
08-26 21:10:26.000  6845  6845 I libpersona: KNOX_SDCARD checking this for 10023
08-26 21:10:26.000  6845  6845 E Zygote  : v2
08-26 21:10:26.000  6845  6845 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:26.010   288   288 E installd: system dir 0 : /system/app/
08-26 21:10:26.010   288   288 E installd: system dir 1 : /system/priv-app/
08-26 21:10:26.010   288   288 E installd: system dir 2 : /vendor/app/
08-26 21:10:26.010   288   288 E installd: system dir 3 : /oem/app/
08-26 21:10:26.010  6845  6845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:26.010  6845  6845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:26.010  6845  6845 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:26.030  1018  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-26 21:10:26.040  6762  6762 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 21:10:26.050  6845  6845 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:26.050  6845  6845 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:26.050  6600  6735 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-26 21:10:26.050  6600  6735 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 21:10:26.050  6600  6735 I GAv4    :   adb logcat -s GAv4
08-26 21:10:26.060  1018  1031 I ActivityManager: Killing 6453:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-26 21:10:26.090  6600  6735 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 21:10:26.090  1018  1321 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 21:10:26.090  6812  6812 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 21:10:26.090  1018  1043 W ProcessCpuTracker: Skipping unknown process pid 6762
08-26 21:10:26.100  6600  6735 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-26 21:10:26.110  6812  6812 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6246-6248)
08-26 21:10:26.110  6812  6812 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 21:10:26.140  6845  6845 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-26 21:10:26.160  6600  6735 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-26 21:10:26.160  6553  6768 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 21:10:26.170  6600  6863 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-26 21:10:26.190  6600  6624 W art     : Suspending all threads took: 7.530ms
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 21:10:26.190  6812  6812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {862eecd}
08-26 21:10:26.190  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 21:10:26.200  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 21:10:26.200  6812  6812 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 21:10:26.200  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 21:10:26.200  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 21:10:26.200  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 21:10:26.200  6812  6812 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 21:10:26.200  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 21:10:26.210  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 21:10:26.210  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-26 21:10:26.220  1822  4188 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-26 21:10:26.260  1822  4188 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-26 21:10:26.290  6812  6812 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-26 21:10:26.290  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:10:26.300  6812  6812 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 21:10:26.320  1822  4188 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-26 21:10:26.340  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 21:10:26.340  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:26.340  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:26.340  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 21:10:26.340  6812  6812 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 21:10:26.340  6812  6812 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 21:10:26.340  6812  6812 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 21:10:26.340  6812  6812 I Adreno-EGL: Local Branch: 
08-26 21:10:26.340  6812  6812 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 21:10:26.340  6812  6812 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 21:10:26.340  6812  6812 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 21:10:26.360  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-26 21:10:26.360  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.360  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.360  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.360  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.370  6877  6877 E Zygote  : MountEmulatedStorage()
08-26 21:10:26.370  6877  6877 E Zygote  : v2
08-26 21:10:26.370  6877  6877 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:10:26.370  6877  6877 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:26.370  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:26.370  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:26.370  1018  1490 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 21:10:26.380  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:26.370  1018  1490 I ActivityManager: Killing 6469:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-26 21:10:26.380  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{36544285 u0 com.test.thalitest/.MainActivity t163}
08-26 21:10:26.400  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:26.400  6877  6877 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:26.420  6877  6877 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-26 21:10:26.430  6877  6877 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-26 21:10:26.430  1018  1522 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-26 21:10:26.430  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-26 21:10:26.430  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:26.430  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:26.430  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-26 21:10:26.430  1018  1490 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-26 21:10:26.440  6877  6877 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-26 21:10:26.450  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-26 21:10:26.450  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-26 21:10:26.450  1018  1404 D NtpTrustedTime: forceRefresh() from cache miss
08-26 21:10:26.450   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:10:26.450   279  1012 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-26 21:10:26.470  6877  6894 E FilterInstaller: installFilters
08-26 21:10:26.470  6877  6894 E FilterInstaller: There is no requred permission
08-26 21:10:26.470  6600  6875 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 21:10:26.470  1018  1031 I ActivityManager: Killing 6484:com.sec.spp.push/u0a32 (adj 15): empty #21
08-26 21:10:26.470  6600  6875 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 21:10:26.490  1018  1018 I BackgroundCompactionService: onStart. jobID=801
08-26 21:10:26.490  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
08-26 21:10:26.500  1018  6903 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-26 21:10:26.500  1018  6903 I BackgroundCompactionService: compact_memory command done
08-26 21:10:26.510  6812  6812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:10:26.550  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 21:10:26.550  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 21:10:26.550  6600  6875 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-26 21:10:26.560  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 21:10:26.560  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 21:10:26.620  6600  6875 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 21:10:26.620  6600  6875 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dadab08: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 21:10:26.620  6600  6875 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-26 21:10:26.700  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:10:26.710  6812  6812 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 21:10:26.720  1018  1404 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472238626713 mCachedNtpElapsedRealtime : 96851 mCachedNtpCertainty : 10
08-26 21:10:26.720  1018  1404 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:26.720  1018  1404 D AlarmManagerService: Setting time of day to sec=1472238626
08-26 21:10:26.720  1018  1404 D AlarmManagerService: Trying to open a file
08-26 21:10:26.720  6812  6812 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 21:10:26.720  6812  6812 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-26 21:10:26.720  1018  1404 D AlarmManagerService: File Open Success
08-26 21:10:26.720  1018  1404 D AlarmManagerService: File Close Success
08-26 21:10:26.720  1018  1404 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-26 21:10:26.713  1018  1096 V AlarmManager: waitForAlarm result :65536
08-26 21:10:26.713  1018  1404 W AlarmManagerService: Unable to set rtc to 1472238626: Invalid argument
08-26 21:10:26.713  6812  6812 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-26 21:10:26.713  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=96865 batch.start=110041
08-26 21:10:26.722  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472238626725
08-26 21:10:26.722  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-26 21:10:26.722  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 21:10:26.732  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 21:10:26.732  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
08-26 21:10:26.742  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-26 21:10:26.742  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-26 21:10:26.742  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:10:26.742  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 21:10:26.742  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-26 21:10:26.742  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-26 21:10:26.752  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:10:26.752  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:10:26.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 21:10:26.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 21:10:26.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 21:10:26.752  1018  1018 I DrmEventService:  no response from SecureClock 
08-26 21:10:26.752  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-26 21:10:26.752  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-26 21:10:26.752  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-26 21:10:26.752  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-26 21:10:26.752  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-26 21:10:26.762  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.762  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.762  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.762  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:26.762  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 21:10:26.762  1018  1321 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-26 21:10:26.762  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:26.762  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:26.762  1018  1321 D SettingsProvider: selectionArgs: false
08-26 21:10:26.762  1018  1321 D SettingsProvider: selectionArgs: 10049
08-26 21:10:26.762  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:26.762  1018  1321 D SettingsProvider: ret = -1
08-26 21:10:26.762  1177  1177 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,08-26 21:10:26.772  6914  6914 E Zygote  : MountEmulatedStorage(),
08-26 21:10:26.772  6914  6914 E Zygote  : v2
,08-26 21:10:26.772  6914  6914 I libpersona: KNOX_SDCARD checking this for 10008
08-26 21:10:26.772  1177  1177 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-26 21:10:26.772  6914  6914 I libpersona: KNOX_SDCARD not a persona,
08-26 21:10:26.772  1177  1177 I GeometricMosaic_Keyguard: update
08-26 21:10:26.772  6914  6914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 21:10:26.772  1177  1177 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-26 21:10:26.772  6914  6914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:26.772  6914  6914 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 21:10:26.782  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6914 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:26.782  1018  1494 I ActivityManager: Killing 6499:com.samsung.helphub/1000 (adj 15): empty #21
,08-26 21:10:26.792  6914  6914 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:26.802  6914  6914 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:26.842  6812  6932 D OpenGLRenderer: Render dirty regions requested: true
,08-26 21:10:26.852  1018  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 21:10:26.852  1018  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 21:10:26.852  1018  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 21:10:26.852  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 21:10:26.852  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 21:10:26.862  6812  6812 V ActivityThread: updateVisibility : ActivityRecord{397c8cc4 token=android.os.BinderProxy@1762ff56 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 21:10:26.862  6812  6899 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 21:10:26.862  6812  6812 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-26 21:10:26.862  6812  6812 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 21:10:26.872  6914  6914 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 21:10:26.882  1177  1177 I KeyguardEffectViewUtil: set current wallpaper info
,08-26 21:10:26.882  1018  1031 D SettingsProvider: name = keyguard_current_wallpaper_type
08-26 21:10:26.882  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:26.882  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:26.882  1018  1031 D SettingsProvider: selectionArgs: false
08-26 21:10:26.882  1018  1031 D SettingsProvider: selectionArgs: 10049
08-26 21:10:26.882  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:26.882  1018  1031 D SettingsProvider: ret = -1
,08-26 21:10:26.882  1018  1514 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-26 21:10:26.882  1018  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:26.882  1018  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:26.882  1018  1514 D SettingsProvider: selectionArgs: false
08-26 21:10:26.882  1018  1514 D SettingsProvider: selectionArgs: 10049
08-26 21:10:26.882  1018  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:26.882  1018  1514 D SettingsProvider: ret = -1
,08-26 21:10:26.882  1018  1321 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-26 21:10:26.882  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:26.882  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:26.882  1018  1321 D SettingsProvider: selectionArgs: false
08-26 21:10:26.882  1018  1321 D SettingsProvider: selectionArgs: 10049
08-26 21:10:26.882  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:26.882  1018  1321 D SettingsProvider: ret = -1
,08-26 21:10:26.892   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 21:10:26.902  1018  1522 D InputDispatcher: Focus entered window: 6812
,08-26 21:10:26.912  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 21:10:26.912  6812  6812 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 21:10:26.912  6812  6932 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 21:10:26.912  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 21:10:26.912  6812  6932 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-26 21:10:26.912  6812  6932 D OpenGLRenderer: Enabling debug mode 0
,08-26 21:10:26.922  6914  6914 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-26 21:10:26.942  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 21:10:26.952  1018  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 21:10:26.952  1018  1139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 21:10:26.952  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-26 21:10:26.952  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:26.952  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:26.952  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:10:26.972  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s104ms (total +1s227ms)
,08-26 21:10:26.972  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36544285 u0 com.test.thalitest/.MainActivity t163} time:97120
08-26 21:10:26.972  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-26 21:10:26.972  1177  1611 D TEST    : run!!!
,08-26 21:10:26.972  1177  1177 D PanelView: There is/are notification(s) 
,08-26 21:10:26.972   259   817 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-26 21:10:26.982   259   434 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 21:10:26.982  6812  6812 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 21:10:26.982  6812  6812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1762ff56 time:97138
,08-26 21:10:27.002  1177  1611 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-26 21:10:27.012  1018  1320 I ActivityManager: Killing 5230:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-26 21:10:27.042  1018  1522 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 21:10:27.042  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-26 21:10:27.042  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:27.052  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:27.052  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:10:27.052  1998  1998 I SamsungIME: getCurrentCandidateView
,08-26 21:10:27.062  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Aug 26 21:10:27 GMT+02:00 2016
,08-26 21:10:27.062  1018  1514 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 21:10:27.062  1018  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 21:10:27.062  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:27.062  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:27.062  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 21:10:27.072  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 21:10:27.072  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 21:10:27.082  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:27.082  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.082  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.082  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:27.092  6944  6944 E Zygote  : MountEmulatedStorage()
,08-26 21:10:27.092  6944  6944 E Zygote  : v2
,08-26 21:10:27.092  6944  6944 I libpersona: KNOX_SDCARD checking this for 10036
08-26 21:10:27.092  6944  6944 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:27.092  1018  1490 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6944 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:27.092  6944  6944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:27.092  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 21:10:27.102  6538  6572 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-26 21:10:27.102  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 21:10:27.112  6944  6944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:27.112  6944  6944 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 21:10:27.112  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 21:10:27.122  2814  6943 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-26 21:10:27.122   325   325 I art     : Explicit concurrent mark sweep GC freed 8681(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 27.383ms
,08-26 21:10:27.132   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84007c8
08-26 21:10:27.132   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-26 21:10:27.132   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 21:10:27.132   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203763912)
08-26 21:10:27.132  6812  6812 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6812
,08-26 21:10:27.142   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 19.734ms
,08-26 21:10:27.142  6538  6572 I AcmsKeyStoreHelper: Key Store exist
08-26 21:10:27.142  6538  6572 I AcmsKeyStoreHelper: Hence loading the keystore file,
08-26 21:10:27.142  2814  6943 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-26 21:10:27.142  2814  6943 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Fri Aug 26 21:10:27 GMT+02:00 2016
,08-26 21:10:27.162  2814  6943 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
08-26 21:10:27.162   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 17.704ms
08-26 21:10:27.162  6944  6944 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:27.162  6944  6944 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:27.172  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy(),
,08-26 21:10:27.192   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
08-26 21:10:27.192   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-26 21:10:27.192   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203763912) wakelock released: 1, error no: 0
08-26 21:10:27.192   274   299 I rmt_storage: 
08-26 21:10:27.192   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84007c8
,08-26 21:10:27.242  6944  6944 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3fb19215
08-26 21:10:27.242  6538  6572 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-26 21:10:27.242  6538  6572 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-26 21:10:27.242  6538  6572 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-26 21:10:27.242  6538  6572 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 21:10:27.242  6538  6572 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-26 21:10:27.242  6538  6572 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-26 21:10:27.242  6538  6572 D AcmsCore: This is NOT a valid MirrorLink app
08-26 21:10:27.242  6538  6572 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-26 21:10:27.242  6538  6572 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 21:10:27.242  6538  6572 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-26 21:10:27.242  6538  6572 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-26 21:10:27.242  6538  6538 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 21:10:27.242  6538  6538 D AcmsService: Enter onDestroy
08-26 21:10:27.242  6538  6538 I AcmsService: cleanUp(): inside service clean up
08-26 21:10:27.242  6538  6538 D AcmsCore: AcmsCore: inside DeInit
08-26 21:10:27.242  6538  6538 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-26 21:10:27.242  6538  6538 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-26 21:10:27.242  6538  6538 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-26 21:10:27.242  6538  6538 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-26 21:10:27.242  6538  6538 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-26 21:10:27.242  6538  6538 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 21:10:27.242  6538  6538 D AcmsService: killing acms process
,08-26 21:10:27.242  6538  6538 I Process : Sending signal. PID: 6538 SIG: 9
,08-26 21:10:27.252  6944  6944 I SA      : [SSP] onCreated
,08-26 21:10:27.262  6944  6944 I SA      : [TPM] There is no property file
,08-26 21:10:27.262  6944  6944 I SA      : [SCU] isHaveSA() - false
,08-26 21:10:27.272  6944  6944 I SA      : [TPM] getModelProperty : null
08-26 21:10:27.272  6944  6944 I SA      : [TPM] getCSCProperty : null
,08-26 21:10:27.272  6944  6944 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 21:10:27.272  6944  6944 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 21:10:27.272  6944  6944 I SA      : [DM] TFT FEATURE: false
,08-26 21:10:27.282  6944  6944 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-26 21:10:27.282  6944  6944 I SA      : [DM] init START
,08-26 21:10:27.282  6944  6944 I SA      : [DM] This device is not a Vodafone
,08-26 21:10:27.282  6944  6944 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 21:10:27.282  6944  6944 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 21:10:27.282  6944  6944 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 21:10:27.292  6944  6944 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-26 21:10:27.302  6944  6944 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 21:10:27.302  6944  6944 I SA      : [SCU] isHaveSA() - false
08-26 21:10:27.302  6944  6944 I SA      : support phone number id : false
08-26 21:10:27.302  6944  6944 I SA      : [DM] Supports Ref Jpn : true
08-26 21:10:27.302  6944  6944 I SA      : [DM] init END
,08-26 21:10:27.312  1998  1998 D SamsungIME: Dismiss ExpandCandiate
,08-26 21:10:27.322  1018  1320 I ActivityManager: Process ACMS.Process (pid 6538)(adj 0) has died(20,796)
,08-26 21:10:27.332  6553  6553 I Mms/MmsApp:  start initViewCache mms
,08-26 21:10:27.332  6553  6553 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1950.184686
08-26 21:10:27.332  6553  6553 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-26 21:10:27.392  6812  6812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 21:10:27.442  6553  6553 D AbsListView: Get MotionRecognitionManager
,08-26 21:10:27.442  1018  1265 D MotionRecognitionService:  ssp status : false
,08-26 21:10:27.452  6553  6553 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 115.334531
,08-26 21:10:27.492  6812  6940 D jxcore_app_log: JniHelper::setJavaVM(0xb764d2b0), pthread_self() = -1212307920
,08-26 21:10:27.492  1998  1998 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 21:10:27.502  6812  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8668eb added. We now have 1 listener(s)
,08-26 21:10:27.502  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-26 21:10:27.512  6812  6940 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 21:10:27.512  6812  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:10:27.512  6812  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 21:10:27.512  6812  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37d7ea06 added. We now have 1 listener(s)
,08-26 21:10:27.512  6812  6940 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 21:10:27.522  6812  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:27.532  6812  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-26 21:10:27.532  6812  6940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:27.532  6812  6940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:27.532  6812  6940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 21:10:27.532  6812  6940 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:10:27.542  6812  6940 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 21:10:27.542  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:27.542  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:27.552  6553  6553 D Mms/BubbleViewCache: fillCache bubble = 1
08-26 21:10:27.562  1018  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
08-26 21:10:27.562  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.562  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.562  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.562  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.562  1998  1998 I SamsungIME: getDebugLevel  : 0x4f4c
08-26 21:10:27.572  6970  6970 E Zygote  : MountEmulatedStorage()
08-26 21:10:27.572  6970  6970 I libpersona: KNOX_SDCARD checking this for 10058
08-26 21:10:27.572  6970  6970 E Zygote  : v2
08-26 21:10:27.572  6970  6970 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:27.572  6970  6970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:27.582  6812  6812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 21:10:27.582  6970  6970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:27.582  6970  6970 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:27.592  1018  1139 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6970 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:10:27.592  1018  1139 I ActivityManager: Killing 5459:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-26 21:10:27.612  6970  6970 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:27.612  6970  6970 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:27.622  1998  1998 I SamsungIME: KeybaordView init() : load resources
,08-26 21:10:27.672  1998  1998 I SamsungIME: getCurrentKeyboard
08-26 21:10:27.672  1998  1998 I SamsungIME: getTextKeyboard
,08-26 21:10:27.682  6970  6970 I ExternalOEMControlProvider: onCreate
,08-26 21:10:27.692  1018  1031 I ActivityManager: Killing 6518:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 21:10:27.702  1998  1998 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 21:10:27.702  1757  1757 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-26 21:10:27.702  1757  1757 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 21:10:27.712  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-26 21:10:27.712  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.712  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.712  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:27.712  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:27.712  6970  6985 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-26 21:10:27.722  6986  6986 E Zygote  : MountEmulatedStorage(),
08-26 21:10:27.722  6986  6986 I libpersona: KNOX_SDCARD checking this for 10081
08-26 21:10:27.722  6986  6986 E Zygote  : v2
08-26 21:10:27.722  6986  6986 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:27.722  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:27.732  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:27.732  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:27.732  1018  1494 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6986 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:27.742  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:27.752  6986  6986 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:27.762  6986  6986 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 21:10:27.762  6986  6986 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 21:10:27.762  6986  6986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:10:27.762  6986  6986 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:10:27.762  6986  6986 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 21:10:27.782   292   292 E SMD     : DCD OFF
,08-26 21:10:27.812  1018  1490 D SettingsProvider: name = next_alarm_formatted
,08-26 21:10:27.812  1018  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:27.812  1018  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:27.812  1018  1490 D SettingsProvider: selectionArgs: false
08-26 21:10:27.812  1018  1490 D SettingsProvider: selectionArgs: 10081
08-26 21:10:27.812  1018  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:27.812  1018  1490 D SettingsProvider: ret = -1
,08-26 21:10:28.012  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 21:10:28.012  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.012  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.012  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.012  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.032  7001  7001 E Zygote  : MountEmulatedStorage(),
08-26 21:10:28.032  7001  7001 E Zygote  : v2
08-26 21:10:28.032  7001  7001 I libpersona: KNOX_SDCARD checking this for 10090
08-26 21:10:28.032  7001  7001 I libpersona: KNOX_SDCARD not a persona,
08-26 21:10:28.032  7001  7001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.032  7001  7001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:28.032  7001  7001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:28.032  1018  1321 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7001 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-26 21:10:28.042  1018  1321 I ActivityManager: Killing 6113:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 21:10:28.052  7001  7001 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.052  7001  7001 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.082  7001  7001 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-26 21:10:28.082  7001  7001 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 21:10:28.082  7001  7001 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 21:10:28.092  1018  1320 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 21:10:28.092  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 21:10:28.092  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:28.092  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:28.092  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 21:10:28.092  7001  7001 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-26 21:10:28.092  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-26 21:10:28.102  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.102  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.102  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.102  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.102  7001  7001 D elm:15121: ElmAgentService : onCreate()
,08-26 21:10:28.112  7001  7016 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
08-26 21:10:28.112  7017  7017 E Zygote  : MountEmulatedStorage()
08-26 21:10:28.112  7017  7017 E Zygote  : v2
08-26 21:10:28.112  7017  7017 I libpersona: KNOX_SDCARD checking this for 10130
08-26 21:10:28.112  7017  7017 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:28.112  7017  7017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.112  1018  3318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 21:10:28.112  7017  7017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:28.112  1018  1490 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7017 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-26 21:10:28.112  7017  7017 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 21:10:28.112  7001  7016 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-26 21:10:28.122  7001  7001 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-26 21:10:28.122  7001  7001 D elm:15121: ModuleBase.ModifySetAlarm()
08-26 21:10:28.122  7001  7001 D elm:15121: MDMBridge.getInstance()
08-26 21:10:28.122  7001  7001 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 21:10:28.122  7001  7001 D elm:15121: ElmAgentService : onDestroy().
,08-26 21:10:28.122  1018  1321 I ActivityManager: Killing 6576:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-26 21:10:28.142  7017  7017 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.142  7017  7017 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.152  7017  7017 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:10:28.162  7017  7017 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-26 21:10:28.172  1018  1514 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-26 21:10:28.172  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.172  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.172  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.172  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.182  7033  7033 E Zygote  : MountEmulatedStorage()
,08-26 21:10:28.182  7033  7033 I libpersona: KNOX_SDCARD checking this for 10131
08-26 21:10:28.182  7033  7033 E Zygote  : v2
08-26 21:10:28.182  7033  7033 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:28.182  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.192  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:28.192  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 21:10:28.192  1018  1514 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7033 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-26 21:10:28.192  1018  1514 I ActivityManager: Killing 6600:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-26 21:10:28.202  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.212  7033  7033 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.222  7033  7033 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 21:10:28.222  7033  7033 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:10:28.222  7033  7033 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:10:28.242  6812  6969 W jxcore-log: Initializing JXcore engine
08-26 21:10:28.242  6812  6969 W jxcore-log: JXcore engine is ready
,08-26 21:10:28.262  2671  6368 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 21:10:28.262  1018  1504 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 21:10:28.262  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 21:10:28.272  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:28.272  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:28.272  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:28.282  1018  1030 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 21:10:28.282  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 21:10:28.282  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:28.282  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:28.292  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:28.292  1018  1494 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-26 21:10:28.292  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.292  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.292  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.292  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.302  1995  1995 E audit   : type=1400 msg=audit(1472238628.302:205): avc:  denied  { ioctl } for  pid=6969 comm="Thread-1270" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-26 21:10:28.302  1995  1995 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:28.302  1995  1995 E audit   : type=1300 msg=audit(1472238628.302:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f1fd8f8 items=0 ppid=325 ppcomm=main pid=6969 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1270" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 21:10:28.302  1995  1995 E audit   : type=1320 msg=audit(1472238628.302:205): 
,08-26 21:10:28.312  7055  7055 E Zygote  : MountEmulatedStorage()
08-26 21:10:28.312  7055  7055 E Zygote  : v2
08-26 21:10:28.312  7055  7055 I libpersona: KNOX_SDCARD checking this for 10037
08-26 21:10:28.312  7055  7055 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:28.312  7055  7055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.312  7055  7055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:10:28.312  1018  1494 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7055 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:10:28.312  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-26 21:10:28.312  7055  7055 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 21:10:28.312  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.312  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.312  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.312  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.312  6812  6969 W jxcore-log: Starting JXcore engine
,08-26 21:10:28.332  7065  7065 E Zygote  : MountEmulatedStorage()
08-26 21:10:28.332  7065  7065 E Zygote  : v2
08-26 21:10:28.332  7065  7065 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:10:28.332  7065  7065 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:28.332  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.332  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:28.332  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:28.332  1018  1504 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 21:10:28.342  7055  7055 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.352  7055  7055 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.362  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.362  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.362  7055  7055 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-26 21:10:28.392  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 21:10:28.392  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 21:10:28.392  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:28.392  7055  7055 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-26 21:10:28.402  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-26 21:10:28.402  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.402  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.402  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.402  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.412  7086  7086 E Zygote  : MountEmulatedStorage()
,08-26 21:10:28.412  7086  7086 E Zygote  : v2
08-26 21:10:28.412  7086  7086 I libpersona: KNOX_SDCARD checking this for 10153
08-26 21:10:28.412  7086  7086 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:28.412  7086  7086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 21:10:28.412  1018  1031 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7086 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-26 21:10:28.422  7086  7086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:28.422  7086  7086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:28.422  1018  1031 I ActivityManager: Killing 6625:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-26 21:10:28.432  7086  7086 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.442  7086  7086 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.442  6812  6969 W jxcore-log: Platform android
08-26 21:10:28.442  6812  6969 W jxcore-log: 
08-26 21:10:28.442  6812  6969 W jxcore-log: Process ARCH arm
08-26 21:10:28.442  6812  6969 W jxcore-log: 
,08-26 21:10:28.462  7086  7086 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:10:28.472  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
08-26 21:10:28.472  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.472  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.472  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:28.472  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:28.502  7104  7104 E Zygote  : MountEmulatedStorage()
08-26 21:10:28.502  7104  7104 E Zygote  : v2
08-26 21:10:28.502  7104  7104 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:10:28.502  7104  7104 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:28.502  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:28.502  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:28.502  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:28.502  1018  1265 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 21:10:28.512  1018  1265 I ActivityManager: Killing 6645:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-26 21:10:28.532  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:28.532  7104  7104 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:28.632  1018  1139 I art     : Explicit concurrent mark sweep GC freed 20037(1105KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.558ms total 141.549ms
,08-26 21:10:28.652  1018  1494 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-26 21:10:28.652  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-26 21:10:28.652  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:28.652  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:28.652  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 21:10:28.662  6812  6969 I jxcore-log: JXcore Cordova bridge is ready!
08-26 21:10:28.662  6812  6969 I jxcore-log: 
,08-26 21:10:28.662  6812  6969 W jxcore-log: JXcore engine is started
,08-26 21:10:28.672  7104  7104 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472238628678
08-26 21:10:28.672  7104  7104 D         : TimeServiceNative: User Time to be set is 1472238628678
08-26 21:10:28.672  7104  7104 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-26 21:10:28.672  7104  7104 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-26 21:10:28.672  7104  7104 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472238628678
,08-26 21:10:28.672  6812  6940 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 21:10:28.672   347   423 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-26 21:10:28.672  7104  7104 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472238628678
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472238628678, operation = 0
,08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/21/71 12:53:19
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:Value read from RTC seconds = 35988799000
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:new time 1472238628678 
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon: delta 1436249829678 genoff 1436249829678 
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829678 to memory
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-26 21:10:28.672   347  7122 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 21:10:28.682  6812  6812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 21:10:28.702   347  7122 D QC-time-services: Updating the TOD offset
08-26 21:10:28.702   347  7122 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829678 to memory
08-26 21:10:28.702   347  7122 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-26 21:10:28.702   347  7122 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 21:10:28.702   347  7122 E QC-time-services: Daemon:Update to modem bit set
08-26 21:10:28.702   347  7122 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-26 21:10:28.702  7104  7104 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-26 21:10:28.702   347  7122 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285029678
,08-26 21:10:28.702   347   416 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-26 21:10:28.702   347   423 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 21:10:28.702  1018  1522 I ActivityManager: Killing 6661:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-26 21:10:28.712  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 21:10:28.712  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 21:10:28.712  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 21:10:28.712  1018  1514 I ActivityManager: Killing 6699:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-26 21:10:28.712  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 21:10:28.722  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 21:10:28.722  2671  2671 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-26 21:10:28.732  2671  2671 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 21:10:28.732  2671  2671 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-26 21:10:28.732  2671  2671 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 21:10:28.732  2671  2671 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 21:10:28.732  2671  2671 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-26 21:10:28.732  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 21:10:28.732  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-26 21:10:28.742  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 21:10:28.742  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 21:10:28.742  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-26 21:10:28.742  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 21:10:28.742  2671  2671 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-26 21:10:28.752  2671  2671 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-26 21:10:28.752  2671  2671 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-26 21:10:29.652  7055  7055 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-26 21:10:29.652  1018  1043 W ActivityManager: userId = 0, bbcId = -10000,
08-26 21:10:29.652  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.652  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-26 21:10:29.662  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-26 21:10:29.662  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:29.662  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.662  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 21:10:29.662  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:29.672  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.672  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:29.672  1018  1494 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 21:10:29.672  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 21:10:29.672  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:29.672  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.672  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:29.682  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:29.682  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.682  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:29.682  1018  1504 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 21:10:29.682  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 21:10:29.682  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:29.682  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:29.682  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 21:10:29.702  1018  1320 I ActivityManager: Killing 6717:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 21:10:30.222  1660  1660 I ConfigService: onDestroy
,08-26 21:10:30.782   292   292 E SMD     : DCD OFF,
,08-26 21:10:33.112  1018  3318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 21:10:33.652  1018  3300 D SSRM:n  : SIOP:: AP = 410
,08-26 21:10:33.792   292   292 E SMD     : DCD OFF
,08-26 21:10:35.762  1018  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 21:10:35.812  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 21:10:35.812  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 21:10:35.812  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 21:10:35.812  1018  1321 D BatteryService: stay LED for charging
,08-26 21:10:35.812  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 21:10:35.812  1018  1018 I MotionRecognitionService: Plugged
,08-26 21:10:35.812  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 21:10:35.822  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 21:10:35.822  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 21:10:35.822  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 21:10:35.822  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 21:10:35.842  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 21:10:35.842  3219  3330 D HeadsetStateMachine: Disconnected process message: 10
,08-26 21:10:35.852  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 21:10:35.852  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 21:10:35.852  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:35.852  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:35.852  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:36.012  1018  1057 D PackageManager: [MSG] MCS_UNBIND
,08-26 21:10:36.022  1018  1514 I ActivityManager: Killing 6042:com.android.vending/u0a26 (adj 15): empty #21
,08-26 21:10:36.792   292   292 E SMD     : DCD OFF,
,08-26 21:10:38.292  1018  1330 E Watchdog: !@Sync 3
,08-26 21:10:39.402   341   341 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 21:10:39.402   341   341 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 21:10:39.792   292   292 E SMD     : DCD OFF
,08-26 21:10:39.892  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 21:10:39.892  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-26 21:10:39.892  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:39.892  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:39.892  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:39.892  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:39.902  7129  7129 E Zygote  : MountEmulatedStorage()
08-26 21:10:39.902  1018  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7129 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:10:39.902  7129  7129 E Zygote  : v2
08-26 21:10:39.902  7129  7129 I libpersona: KNOX_SDCARD checking this for 10026
08-26 21:10:39.902  7129  7129 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:39.912  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:39.912  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:39.912  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 21:10:39.932  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:39.932  7129  7129 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:40.002  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.012  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.052  7129  7129 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 21:10:40.052  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.142  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.142  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.152  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.152  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.152  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.162  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.172  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.172  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.172  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.172  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.172  7129  7129 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 21:10:40.192  7129  7129 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 21:10:40.192  7129  7129 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 21:10:40.212  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.212  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.212  7129  7129 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 21:10:40.242  7129  7129 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 21:10:40.242  1018  1265 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-26 21:10:40.242  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-26 21:10:40.242  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:40.242  1018  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 21:10:40.242  7129  7165 D Ads     : Skipping gmscore version check
,08-26 21:10:40.252  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-26 21:10:40.262  1018  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 21:10:40.262  7129  7129 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 21:10:40.272  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:40.272  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:40.272  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-26 21:10:40.292  7129  7129 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 21:10:40.482  7129  7162 D Finsky  : [1339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-26 21:10:40.482  7129  7129 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 21:10:40.482  1018  1514 I ActivityManager: Killing 6737:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-26 21:10:41.182  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 21:10:41.182  6812  6969 I jxcore-log: 
,08-26 21:10:41.192  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 21:10:41.192  6812  6969 I jxcore-log: 
,08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:41.192  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:41.192  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-26 21:10:41.202  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-26 21:10:41.202  6812  6969 I jxcore-log: 
,08-26 21:10:41.202  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-26 21:10:41.202  6812  6969 I jxcore-log: 
,08-26 21:10:41.852  6812  6969 D executeNativeTests: Running unit tests,
,08-26 21:10:41.942  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:10:41.942  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb added. We now have 2 listener(s)
,08-26 21:10:41.952  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 21:10:41.952  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:10:41.952  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:10:41.952  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:41.952  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 added. We now have 2 listener(s)
,08-26 21:10:41.952  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:41.952  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:10:41.952  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:41.952  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:41.952  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:41.952  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:41.962  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:41.962  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:10:41.962  6812  6969 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 21:10:41.962  6812  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:10:41.962  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:41.962  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:41.962  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:41.962  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:41.962  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:41.962  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.962  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:41.962  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb removed from the list
08-26 21:10:41.962  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:41.962  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 removed from the list
,08-26 21:10:41.962  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:41.962  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:41.962  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:41.962  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.962  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:41.972  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:41.972  6812  6969 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 21:10:41.972  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:41.972  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:41.972  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:41.972  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.972  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:41.972  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:41.972  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:41.972  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:41.972  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.972  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:41.972  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.972  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:41.972  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:41.972  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:10:41.982  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:41.982  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:41.982  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:41.982  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 21:10:41.982  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:41.982  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:41.982  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:41.982  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:41.982  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:41.982  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:41.982  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:41.982  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:41.982  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:41.982  6812  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:10:41.982  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:41.992  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:41.992  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:41.992  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:10:41.992  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:10:41.992  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:10:41.992  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:10:41.992  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:41.992  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:10:41.992  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:41.992  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:10:41.992  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.002  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:10:42.012  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:10:42.012  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 21:10:42.022  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 21:10:42.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:10:42.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:10:42.022  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:10:42.022  3219  3326 D BtGatt.GattService: registerClient() - UUID=073806b2-47fa-4644-874c-8483671e007b
,08-26 21:10:42.072  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=073806b2-47fa-4644-874c-8483671e007b, clientIf=6,
08-26 21:10:42.072  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 21:10:42.072  3219  3233 D BtGatt.GattService: start scan with filters
08-26 21:10:42.072  3219  3328 D BtGatt.ScanManager: handling starting scan
08-26 21:10:42.072  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:10:42.072  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:10:42.072  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:42.072  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:10:42.072  3219  3328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64,
08-26 21:10:42.082  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:42.082  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 21:10:42.082  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:10:42.082  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 21:10:42.082  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.092  3219  3328 D BtGatt.ScanManager: allow scan with filters
08-26 21:10:42.092  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 21:10:42.092  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:10:42.092  3219  3328 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 21:10:42.092  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 21:10:42.092  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.092  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:10:42.092  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 21:10:42.092  6812  6969 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:10:42.102  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 21:10:42.102  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.102  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:42.102  6812  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:10:42.102  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.102  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:10:42.102  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.102  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:42.102  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:10:42.102  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:42.102  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:42.102  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:10:42.102  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:10:42.102  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:10:42.102  3219  3234 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:10:42.102  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 21:10:42.102  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:10:42.102  3219  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:42.112  3219  3328 D BtGatt.ScanManager: filter size is 1
08-26 21:10:42.112  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.112  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:42.112  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.112  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.112  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.112  6812  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:10:42.112  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:10:42.112  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:42.112  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:42.112  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:42.122  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:42.122  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 21:10:42.122  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.122  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:10:42.122  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:42.122  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:42.122  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:10:42.122  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:10:42.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:10:42.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:42.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:10:42.132  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 21:10:42.132  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.132  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.132  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 21:10:42.132  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.132  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:10:42.132  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 21:10:42.142  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:10:42.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:10:42.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:10:42.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 21:10:42.142  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:10:42.142  3219  3233 D BtGatt.GattService: registerClient() - UUID=feb6570f-fdc5-42ce-b9c1-42a5fc129f38
,08-26 21:10:42.192  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=feb6570f-fdc5-42ce-b9c1-42a5fc129f38, clientIf=6
,08-26 21:10:42.192  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 21:10:42.192  3219  3326 D BtGatt.GattService: start scan with filters
08-26 21:10:42.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:10:42.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:10:42.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:42.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:10:42.192  3219  3328 D BtGatt.ScanManager: handling starting scan
,08-26 21:10:42.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:42.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:10:42.192  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:42.202  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 21:10:42.202  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.202  3219  3328 D BtGatt.ScanManager: allow scan with filters
08-26 21:10:42.202  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 21:10:42.202  3219  3328 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 21:10:42.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:10:42.202  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 21:10:42.202  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.212  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:10:42.212  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 21:10:42.212  6812  6969 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:10:42.212  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:42.212  6812  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:10:42.212  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.212  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:10:42.212  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.212  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:42.212  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:10:42.212  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:42.212  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:42.212  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:10:42.212  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:10:42.212  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:10:42.212  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 21:10:42.212  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.212  3219  3326 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:10:42.212  3219  3233 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:10:42.222  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 21:10:42.222  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.222  3219  3328 D BtGatt.ScanManager: filter size is 1
,08-26 21:10:42.222  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 21:10:42.222  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:10:42.232  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 21:10:42.232  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.232  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:10:42.232  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:10:42.232  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:10:42.232  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:10:42.232  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:10:42.232  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 21:10:42.232  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.232  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:42.242  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:10:42.242  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:42.242  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.242  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:10:42.242  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:10:42.242  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:42.242  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:10:42.242  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:42.242  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
,08-26 21:10:42.242  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:42.242  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.242  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.242  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.252  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-26 21:10:42.252  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.252  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:42.252  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:42.252  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:42.252  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.252  6812  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 21:10:42.262  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:42.262  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:42.262  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:42.262  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:42.272  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:10:42.272  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:10:42.272  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:10:42.272  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:42.272  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:10:42.272  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.272  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.272  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:10:42.282  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:10:42.282  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:10:42.282  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:10:42.282  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:10:42.282  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:10:42.292  3219  3326 D BtGatt.GattService: registerClient() - UUID=2f9153d4-68b5-4571-9ab8-5d5653499611
,08-26 21:10:42.332  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=2f9153d4-68b5-4571-9ab8-5d5653499611, clientIf=6
,08-26 21:10:42.332  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 21:10:42.332  3219  3233 D BtGatt.GattService: start scan with filters
08-26 21:10:42.332  3219  3328 D BtGatt.ScanManager: handling starting scan,
08-26 21:10:42.332  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:10:42.332  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 21:10:42.332  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:42.332  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:10:42.342  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-26 21:10:42.342  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:10:42.342  3219  3328 D BtGatt.ScanManager: allow scan with filters,
08-26 21:10:42.342  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 21:10:42.342  3219  3328 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 21:10:42.342  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:42.342  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 21:10:42.342  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.342  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:10:42.342  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 21:10:42.352  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:10:42.352  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:10:42.352  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 21:10:42.352  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.352  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:10:42.362  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 21:10:42.362  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:10:42.362  6812  6969 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:10:42.362  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.362  6812  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:10:42.362  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:42.362  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 21:10:42.362  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.362  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:42.362  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 21:10:42.372  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:42.372  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 21:10:42.372  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:10:42.372  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:10:42.372  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:10:42.372  3219  3234 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:10:42.372  3219  3328 D BtGatt.ScanManager: filter size is 1
,08-26 21:10:42.372  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 21:10:42.372  3219  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:10:42.372  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:10:42.372  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:10:42.372  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:10:42.372  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:10:42.372  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:10:42.372  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-26 21:10:42.372  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:10:42.372  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:10:42.382  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:42.382  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-26 21:10:42.382  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:10:42.382  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:42.382  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:42.382  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:42.382  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.382  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 21:10:42.382  6812  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:10:42.382  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.382  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.382  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.382  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:42.382  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.382  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.382  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.382  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.382  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.382  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.392  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 21:10:42.392  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:10:42.392  6812  6969 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 21:10:42.392  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.392  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.392  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.392  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.392  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:10:42.392  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:42.392  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.392  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.392  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.392  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.392  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.392  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.392  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.402  6812  6969 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 21:10:42.402  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:42.402  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.402  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.402  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.402  6812  6969 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 21:10:42.402  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.402  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:42.402  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list,
08-26 21:10:42.402  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.402  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.402  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:42.402  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-26 21:10:42.402  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 21:10:42.402  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:42.402  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:10:42.402  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.412  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.412  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.412  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:42.412  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.412  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.412  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.412  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.412  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:42.412  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.412  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.412  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 21:10:42.412  6812  6969 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:42.412  6812  6969 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:10:42.412  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 21:10:42.412  6812  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:42.412  6812  6969 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:42.412  6812  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:42.412  6812  6969 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 21:10:42.412  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:42.412  6812  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:42.412  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 21:10:42.422  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 21:10:42.422  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 21:10:42.422  6812  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:42.422  6812  6969 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 21:10:42.422  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.422  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.422  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.422  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.422  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.422  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 21:10:42.422  6812  7171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1334)
08-26 21:10:42.422  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.422  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.422  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.422  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.422  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.422  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.422  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.422  6812  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1334
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.422  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.422  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.422  6812  6969 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 21:10:42.432  6812  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:10:42.432  6812  6969 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:10:42.432  6812  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:42.432  6812  6969 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 21:10:42.432  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.432  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.432  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.432  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.432  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.432  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.442  6812  7171 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.442  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.442  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.442  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.442  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.442  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  7171 D BluetoothSocket: connect(): myUserId = 0
08-26 21:10:42.442  6812  7171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 21:10:42.442  6812  6812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 21:10:42.442  3219  3233 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 21:10:42.442  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.442  6812  6812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 21:10:42.442  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:10:42.442  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.442  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.442  6812  7173 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 21:10:42.442  6812  7173 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 21:10:42.442  6812  7171 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.452  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.452  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.452  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:42.452  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:42.452  6812  6812 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 21:10:42.452  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:42.452  6812  6969 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 21:10:42.452  6812  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:10:42.452  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:42.452  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.452  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
,08-26 21:10:42.452  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.452  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.452  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.452  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.452  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.452  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.462  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:42.462  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:42.462  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:42.462  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:42.462  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.462  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.462  6812  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af4aefb not in the list
08-26 21:10:42.462  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.462  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:42.462  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.462  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.462  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:42.462  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:42.462  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:42.462  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:42.462  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:42.462  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a12b18 not in the list
08-26 21:10:42.462  6812  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:10:42.462  6812  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:10:42.462  6812  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 21:10:42.462  6812  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:10:42.462  6812  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:10:42.462  6812  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 21:10:42.462  6812  6969 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgo,ing connection with peer with ID outgoing
08-26 21:10:42.462  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:42.462  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@381bb83a added. We now have 2 listener(s)
08-26 21:10:42.462  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:42.462  6812  6969 D BluetoothAdapter: enable()
08-26 21:10:42.472  6812  6969 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 21:10:42.472  1018  1504 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 21:10:42.472  1018  1504 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 21:10:42.472  1018  1504 D SecContentProvider2: mCursor = null
08-26 21:10:42.472  1018  1504 D WifiService: setWifiEnabled: true pid=6812, uid=10170
08-26 21:10:42.472  1018  1504 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:10:42.482  1018  1504 W WifiService: Failed getting userId using ActivityManagerNative
08-26 21:10:42.482  1018  1504 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:10:42.482  1018  1504 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 21:10:42.482  1018  1504 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 21:10:42.482  1018  1504 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 21:10:42.482  1018  1504 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 21:10:42.482  1018  1504 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 21:10:42.482  1018  1504 D SettingsProvider: name = wifi_on
08-26 21:10:42.482  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:42.482  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ccb4ceb added. We now have 3 listener(s)
08-26 21:10:42.482  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:42.482  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:42.482  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc18a48 added. We now have 4 listener(s)
08-26 21:10:42.482  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:42.492  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:42.492  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@223a00e1 added. We now have 5 listener(s)
08-26 21:10:42.492  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:42.492  1018  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 21:10:42.492  1018  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 21:10:42.492  1018  1494 D SecContentProvider2: mCursor = null
,08-26 21:10:42.492  1018  1494 D WifiService: setWifiEnabled: false pid=6812, uid=10170
,08-26 21:10:42.492  1018  1494 D SettingsProvider: name = wifi_on
,08-26 21:10:42.512  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-26 21:10:42.512  6812  6969 D BluetoothAdapter: disable()
08-26 21:10:42.512  1395  1395 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 21:10:42.512  1395  1395 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 21:10:42.512  1018  1031 D SettingsProvider: name = bluetooth_on
08-26 21:10:42.512  1395  1395 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 21:10:42.512  1395  1395 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 21:10:42.522  3219  3277 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
,08-26 21:10:42.522  3219  3277 D BluetoothAdapterProperties: Setting state to 13
08-26 21:10:42.522  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.522  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:10:42.522  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 21:10:42.522  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:42.522  3219  3277 D BluetoothAdapterService: updateAdapterState state is 13
08-26 21:10:42.522  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:10:42.522  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.522  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:42.522  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.522  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 21:10:42.522  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e25bd24, channel: 19, state: LISTENING
08-26 21:10:42.522  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e25bd24, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dfce88c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@338ab08dmSocket: android.net.LocalSocket@de65242 impl:android.net.LocalSocketImpl@392d5253 fd:FileDescriptor[80]
08-26 21:10:42.522  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@de65242 impl:android.net.LocalSocketImpl@392d5253 fd:FileDescriptor[80]
08-26 21:10:42.522  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:42.522  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 21:10:42.532  3219  3277 D BluetoothAdapterService: terminating service from this receiver
08-26 21:10:42.532  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:42.532  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:42.532  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 21:10:42.532  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 21:10:42.532  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 21:10:42.532  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:42.532  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 21:10:42.542  1998  1998 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:10:42.542  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:42.542  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:42.542  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:42.542  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.542  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:42.542  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:10:42.542  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:42.542  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:42.542  1018  1320 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 21:10:42.542  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.552  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.552  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.552  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:42.552  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 21:10:42.552  3219  3277 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 21:10:42.552  3219  3277 D BluetoothAdapterProperties: mDiscovering is false
,08-26 21:10:42.552  1018  1265 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 21:10:42.552  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:42.552  1018  1127 E WifiNative-wlan0: do suspend true
08-26 21:10:42.552  3219  3277 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 21:10:42.552  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:42.562  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 21:10:42.562  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.562  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26938790, channel: 5, state: LISTENING
08-26 21:10:42.562  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26938790, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1bd1dbd5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@97ec889mSocket: android.net.LocalSocket@f0b508e impl:android.net.LocalSocketImpl@3630c0af fd:FileDescriptor[82]
08-26 21:10:42.562  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f0b508e impl:android.net.LocalSocketImpl@3630c0af fd:FileDescriptor[82]
,08-26 21:10:42.562  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 21:10:42.562  3219  3219 I BtOppRfcommListener: stopping Accept Thread
08-26 21:10:42.562  3219  3280 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:10:42.562  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23d18cbc, channel: 12, state: LISTENING
08-26 21:10:42.562  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23d18cbc, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cff51b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e826445mSocket: android.net.LocalSocket@1a6fe79a impl:android.net.LocalSocketImpl@1552b8cb fd:FileDescriptor[87]
08-26 21:10:42.562  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a6fe79a impl:android.net.LocalSocketImpl@1552b8cb fd:FileDescriptor[87]
,08-26 21:10:42.562  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 21:10:42.562  3219  3277 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 21:10:42.572  3219  5227 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:10:42.572  3219  5227 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 21:10:42.572  3219  3277 E bt-btif : cmd socket is not created
08-26 21:10:42.572  6812  7171 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@128fccc7, channel: -1, state: INIT
08-26 21:10:42.572  6812  7171 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@128fccc7, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@208902f4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15f4ca1dmSocket: android.net.LocalSocket@1e3d1492 impl:android.net.LocalSocketImpl@37326e63 fd:FileDescriptor[106]
08-26 21:10:42.572  6812  7171 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e3d1492 impl:android.net.LocalSocketImpl@37326e63 fd:FileDescriptor[106]
08-26 21:10:42.572  6812  7171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1334)
08-26 21:10:42.572  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:42.572  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:42.572  3219  3277 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 21:10:42.572  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.572  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:42.572  3219  3281 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 21:10:42.582  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:42.582  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.582  1018  1139 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 21:10:42.582  3219  3219 V BluetoothOppManager: cleanUp...
,08-26 21:10:42.582  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.582  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.582  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.582  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:10:42.582  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.582  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:42.592  4815  4815 D BluetoothPbap: Proxy object disconnected
08-26 21:10:42.592  4815  4815 D PbapServerProfile: Bluetooth service disconnected
,08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:10:42.592  3219  3281 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-26 21:10:42.592  3219  3281 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-26 21:10:42.592  3219  3281 W bt-btif : invalid rfc slot id: 4
,08-26 21:10:42.592  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:42.592  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:42.602  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:42.602  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:42.602  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 21:10:42.602  1018  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 21:10:42.602  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:42.602  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:42.602  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:42.602  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:42.622  7181  7181 E Zygote  : MountEmulatedStorage(),
08-26 21:10:42.622  7181  7181 E Zygote  : v2
08-26 21:10:42.622  7181  7181 I libpersona: KNOX_SDCARD checking this for 10055
08-26 21:10:42.622  7181  7181 I libpersona: KNOX_SDCARD not a persona,
,08-26 21:10:42.622  7181  7181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:42.622  1018  1139 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7181 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-26 21:10:42.622  7181  7181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:42.632  7181  7181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 21:10:42.642   325   325 I art     : Explicit concurrent mark sweep GC freed 8678(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 20.994ms
,08-26 21:10:42.652  7181  7181 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:10:42.652  7181  7181 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:42.652   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.426ms
,08-26 21:10:42.672  7181  7181 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 21:10:42.672   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.499ms
,08-26 21:10:42.712  7181  7181 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 21:10:42.712  7181  7181 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-26 21:10:42.712  7181  7181 D UserAnalysis: Create SecureDbHelper
,08-26 21:10:42.722  7181  7181 D IntelligenceServiceApplication: onCreate()
,08-26 21:10:42.722  1018  1522 I ActivityManager: Killing 6777:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-26 21:10:42.732  1018  1522 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 21:10:42.732  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:42.732  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:42.732  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:42.732  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:42.732  7181  7181 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 21:10:42.742  7196  7196 E Zygote  : MountEmulatedStorage()
,08-26 21:10:42.742  7196  7196 E Zygote  : v2
08-26 21:10:42.742  7196  7196 I libpersona: KNOX_SDCARD checking this for 10105
08-26 21:10:42.742  7196  7196 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:42.742  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:42.742  1018  1522 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7196 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 21:10:42.752  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:42.752  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 21:10:42.752  7181  7181 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-26 21:10:42.752  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 21:10:42.752  7181  7181 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 21:10:42.762  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:42.772  7196  7196 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:42.772  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 21:10:42.772  3219  3277 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 21:10:42.772  3219  3277 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 21:10:42.772  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 21:10:42.772  3219  3277 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 21:10:42.782  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 21:10:42.782  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:42.782  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.782  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.782  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.782  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:42.782  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:42.782  1018  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.782  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.782  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.782  3219  3219 D HeadsetService: Received stop request...Stopping profile...
08-26 21:10:42.782  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.782  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 21:10:42.782  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:42.782  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:42.782  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 21:10:42.782  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 21:10:42.782  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.782  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.792  3219  3219 D A2dpService: Received stop request...Stopping profile...
08-26 21:10:42.792  4815  4815 D HeadsetProfile: Bluetooth service disconnected
08-26 21:10:42.792  3219  3347 D A2dpStateMachine: Exit Disconnected: -1
,08-26 21:10:42.792  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.792  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.792  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-26 21:10:42.792   292   292 E SMD     : DCD OFF
,08-26 21:10:42.792  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 21:10:42.792  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 21:10:42.792  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 21:10:42.792  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.792  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.792  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:42.792  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.792  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.792  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.792  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:42.792  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 21:10:42.802  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 21:10:42.802  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 21:10:42.802  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 21:10:42.802  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.802  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:10:42.802  4815  4815 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:42.802  4815  4815 D A2dpProfile: Bluetooth service disconnected
,08-26 21:10:42.802  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.802  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.802  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.802  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.802  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:42.802  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:42.802  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-26 21:10:42.802  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 21:10:42.802   279  1016 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:10:42.802  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.802  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 21:10:42.812  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.812  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:42.812  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:42.812  1660  2528 V NativeCrypto: Read error: ssl=0xb7a85a48: I/O error during system call, Connection timed out
08-26 21:10:42.812  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 21:10:42.812  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:42.812  3219  3277 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 21:10:42.812  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.812  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:42.812  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 21:10:42.812  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.812  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.812  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.812  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.812  1660  2528 V NativeCrypto: SSL shutdown failed: ssl=0xb7a85a48: I/O error during system call, Broken pipe
,08-26 21:10:42.812  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 21:10:42.812  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:42.812  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:42.812  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:42.812  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:42.812  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 21:10:42.822  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:42.822  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:10:42.822  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:42.822  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-26 21:10:42.822  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-26 21:10:42.822  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 21:10:42.822  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:42.822  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:42.822  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-26 21:10:42.822  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:10:42.822  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 21:10:42.822  1018  1514 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-26 21:10:42.822  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 21:10:42.822  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 21:10:42.822  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:42.822  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:42.822  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 21:10:42.822  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:42.822  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-26 21:10:42.822  1018  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 21:10:42.832  1018  1735 I qtaguid : Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
08-26 21:10:42.832  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 21:10:42.832  3219  3277 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 21:10:42.832  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 21:10:42.832  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:42.832  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 21:10:42.842  1018  1735 I qtaguid : Untagging socket 351
,08-26 21:10:42.842  1018  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 21:10:42.842  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 21:10:42.842  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:42.842  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-26 21:10:42.842  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:10:42.852  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:10:42.852  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.852  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.852  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:42.852  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-26 21:10:42.852  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 21:10:42.862  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 21:10:42.862  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 21:10:42.862  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 21:10:42.862  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:10:42.862  1018  1048 D WifiDisplayController: disconnect
08-26 21:10:42.862  1018  1048 D WifiDisplayController: updateConnection
08-26 21:10:42.862  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:10:42.862  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:10:42.862  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 21:10:42.862  1018  1127 E WifiNative-wlan0: do suspend true
08-26 21:10:42.862  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 21:10:42.862  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 21:10:42.862  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 21:10:42.862  1018  1126 D WifiP2pService: P2pDisablingState
08-26 21:10:42.862  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 21:10:42.862  1018  1126 D WifiP2pService: p2p socket connection lost
08-26 21:10:42.862  1018  1126 D WifiP2pService: P2pDisabledState
08-26 21:10:42.862  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 21:10:42.862  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
08-26 21:10:42.862  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:10:42.862  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 21:10:42.862  3219  3219 D HidService: Received stop request...Stopping profile...
08-26 21:10:42.862  3219  3219 D HidService: Stopping Bluetooth HidService
08-26 21:10:42.862  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:10:42.862  3219  3219 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 21:10:42.862  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:10:42.862  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:42.872  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 21:10:42.872  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:42.872  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 21:10:42.872  3219  3219 D HealthService: Received stop request...Stopping profile...
,08-26 21:10:42.872  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:42.872  4815  4815 D BluetoothInputDevice: Proxy object disconnected
08-26 21:10:42.872  4815  4815 D HidProfile: Bluetooth service disconnected
08-26 21:10:42.872  3219  3219 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:42.872  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 21:10:42.872  3219  3348 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 21:10:42.872  3219  3219 I GKI_LINUX: GKI_exit_task 2 done
08-26 21:10:42.872  3219  3219 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 21:10:42.872  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 21:10:42.872  1018  1320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:10:42.872  3219  3219 D PanService: Received stop request...Stopping profile...
08-26 21:10:42.872  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:42.872  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 21:10:42.882  4815  4815 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:10:42.882  4815  4815 D PanProfile: Bluetooth service disconnected
08-26 21:10:42.882   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:10:42.882  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 21:10:42.882   279  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 21:10:42.882   279  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:10:42.882  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 21:10:42.882  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:42.882  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 21:10:42.882  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:42.882  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-26 21:10:42.882  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-26 21:10:42.882  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 21:10:42.892  1018  1129 V NetworkStats: performPollLocked() took 5ms
08-26 21:10:42.882  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 21:10:42.882  3219  3219 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:10:42.882  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 21:10:42.892  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.892  1395  1395 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.892  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.892  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:42.892  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.892  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:42.892  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-26 21:10:42.902  1018  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:42.902  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:42.902  1177  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 21:10:42.902  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:42.902  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.902  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.902  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.902  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 21:10:42.902  1483  1483 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 21:10:42.902  1483  1483 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:10:42.902  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 21:10:42.902  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 21:10:42.902  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 21:10:42.902  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 21:10:42.912  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:42.912  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:42.912  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.912  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.912  4815  4815 D BluetoothMap: Proxy object disconnected
08-26 21:10:42.912  4815  4815 D MapProfile: Bluetooth service disconnected
08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.912  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.912  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:42.912  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:42.912  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 21:10:42.912  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 21:10:42.912  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 21:10:42.912  3219  3219 D SapService: Received stop request...Stopping profile...
08-26 21:10:42.912  3219  3219 D SapService: Stopping Bluetooth SapService
08-26 21:10:42.912  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:42.922  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 21:10:42.922  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 21:10:42.922  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:42.922  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:10:42.922  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:42.922  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 21:10:42.922  1018  1130 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:10:42.922  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 21:10:42.922  1018  1124 V NetworkStats: updateIfacesLocked()
,08-26 21:10:42.922  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 21:10:42.922  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:42.922  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 21:10:42.922  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 21:10:42.922  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 21:10:42.932  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:42.932  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:42.932  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.932  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:42.932  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:42.932  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:10:42.932  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:10:42.932  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:42.932  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:42.932  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:10:42.932  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 21:10:42.932  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.932  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:42.932  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 21:10:42.932  4815  4815 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 21:10:42.932  4815  4815 D SapProfile: Bluetooth service disconnected
,08-26 21:10:42.932  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:42.932  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:42.932  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:42.932  1018  1124 V NetworkStats: performPollLocked() took 4ms
08-26 21:10:42.932  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 21:10:42.932  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 21:10:42.932  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:42.932  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:42.932  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 21:10:42.932  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-26 21:10:42.932  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:42.932  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:42.942  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.942  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 21:10:42.942  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 21:10:42.942  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:42.942   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 21:10:42.942  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:42.942   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 21:10:42.942  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:42.942  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 21:10:42.942  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 21:10:42.942  3219  3277 D BluetoothAdapterProperties: Setting state to 10
08-26 21:10:42.942  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 21:10:42.942  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:42.942  3219  3277 D BluetoothAdapterService: updateAdapterState state is 10
08-26 21:10:42.942  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:42.942  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-26 21:10:42.942  3219  3277 I BluetoothAdapterState: Entering OffState
08-26 21:10:42.942  4815  4830 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 21:10:42.942  4815  4830 D Bluetoothsap: Unbinding service...
,08-26 21:10:42.942  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 21:10:42.942  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte,
08-26 21:10:42.942  7196  7221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-26 21:10:42.942  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 21:10:42.942  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 21:10:42.942  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:42.952  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.952  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:42.952  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:42.952  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:42.952  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:42.962  1605  1622 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:42.962  1605  1622 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:42.962  4815  4824 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 21:10:42.972   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 21:10:42.972   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:42.982  7196  7221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-26 21:10:42.982  1395  1395 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 21:10:42.982  3219  3234 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:42.982  3219  3234 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:42.982  4815  4830 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:42.982  4815  4824 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 21:10:42.982  6812  6823 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:42.982  6812  6823 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 21:10:42.982  6812  6823 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 21:10:42.982  6812  6823 D BluetoothLeAdvertiser: Exit stop advertising
08-26 21:10:42.982  6812  6823 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 21:10:42.982  6812  6823 D BluetoothLeScanner: Exiting stopAllScan
,08-26 21:10:42.992  3219  3326 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:42.992  1177  5820 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:42.992  1177  5820 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.002  1464  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:43.002  1464  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.002  1660  1669 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:43.002  1660  1669 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.002  1457  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:43.002  1457  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.002  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:43.002  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.012  4815  7225 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:43.012  4815  7225 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.012  1395  1395 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 21:10:43.012  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:10:43.012  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 21:10:43.012  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 21:10:43.012  4815  4830 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 21:10:43.022  1483  1500 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:43.022  1483  1500 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:43.022  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:43.022  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-26 21:10:43.022  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 21:10:43.032  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 21:10:43.032  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:43.032  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 21:10:43.042  1998  1998 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:10:43.042  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:43.042  1018  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 21:10:43.042  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 21:10:43.042  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:43.042  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 21:10:43.052  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:43.052  1395  1395 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-26 21:10:43.052  1395  1395 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 21:10:43.052  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.052  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.052  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:10:43.052  1395  1395 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 21:10:43.052  1395  1395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 21:10:43.052  1395  1395 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 21:10:43.052  1018  1130 D Tethering: InitialState.processMessage what=4
08-26 21:10:43.052  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:43.052  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.052  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.052  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:43.062  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.062  1018  1130 E Tethering: No numeric data
,08-26 21:10:43.062  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.062  1018  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-26 21:10:43.062  1018  1130 D Tethering: clearTetheredNotification()
08-26 21:10:43.062  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:43.062  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:43.062  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.062  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.062  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:10:43.062  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 21:10:43.062  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:43.062  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 21:10:43.062  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:10:43.062  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 21:10:43.062  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.062  1018  1124 V NetworkStats: performPollLocked() took 3ms
08-26 21:10:43.062  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:43.062  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.072  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:43.072  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:43.072  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.072  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.072  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.072  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.072  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.072  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 21:10:43.072  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.072  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.082  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.082  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.082  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.082  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.082  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.082  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.082  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 21:10:43.082  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.092  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.092  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.092  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.092  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.092  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.092  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.092  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.092  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 21:10:43.092  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 21:10:43.122  1395  1395 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.v.a(PG,:1161)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.152  7196  7196 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:43.152  7196  7196 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:43.162  1018  1514 I ActivityManager: Killing 6771:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-26 21:10:43.172  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:43.172  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:10:43.172  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.172  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.172  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 21:10:43.172  2191  2191 I Hs20UtilService: Starting #8
08-26 21:10:43.172  2191  2216 I Hs20UtilService: Message received 5007
08-26 21:10:43.172  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:10:43.182  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 21:10:43.182  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 21:10:43.182  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 21:10:43.182  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:43.182  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 21:10:43.182  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 21:10:43.192  1395  1395 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 21:10:43.192  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 21:10:43.202  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 21:10:43.202  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.202  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:43.202  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:10:43.202  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 21:10:43.202  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 21:10:43.202  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:43.202  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 21:10:43.202  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 21:10:43.202  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-26 21:10:43.202  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.202  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.202  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.202  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.222  7249  7249 E Zygote  : MountEmulatedStorage()
08-26 21:10:43.222  7249  7249 E Zygote  : v2
08-26 21:10:43.222  7249  7249 I libpersona: KNOX_SDCARD checking this for 10064
08-26 21:10:43.222  7249  7249 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:43.222  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:43.222  1018  1030 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7249 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:43.232  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:43.232  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:43.232  7196  7243 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 21:10:43.252  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:43.252  7249  7249 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:43.262  1018  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 21:10:43.262  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.262  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:43.262  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 21:10:43.272  7249  7249 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 21:10:43.292  7249  7249 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:43.292  7249  7249 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 21:10:43.292  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 21:10:43.292  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 21:10:43.302  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:43.302  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 21:10:43.302  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:10:43.302  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:43.312  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:43.312  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:43.312  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:43.312  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:43.312  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 21:10:43.312  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:43.312  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 21:10:43.312  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 21:10:43.312  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:43.312  1605  2074 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:10:43.312  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:43.322  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 21:10:43.322  7249  7249 D FileShare-Client: Outbound.stopDelayTimer - ,
,08-26 21:10:43.322  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 21:10:43.332  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.332  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.332  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.332  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.342  7266  7266 E Zygote  : MountEmulatedStorage()
08-26 21:10:43.342  1018  1321 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7266 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:10:43.342  7266  7266 E Zygote  : v2
08-26 21:10:43.342  1018  1321 I ActivityManager: Killing 6845:com.wsomacp/u0a23 (adj 15): empty #21
08-26 21:10:43.342  7266  7266 I libpersona: KNOX_SDCARD checking this for 10065
08-26 21:10:43.342  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:43.342  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:43.352  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:43.352  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:43.362  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:43.362  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:43.392  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:43.392  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.392  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 21:10:43.392  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 21:10:43.392  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 21:10:43.402  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.402  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.402  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.402  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.412  1018  1030 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7281 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 21:10:43.412  1018  1030 I ActivityManager: Killing 6877:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-26 21:10:43.412  7281  7281 E Zygote  : MountEmulatedStorage()
08-26 21:10:43.412  7281  7281 I libpersona: KNOX_SDCARD checking this for 10102
08-26 21:10:43.412  7281  7281 E Zygote  : v2
08-26 21:10:43.412  7281  7281 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:43.412  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:43.422  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:43.422  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 21:10:43.422  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:43.422  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-26 21:10:43.432  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:43.432  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:43.442  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:43.452  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:43.452  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-26 21:10:43.452  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-26 21:10:43.452  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-26 21:10:43.452  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=533)
,08-26 21:10:43.462  7281  7281 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 21:10:43.552  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:43.662  1018  3300 D SSRM:n  : SIOP:: AP = 400
,08-26 21:10:43.672  7281  7301 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 21:10:43.672  7281  7301 I Babel_SMS: MmsConfig.loadMmsSettings
08-26 21:10:43.672  7281  7301 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 21:10:43.672  7281  7301 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 21:10:43.702  7281  7301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 21:10:43.702  7281  7301 I Babel_SMS: MmsConfig.loadFromResources
,08-26 21:10:43.702  7281  7301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 21:10:43.702  7281  7301 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 21:10:43.722  1018  1321 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 21:10:43.722  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 21:10:43.722  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.722  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 21:10:43.722  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 21:10:43.752  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:10:43.762  7281  7281 I Babel_Crash: startup - clean
,08-26 21:10:43.792  1018  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 21:10:43.792  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:43.792  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.792  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.792  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:43.792  2191  2191 I Hs20UtilService: Starting #9
,08-26 21:10:43.792  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:10:43.792  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 21:10:43.802  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:43.802  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:10:43.802  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 21:10:43.802  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 21:10:43.802  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:10:43.802  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 21:10:43.802  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:43.812  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:43.812  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:43.812  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.812  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.812  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:43.812  7281  7281 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 21:10:43.812  2191  2191 I Hs20UtilService: Starting #10
,08-26 21:10:43.812  2191  2216 I Hs20UtilService: Message received 5011
08-26 21:10:43.812  7281  7281 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 21:10:43.822  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 21:10:43.822  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:10:43.822  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:43.822  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:10:43.822  7281  7281 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-26 21:10:43.822  7281  7281 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 21:10:43.832  7281  7281 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 21:10:43.832  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.832  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.832  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.832  1018  1045 D Tethering: interfaceRemoved wlan0
08-26 21:10:43.832  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 21:10:43.832  7281  7281 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 21:10:43.832  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.832  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.832  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.832  7281  7281 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 21:10:43.832  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.832  7281  7281 W AudioCapabilities: Unsupported mime audio/evrc
08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.842  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.842  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:43.842  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.852  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.852  7281  7281 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 21:10:43.852  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.852  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.852  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.852  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.862  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.862  7281  7281 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 21:10:43.862  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-26 21:10:43.862  7281  7281 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 21:10:43.862  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 21:10:43.862  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.862  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.872  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 21:10:43.872  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.872  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.872  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.872  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 21:10:43.872  7281  7281 W VideoCapabilities: Unsupported mime video/mp43
,08-26 21:10:43.872  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:43.872  1018  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 21:10:43.872  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:10:43.882  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.882  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.882  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:10:43.882  7281  7281 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 21:10:43.882  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:43.882  7281  7281 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 21:10:43.892  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:43.892  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:43.892  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:43.892  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 21:10:43.902  7281  7281 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 21:10:43.902  1018  1514 W ActivityManager: userId = 0, bbcId = -10000,
08-26 21:10:43.902  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.902  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.912  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.912  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.912  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.912  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:43.912  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.912  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 21:10:43.912  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:43.912  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:43.922  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:43.922  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:43.922  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:43.922  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 21:10:43.922  2191  2191 I Hs20UtilService: Starting #11
,08-26 21:10:43.922  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:10:43.922  2191  2216 I Hs20UtilService: Message received 5011
08-26 21:10:43.922  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
08-26 21:10:43.922  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:10:43.932  1018  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 21:10:43.932  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.932  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.932  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:43.932  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:43.942  7306  7306 E Zygote  : MountEmulatedStorage()
08-26 21:10:43.942  7306  7306 E Zygote  : v2
08-26 21:10:43.942  7306  7306 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:10:43.942  7306  7306 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:43.942  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:43.952  1018  1514 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7306 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 21:10:43.952  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:43.952  1018  1045 D Tethering: interfaceRemoved p2p0
08-26 21:10:43.952  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 21:10:43.952  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:43.952  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 21:10:43.952  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 21:10:43.962  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 21:10:43.962  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 21:10:43.972  1018  1490 I ActivityManager: Killing 6914:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 21:10:43.972  7281  7281 I vclib   : onServiceConnected
,08-26 21:10:43.982  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:43.982  7306  7306 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.012  7306  7306 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 21:10:44.012  7306  7306 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 21:10:44.012  7306  7306 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 21:10:44.022  7306  7306 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 21:10:44.022  7306  7306 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 21:10:44.022  7306  7306 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 21:10:44.022  7306  7306 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:44.032  1018  1031 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-26 21:10:44.032  1018  1031 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-26 21:10:44.032  1018  1031 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-26 21:10:44.032  1018  1031 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-26 21:10:44.042  1018  1031 I ActivityManager: Killing 6944:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 21:10:44.042  7306  7321 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 21:10:44.042  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 21:10:44.052  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.052  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:44.052  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:44.052  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.062  7323  7323 E Zygote  : MountEmulatedStorage(),
08-26 21:10:44.062  7323  7323 E Zygote  : v2
08-26 21:10:44.062  7323  7323 I libpersona: KNOX_SDCARD checking this for 10001,
08-26 21:10:44.062  7323  7323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:44.062  7323  7323 I libpersona: KNOX_SDCARD not a persona,
,08-26 21:10:44.062  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7323 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:44.072  7323  7323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:44.072  7323  7323 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:44.092  7323  7323 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:44.092  7323  7323 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.162  1018  1522 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 21:10:44.172  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.172  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.172  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.172  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.182  1018  1522 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7340 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 21:10:44.182  1018  1522 I ActivityManager: Killing 6553:com.android.mms/u0a41 (adj 15): empty #21
,08-26 21:10:44.182  7340  7340 E Zygote  : MountEmulatedStorage()
08-26 21:10:44.182  7340  7340 E Zygote  : v2
08-26 21:10:44.182  7340  7340 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:10:44.182  7340  7340 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:44.192  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:44.192  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:44.192  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:44.202  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 21:10:44.212  7340  7340 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.252  7340  7340 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 21:10:44.282  1018  1514 D CountryDetector: No listener is left
,08-26 21:10:44.382  7340  7340 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 21:10:44.402  7340  7340 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
08-26 21:10:44.402   341   341 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 21:10:44.402  7340  7340 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:44.412  7340  7340 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 21:10:44.412  7340  7340 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 21:10:44.412  7340  7340 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 21:10:44.412  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 21:10:44.412  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.412  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.412  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.422  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.432  7356  7356 E Zygote  : MountEmulatedStorage()
08-26 21:10:44.432  1018  1494 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7356 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:10:44.432  7356  7356 E Zygote  : v2
08-26 21:10:44.432  7356  7356 I libpersona: KNOX_SDCARD checking this for 10008
08-26 21:10:44.432  7356  7356 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:44.442  7356  7356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:44.432  1018  1494 I ActivityManager: Killing 6970:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 21:10:44.442  7356  7356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:44.442  7356  7356 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 21:10:44.462  7356  7356 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:44.462  7356  7356 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.542  1018  1514 I ActivityManager: Killing 6343:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 21:10:44.552  1018  1320 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 21:10:44.552  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 21:10:44.552  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:44.552  1018  1320 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:44.552  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 21:10:44.572  1822  1822 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 21:10:44.572  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 21:10:44.572  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-26 21:10:44.572  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:44.582  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:44.582  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:10:44.582  1822  2810 I iu.UploadsManager: num queued entries: 0
,08-26 21:10:44.582  1822  2810 I iu.UploadsManager: num updated entries: 0
,08-26 21:10:44.582  1822  2810 I iu.SyncManager: NEXT; no task
,08-26 21:10:44.592  1822  1822 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:10:44.592  1822  1822 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-26 21:10:44.602  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 21:10:44 GMT+02:00 2016
,08-26 21:10:44.602  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 21:10:44.602  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 21:10:44.602  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:44.602  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:44.602  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 21:10:44.602  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 21:10:44.612  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 21:10:44.612  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 21:10:44.612  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 21:10:44.612  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.612  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.612  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.612  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.622  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 21:10:44.622  2814  7372 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 21:10:44.622  2814  7372 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 21:10:44.632  7373  7373 E Zygote  : MountEmulatedStorage()
08-26 21:10:44.632  7373  7373 I libpersona: KNOX_SDCARD checking this for 10031
,08-26 21:10:44.632  7373  7373 E Zygote  : v2
08-26 21:10:44.632  7373  7373 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:44.632  7373  7373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 21:10:44.632  1018  1504 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7373 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-26 21:10:44.632  2814  7372 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
08-26 21:10:44.632  2814  7372 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END,
08-26 21:10:44.632  7373  7373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:44.632  7373  7373 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 21:10:44.642  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 21:10:44.652  7373  7373 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 21:10:44.662  7373  7373 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.692  7373  7373 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 21:10:44.692  1018  1504 I ActivityManager: Killing 6986:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-26 21:10:44.712  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 21:10:44.712  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.712  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.712  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.712  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.712  2752  7388 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 21:10:44.722  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 21:10:44.732  7389  7389 E Zygote  : MountEmulatedStorage()
08-26 21:10:44.732  7389  7389 E Zygote  : v2
08-26 21:10:44.732  7389  7389 I libpersona: KNOX_SDCARD checking this for 10032
08-26 21:10:44.732  7389  7389 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:44.732  2752  7388 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-26 21:10:44.732  7389  7389 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:44.732  2752  7388 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 21:10:44.732  7389  7389 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:44.732  2752  7388 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 21:10:44.732  1018  1321 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7389 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:44.742  7389  7389 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 21:10:44.742  2752  7388 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 21:10:44.762  7389  7389 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:44.772  7389  7389 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.792  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 21:10:44.822  7389  7404 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 21:10:44.822  7389  7404 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 21:10:44.832  7389  7389 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 21:10:44.832  7389  7404 D SPPClientService: PushLog.txt file is not deleted.
08-26 21:10:44.832  7389  7404 D SPPClientService: PushLog.txt file is not deleted.
08-26 21:10:44.832  7389  7404 D SPPClientService: ============PushLog. stop!
,08-26 21:10:44.832  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 21:10:44.832  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:44.832  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:44.832  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:44.832  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:44.852  7406  7406 E Zygote  : MountEmulatedStorage(),
08-26 21:10:44.852  7406  7406 E Zygote  : v2
08-26 21:10:44.852  7406  7406 I libpersona: KNOX_SDCARD checking this for 10036
,08-26 21:10:44.852  7406  7406 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:44.852  7406  7406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:44.852  1018  1265 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7406 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:44.852  7406  7406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:10:44.852  1018  1265 I ActivityManager: Killing 7001:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-26 21:10:44.852  7406  7406 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 21:10:44.852  1018  1490 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 21:10:44.852  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 21:10:44.862  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:44.862  1018  1490 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 21:10:44.862  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 21:10:44.882  7406  7406 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:44.882  7406  7406 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:44.882   325   325 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 30.591ms
,08-26 21:10:44.892  7389  7415 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 21:10:44.902   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.625ms,
,08-26 21:10:44.922   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.346ms
,08-26 21:10:44.922  7406  7406 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3fb19215
,08-26 21:10:44.932  7406  7406 I SA      : [SSP] onCreated
,08-26 21:10:44.942  7406  7406 I SA      : [TPM] There is no property file
,08-26 21:10:44.952  7406  7406 I SA      : [SCU] isHaveSA() - false
,08-26 21:10:44.952  7406  7406 I SA      : [TPM] getModelProperty : null
08-26 21:10:44.952  7406  7406 I SA      : [TPM] getCSCProperty : null
,08-26 21:10:44.952  7406  7406 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 21:10:44.952  7406  7406 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 21:10:44.952  7406  7406 I SA      : [DM] TFT FEATURE: false
,08-26 21:10:44.962  7406  7406 I SA      : [DM] init START
,08-26 21:10:44.962  7406  7406 I SA      : [DM] This device is not a Vodafone
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 21:10:44.972  7406  7406 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-26 21:10:44.982  7406  7406 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-26 21:10:44.992  7406  7406 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 21:10:44.992  7406  7406 I SA      : [SCU] isHaveSA() - false
08-26 21:10:44.992  7406  7406 I SA      : support phone number id : false
08-26 21:10:44.992  7406  7406 I SA      : [DM] Supports Ref Jpn : true
,08-26 21:10:44.992  7406  7406 I SA      : [DM] init END
,08-26 21:10:44.992  7406  7406 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 21:10:45.002  7406  7406 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 21:10:45.002  7406  7406 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 21:10:45.002  7406  7406 I SA      : [SLFUCHKMGR] constructor called
,08-26 21:10:45.012  7406  7406 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 21:10:45.012  7406  7406 I SA      : [OR] == isSIMCardReady false ==
,08-26 21:10:45.012  7406  7406 I SA      : [SCU] == networkStateCheck == false
,08-26 21:10:45.012  7406  7406 I SA      : [OR] onReceive END
,08-26 21:10:45.012  1018  1514 I ActivityManager: Killing 7086:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 21:10:45.022  1223  1223 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE,
,08-26 21:10:45.032  1757  1757 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 21:10:45.032  2671  2679 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-26 21:10:45.042  1757  1757 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 21:10:45.042  1757  1757 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-26 21:10:45.042  1757  1757 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 21:10:45.042  1757  1757 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 21:10:45.042  1757  1757 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 21:10:45.052  1757  1757 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 21:10:45.052  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 21:10:45.052  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.052  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.052  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.052  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.072  7428  7428 E Zygote  : MountEmulatedStorage()
08-26 21:10:45.072  7428  7428 E Zygote  : v2
08-26 21:10:45.072  7428  7428 I libpersona: KNOX_SDCARD checking this for 10077
08-26 21:10:45.072  7428  7428 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:45.072  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:45.072  1018  1320 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7428 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 21:10:45.072  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:45.082  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-26 21:10:45.092  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:45.092  7428  7428 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:45.272  1018  1494 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 21:10:45.272  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 21:10:45.272  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:45.272  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:45.272  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 21:10:45.272  1018  1522 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 21:10:45.272  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.272  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:45.272  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.272  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:45.292  7446  7446 E Zygote  : MountEmulatedStorage(),
,08-26 21:10:45.292  7446  7446 E Zygote  : v2,
08-26 21:10:45.292  7446  7446 I libpersona: KNOX_SDCARD checking this for 10110
08-26 21:10:45.292  7446  7446 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:45.292  7446  7446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:45.292  1018  1522 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7446 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:10:45.292  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 21:10:45.292  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 21:10:45.292  7446  7446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:10:45.292  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:45.292  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:45.292  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 21:10:45.302  7281  7445 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 21:10:45.302  7446  7446 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 21:10:45.302  1018  1514 I ActivityManager: Killing 7104:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 21:10:45.322  7446  7446 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:45.322  7446  7446 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:45.402   341   341 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 21:10:45.432  1018  1139 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 21:10:45.542  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 21:10:45.542  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 21:10:45.542  1018  1030 D SecContentProvider2: mCursor = null
,08-26 21:10:45.552  1018  1030 D WifiService: setWifiEnabled: true pid=6812, uid=10170
,08-26 21:10:45.552  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 21:10:45.552  1018  1030 W WifiService: Failed getting userId using ActivityManagerNative
08-26 21:10:45.552  1018  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:10:45.552  1018  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 21:10:45.552  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 21:10:45.552  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 21:10:45.552  1018  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 21:10:45.552  1018  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 21:10:45.552  1018  1030 D SettingsProvider: name = wifi_on,
,08-26 21:10:45.552  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################,
,08-26 21:10:45.582  7446  7446 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 21:10:45.582  7446  7446 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
,08-26 21:10:45.582  7446  7446 I GAv4    :   adb logcat -s GAv4
,08-26 21:10:45.622  7446  7446 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:45.622  1018  1490 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 21:10:45.622   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 21:10:45.622   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:45.622  7446  7464 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 21:10:45.622   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 21:10:45.632   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:45.632  7446  7464 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 21:10:45.632  7446  7446 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:45.642  7446  7467 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:45.652   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 21:10:45.652   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:45.652  7446  7468 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 21:10:45.662   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 21:10:45.662   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:45.662  7446  7468 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 21:10:45.792   292   292 E SMD     : DCD OFF
,08-26 21:10:45.852  1018  1522 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 21:10:45.852  1018  1522 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 21:10:45.852  1018  1522 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 21:10:45.852  1018  1522 D BatteryService: stay LED for charging
,08-26 21:10:45.862  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 21:10:45.862  1018  1018 I MotionRecognitionService: Plugged
,08-26 21:10:45.862  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 21:10:45.862  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 21:10:45.862  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 21:10:45.862  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 21:10:45.872  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 21:10:45.882  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 21:10:45.892  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 21:10:45.892  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 21:10:45.892  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:45.892  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 21:10:45.892  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 21:10:45.892  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:45.902  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:45.902  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:45.922  7446  7446 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 21:10:45.932  1018  1045 D Tethering: interfaceAdded wlan0
,08-26 21:10:45.932  1018  1130 E Tethering: No numeric data
,08-26 21:10:45.942  1018  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 21:10:45.942  1018  1130 D Tethering: clearTetheredNotification()
,08-26 21:10:45.942  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:45.942  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 21:10:45.942  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:45.942  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:10:45.942  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:10:45.942  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 21:10:45.942  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 21:10:45.942  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:45.942  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:45.942  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-26 21:10:45.942  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:45.942  1018  1130 D Tethering: InitialState.processMessage what=4
,08-26 21:10:45.942  7446  7446 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6088-6090)
,08-26 21:10:45.942  7446  7446 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 21:10:45.952  1018  1130 E Tethering: No numeric data
,08-26 21:10:45.952  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:45.952  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:45.952  1018  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:10:45.952  1018  1130 D Tethering: clearTetheredNotification()
,08-26 21:10:45.952  1018  1045 D Tethering: interfaceAdded p2p0,
08-26 21:10:45.952  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:45.952  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
08-26 21:10:45.952  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:45.952  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:45.952  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:10:45.952  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:10:45.952  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 21:10:45.952  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:10:45.952  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 21:10:45.952  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:10:45.962   279  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 21:10:45.962   279  1016 D SoftapController: Softap fwReload - Ok
,08-26 21:10:45.962  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-26 21:10:45.962  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:45.962   279  1016 D CommandListener: Setting iface cfg
08-26 21:10:45.962   279  1016 D CommandListener: Trying to bring down wlan0
,08-26 21:10:45.962   279  1016 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:10:45.962  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:45.962  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:45.972  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 21:10:45.982  7446  7446 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e25bd24},
08-26 21:10:45.982  7446  7446 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 21:10:45.982  7446  7446 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 21:10:46.002  7446  7446 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 21:10:46.002  7446  7446 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 21:10:46.012  7446  7446 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 21:10:46.022  7493  7493 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-26 21:10:46.022  7493  7493 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 21:10:46.022  7446  7446 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 21:10:46.022  7446  7446 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 21:10:46.022  7446  7446 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 21:10:46.022  7446  7446 I Adreno-EGL: Local Branch: 
08-26 21:10:46.022  7446  7446 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 21:10:46.022  7446  7446 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 21:10:46.022  7446  7446 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 21:10:46.022  7493  7493 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 21:10:46.042  7493  7493 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-26 21:10:46.052   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7493,
08-26 21:10:46.052   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 21:10:46.052  7493  7493 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 21:10:46.052  7493  7493 I wpa_supplicant: ssSupport state is = 1
,08-26 21:10:46.052  7493  7493 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 21:10:46.052  7493  7493 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 21:10:46.052   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7493
,08-26 21:10:46.052   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 21:10:46.072  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:46.082  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.082  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:46.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.082  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:46.082  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 21:10:46.082  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 21:10:46.082  1177  1177 D HotspotTile: onReceive : 2, 0
,08-26 21:10:46.082  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:46.092  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:46.092  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:46.132  7446  7446 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 21:10:46.132  7446  7506 W cr.media: Requires BLUETOOTH permission
,08-26 21:10:46.142  7446  7446 I NSApplication: Starting up...
,08-26 21:10:46.142  1018  1031 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 21:10:46.152  1018  1490 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 21:10:46.152  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 21:10:46.162  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.162  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.162  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.162  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.172  7511  7511 E Zygote  : MountEmulatedStorage(),
,08-26 21:10:46.172  1018  1321 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7511 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-26 21:10:46.172  7511  7511 E Zygote  : v2
08-26 21:10:46.172  7511  7511 I libpersona: KNOX_SDCARD checking this for 10117
08-26 21:10:46.172  1018  1321 I ActivityManager: Killing 7055:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-26 21:10:46.172  7511  7511 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:46.172  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:46.182  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:46.182  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 21:10:46.202  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:46.202  7511  7511 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:46.222  7511  7511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 21:10:46.232   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 21:10:46.242  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 21:10:46.302  7493  7493 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 21:10:46.302  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 21:10:46.322  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-26 21:10:46.322   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7493
08-26 21:10:46.322   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 21:10:46.322  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 21:10:46.322  7493  7493 I wpa_supplicant: ssSupport state is = 1
08-26 21:10:46.322  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.322  7493  7493 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:10:46.322  7493  7493 E wpa_supplicant: SIM READ ERROR
08-26 21:10:46.322  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.322  7493  7493 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:10:46.322  7493  7493 E wpa_supplicant: SIM READ ERROR
08-26 21:10:46.322  7493  7493 I wpa_supplicant: Blacklist: Clear (all) 
08-26 21:10:46.322  7493  7493 I wpa_supplicant: wpa_default_ap_write_once
08-26 21:10:46.322  7493  7493 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 21:10:46.322  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.322  7493  7493 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 21:10:46.322  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.322  7493  7493 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:10:46.322  7493  7493 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 21:10:46.332  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:46.332  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:46.332  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:46.392  7493  7493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 21:10:46.402   341   341 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 21:10:46.552  7493  7493 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 21:10:46.552  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 21:10:46.572  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 21:10:46.572   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7493
08-26 21:10:46.572   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 21:10:46.572  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-26 21:10:46.572  7493  7493 I wpa_supplicant: ssSupport state is = 1
,08-26 21:10:46.592  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 21:10:46.592  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.592  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.592  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.592  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.602  7534  7534 E Zygote  : MountEmulatedStorage()
,08-26 21:10:46.602  7534  7534 E Zygote  : v2
08-26 21:10:46.602  7534  7534 I libpersona: KNOX_SDCARD checking this for 10121
08-26 21:10:46.602  7534  7534 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:46.612  7534  7534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:46.612  7493  7493 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 21:10:46.612  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 21:10:46.612  1018  1031 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7534 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 21:10:46.612  1018  1031 I ActivityManager: Killing 7017:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 21:10:46.612  7534  7534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:10:46.612  7534  7534 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:46.622  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 21:10:46.622   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7493
08-26 21:10:46.622   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 21:10:46.622  7493  7493 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 21:10:46.622  7493  7493 I wpa_supplicant: ssSupport state is = 1
08-26 21:10:46.622  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.622  7493  7493 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:10:46.622  7493  7493 E wpa_supplicant: SIM READ ERROR
08-26 21:10:46.622  7493  7493 I wpa_supplicant: wpa_default_ap_write_once,
08-26 21:10:46.622  7493  7493 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 21:10:46.622  7493  7493 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 21:10:46.622  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.622  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.622  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:10:46.622  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.622  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.622  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:10:46.632  7534  7534 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:46.632  7534  7534 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:46.652  7534  7534 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:10:46.652  7534  7534 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 21:10:46.652  7534  7534 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 21:10:46.662  7534  7534 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:46.672  7534  7534 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,08-26 21:10:46.682  7534  7534 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 21:10:46.682  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
08-26 21:10:46.682  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.682  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.682  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.682  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.702  1018  1494 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7552 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 21:10:46.702  7552  7552 E Zygote  : MountEmulatedStorage()
,08-26 21:10:46.702  7552  7552 E Zygote  : v2
08-26 21:10:46.702  7552  7552 I libpersona: KNOX_SDCARD checking this for 10141
,08-26 21:10:46.702  1018  1494 I ActivityManager: Killing 7033:com.android.calendar/u0a131 (adj 15): empty #21
08-26 21:10:46.702  7552  7552 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:46.702  7552  7552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:10:46.702  7552  7552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:46.702  7552  7552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:46.712  7493  7493 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 21:10:46.712  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 21:10:46.722  7552  7552 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:46.722  7552  7552 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:46.742  7552  7552 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 21:10:46.742  7552  7552 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:10:46.742  7552  7552 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 21:10:46.742  7552  7552 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 21:10:46.782  7493  7493 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 21:10:46.782  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 21:10:46.782  7493  7493 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 21:10:46.792  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-26 21:10:46.792  1018  1321 D RCPManagerService: exchangeData() failure , invalid userId
08-26 21:10:46.792  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 21:10:46.792  7493  7493 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-26 21:10:46.792  7493  7493 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:10:46.792  7493  7493 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 21:10:46.792  7493  7493 E wpa_supplicant: SIM READ ERROR
08-26 21:10:46.792  7493  7493 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 21:10:46.802  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 21:10:46.812  7493  7493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 21:10:46.832  7493  7493 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 21:10:46.832  1018  1522 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 21:10:46.832  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:46.842  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.842  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 21:10:46.842  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:46.842  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-26 21:10:46.842  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:46.842  1177  1177 D HotspotTile: onReceive : 3, 0
08-26 21:10:46.842  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 21:10:46.842  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:46.842  1018  1127 E WifiConfigStore: Not a HS20
,08-26 21:10:46.852  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:46.852  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:46.852  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:46.852  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:46.852  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:46.852  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:46.852  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:46.852  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 21:10:46.852  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 21:10:46.852  7493  7493 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 21:10:46.852  7493  7493 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 21:10:46.852  7493  7493 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 21:10:46.862  7493  7493 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 21:10:46.862  7493  7493 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 21:10:46.862  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 21:10:46.862  7493  7493 I wpa_supplicant: First Scan Start
,08-26 21:10:46.862  7493  7493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 21:10:46.862  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
08-26 21:10:46.862  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:10:46.862  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 21:10:46.862  1018  1127 I WifiNative-HAL: startHal
08-26 21:10:46.862  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f2c088c
08-26 21:10:46.862  1018  1127 I WifiNative-HAL: Could not start hal
,08-26 21:10:46.862  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 21:10:46.862  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 21:10:46.862  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 21:10:46.862  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 21:10:46.872   279  1016 D CommandListener: Setting iface cfg
08-26 21:10:46.872   279  1016 D CommandListener: Trying to bring up p2p0
,08-26 21:10:46.872  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 21:10:46.872  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:46.872  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 21:10:46.872  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 21:10:46.872  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 21:10:46.872  1018  1151 I WifiNative-HAL: startHal
08-26 21:10:46.872  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e1829bc
,08-26 21:10:46.872  1018  1151 I WifiNative-HAL: Could not start hal
08-26 21:10:46.872  1018  1151 E WifiScanningService: could not start HAL
08-26 21:10:46.872  1018  1018 D RttService: SCAN_AVAILABLE : 3
,08-26 21:10:46.872  1018  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:10:46.872  7493  7493 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 21:10:46.872  7493  7493 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 21:10:46.872  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:10:46.872  1018  1126 D WifiP2pService: P2pEnablingState
,08-26 21:10:46.872  7493  7493 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 21:10:46.872  1018  1127 E WifiStateMachine: Failed to set frequency band 0,
,08-26 21:10:46.882  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 21:10:46.882  1018  1127 D SecContentProvider2: mCursor = null
08-26 21:10:46.882  1018  1126 D WifiP2pService: P2pEnablingState{ what=143376 }
,08-26 21:10:46.882  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 21:10:46.882  1018  1126 D WifiP2pService: DefaultState{ what=143376 }
08-26 21:10:46.882  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:46.882  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 21:10:46.882  1018  1126 D WifiP2pService: P2p socket connection successful
08-26 21:10:46.882  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:46.882  1018  1126 D WifiP2pService: P2pEnabledState,
08-26 21:10:46.882  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 21:10:46.882  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 21:10:46.882  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-26 21:10:46.882  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 21:10:46.882  1018  1048 D WifiDisplayController: disconnect
,08-26 21:10:46.882  1018  1048 D WifiDisplayController: updateConnection
08-26 21:10:46.882  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 21:10:46.882  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:10:46.892  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:10:46.892  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 21:10:46.892  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 21:10:46.892  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 21:10:46.892  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 21:10:46.892  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-26 21:10:46.892  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 21:10:46.892  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 21:10:46.892  1018  1522 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:10:46.892  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 21:10:46.902  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  secondary type: null
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  wps: 0
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  grpcapab: 0
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  devcapab: 0
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  status: 3
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  wfdInfo: null
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-26 21:10:46.902  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-26 21:10:46.912  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 21:10:46.912  1018  1126 D WifiP2pService: InactiveState
,08-26 21:10:46.912  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-26 21:10:46.912  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 21:10:46.912  7493  7493 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 21:10:46.912  1018  1504 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 21:10:46.912  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.912  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.912  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:46.912  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.922  1018  1139 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 21:10:46.932  7577  7577 E Zygote  : MountEmulatedStorage()
08-26 21:10:46.932  7577  7577 I libpersona: KNOX_SDCARD checking this for 10068
08-26 21:10:46.932  7577  7577 E Zygote  : v2
08-26 21:10:46.932  7577  7577 I libpersona: KNOX_SDCARD not a persona
08-26 21:10:46.932  7577  7577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:46.932  1018  1514 D RCPManagerService: exchangeData() failure , invalid userId
08-26 21:10:46.932  7577  7577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:10:46.932  1018  1504 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7577 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-26 21:10:46.932  7577  7577 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 21:10:46.942  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.942  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:10:46.942  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:10:46.952  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 21:10:46.962  7577  7577 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 21:10:46.962  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-26 21:10:46.962  7577  7577 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:46.962  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 21:10:46.962  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.962  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 21:10:46.962  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:46.982  7594  7594 E Zygote  : MountEmulatedStorage(),
08-26 21:10:46.982  7594  7594 E Zygote  : v2
,08-26 21:10:46.982  7594  7594 I libpersona: KNOX_SDCARD checking this for 10009
08-26 21:10:46.982  7594  7594 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:46.982  7594  7594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:46.982  7594  7594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:46.982  7594  7594 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 21:10:46.992  1018  1265 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7594 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-26 21:10:46.992  1018  1265 I ActivityManager: Killing 6829:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 21:10:47.002  1018  1522 I ActivityManager: Killing 7129:com.android.vending/u0a26 (adj 15): empty #21
,08-26 21:10:47.022  7594  7594 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:47.032  7594  7594 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:47.162  1018  1031 I art     : Explicit concurrent mark sweep GC freed 68669(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 22MB/34MB, paused 2.405ms total 152.219ms
,08-26 21:10:47.182  7577  7577 D BadgeProvider: onCreate
,08-26 21:10:47.182  7577  7577 D BadgeProvider: DatabaseHelper
,08-26 21:10:47.202  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-26 21:10:47.202  1018  1320 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 21:10:47.202  7577  7589 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 21:10:47.202  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 21:10:47.202  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 21:10:47.222  7577  7589 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 21:10:47.222  7577  7589 D BadgeProvider: sendNotify, [notify] : null
08-26 21:10:47.222  7577  7589 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 21:10:47.222  7577  7589 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 21:10:47.222  7577  7589 D BadgeProvider: update, [UpdateCount] : 1
,08-26 21:10:47.222  1505  1505 D Launcher.Model: reloadBadges entered.
,08-26 21:10:47.242  1018  1490 I ActivityManager: Killing 7249:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-26 21:10:47.252  1018  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 21:10:47.252  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:47.252  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:47.252  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:47.252  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 21:10:47.252   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:10:47.252   279  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 21:10:47.252  2191  2191 I Hs20UtilService: Starting #12
08-26 21:10:47.252  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:10:47.252  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 21:10:47.252  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:10:47.252  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:47.262  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:10:47.272  1018  1265 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 21:10:47.272  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:47.272  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:47.272  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:47.272  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:47.272  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 21:10:47.272  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 21:10:47.282  2191  2191 I Hs20UtilService: Starting #13
08-26 21:10:47.282  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:47.282  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:10:47.282  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:10:47.282  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 21:10:47.282  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 21:10:47.282  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 21:10:47.292  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 21:10:47.292  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:47.292  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:10:47.292  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 21:10:47.292  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 21:10:47.292  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:10:47.292  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:47.292  1018  1265 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 21:10:47.292  1018  1265 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-26 21:10:47.292  1018  1265 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 21:10:47.292  1018  1265 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 21:10:47.292  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 21:10:47.302  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:47.302  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:47.302  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:47.302  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:47.312  7614  7614 E Zygote  : MountEmulatedStorage()
08-26 21:10:47.312  7614  7614 E Zygote  : v2,
08-26 21:10:47.312  7614  7614 I libpersona: KNOX_SDCARD checking this for 10064
08-26 21:10:47.312  7614  7614 I libpersona: KNOX_SDCARD not a persona,
,08-26 21:10:47.312  1018  1265 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7614 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 21:10:47.312  7614  7614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:47.312  7614  7614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:47.312  7614  7614 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:10:47.332  7614  7614 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:47.332  7614  7614 D ActivityThread: Added TimaKeyStore provider,
,08-26 21:10:47.342  7614  7614 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 21:10:47.352  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:47.352  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 21:10:47.352  1018  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7249/cgroup.procs: No such file or directory
,08-26 21:10:47.382  7614  7614 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 21:10:47.382  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:47.382  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:47.382  1018  1320 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:47.382  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 21:10:47.392  1018  1265 I ActivityManager: Killing 7181:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-26 21:10:47.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 21:10:48.022  5917  5917 D FactoryTest: Not factory mode
,08-26 21:10:48.022  5917  5917 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 21:10:48.022  5917  5917 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 21:10:48.022  5917  5917 D MTPRx   : still no open session command from host, so toast
,08-26 21:10:48.022  5917  5917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,08-26 21:10:48.022  5917  5917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
,08-26 21:10:48.032  5917  5917 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118181,
,08-26 21:10:48.032  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 21:10:48.032  1018  1030 I PersonaManagerService: PersonaId don't exist
08-26 21:10:48.032  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 21:10:48.032  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 21:10:48.032  1018  1030 W ActivityManager: userId = 0, bbcId = -10000,
,08-26 21:10:48.032  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 21:10:48.032  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,08-26 21:10:48.042  1018  1030 W ActivityManager: mDVFSHelper.acquire()
,08-26 21:10:48.062  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-26 21:10:48.072  7493  7493 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
08-26 21:10:48.072  7493  7493 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 21:10:48.072  7493  7493 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 21:10:48.072  7493  7493 I wpa_supplicant: Trying to associate with  'G700'
,08-26 21:10:48.072  7493  7493 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 21:10:48.072  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 21:10:48.072  1018  7567 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 21:10:48.082  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 21:10:48.082  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 21:10:48.082  1018  1030 D InputDispatcher: Focused application set to: xxxx
08-26 21:10:48.082  1018  1030 D InputDispatcher: Focus left window: 6812
,08-26 21:10:48.082  5917  5917 E MTPRx   : started activity for popup
,08-26 21:10:48.082  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 21:10:48.082  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 21:10:48.092  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 21:10:48.092  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 21:10:48.112  5917  5917 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 21:10:48.142  5917  5917 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 21:10:48.142  1018  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 21:10:48.142  1018  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 21:10:48.142  1018  1321 D InputDispatcher: Focused application set to: xxxx
,08-26 21:10:48.142  1018  1321 D InputDispatcher: Focus entered window: 6812
,08-26 21:10:48.152  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 21:10:48.152  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 21:10:48.152  1018  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 21:10:48.162  1018  1494 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9e2fc5 attribute=null, token = android.os.BinderProxy@136bf3d5
,08-26 21:10:48.182  5917  5917 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-26 21:10:48.182  7493  7493 E wpa_supplicant: Cmd 35605 not handled
,08-26 21:10:48.182  7493  7493 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 21:10:48.182  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.182  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 21:10:48.182  7493  7493 I wpa_supplicant: Associated with F4.99.3E
08-26 21:10:48.182  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.182  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:10:48.182  7493  7493 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 21:10:48.182  7493  7493 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 21:10:48.192  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 21:10:48.192  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.192  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.192  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:48.192  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 21:10:48.192  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.192  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-26 21:10:48.192  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 21:10:48.192  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 21:10:48.192  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-26 21:10:48.192  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:48.192  1018  1127 D SecContentProvider2: mCursor = null
08-26 21:10:48.192  5917  5917 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 21:10:48.192  5917  5917 D PhoneWindow: *FMB* installDecor flags : 8388610
08-26 21:10:48.192  1018  1130 E Tethering: No numeric data
08-26 21:10:48.192  1018  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 21:10:48.192  1018  1130 D Tethering: clearTetheredNotification()
08-26 21:10:48.192  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:48.192  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:48.192  7493  7493 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 21:10:48.192  7493  7493 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 21:10:48.192  7493  7493 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 21:10:48.192  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 21:10:48.192  7493  7493 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-26 21:10:48.192  7493  7493 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 21:10:48.202  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:48.192  7493  7493 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 21:10:48.202  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 21:10:48.202  7493  7493 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 21:10:48.202  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 21:10:48.202  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.202  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 21:10:48.202  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-26 21:10:48.202  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:10:48.202  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 21:10:48.202  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 21:10:48.202  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 21:10:48.202  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-26 21:10:48.202  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:48.202  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.202  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:48.202  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 21:10:48.212  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 21:10:48.212  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 21:10:48.212  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-26 21:10:48.212  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:48.212  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 21:10:48.222  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.222  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.222  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:10:48.222  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:48.222  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:48.222  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:48.222  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:48.222  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-26 21:10:48.232  2191  2191 I Hs20UtilService: Starting #14
,08-26 21:10:48.232  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:10:48.232  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:10:48.242   279  1016 D CommandListener: Setting iface cfg
,08-26 21:10:48.242  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 21:10:48.242  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 21:10:48.242  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 21:10:48.242  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 21:10:48.252  1018  1504 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 21:10:48.252  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 21:10:48.252  1018  1504 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 21:10:48.252  1018  1504 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 21:10:48.252  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 21:10:48.252  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 21:10:48.252  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:10:48.252  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:48.252  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:10:48.252  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 21:10:48.262  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:48.262  1018  1127 D SecContentProvider2: mCursor = null
08-26 21:10:48.262  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:48.262  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:10:48.262  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:48.262  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
08-26 21:10:48.262  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 21:10:48.272  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16e8a132 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@21ad5a60, 16908290=android.view.AbsSavedState$1@21ad5a60}, android:focusedViewId=100}]}]
08-26 21:10:48.272  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 21:10:48.272  6812  6812 V ActivityThread: updateVisibility : ActivityRecord{397c8cc4 token=android.os.BinderProxy@1762ff56 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 21:10:48.272  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 21:10:48.272  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 21:10:48.272  6812  6812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1762ff56 time:118421
,08-26 21:10:48.282  1018  1265 D PersonaManager: isKioskContainerExistOnDevice
,08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:48.292  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.292  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.292  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:48.292  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:48.302  1018  1127 E WifiNative-wlan0: do suspend false
,08-26 21:10:48.302  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 21:10:48.302  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 21:10:48.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 21:10:48.512  7633  7633 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
08-26 21:10:48.512  7633  7633 I dhcpcd  : version 5.5.6 starting
,08-26 21:10:48.522  7633  7633 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 21:10:48.552  1018  1490 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-26 21:10:48.552  1018  1490 D WifiService: setWifiEnabled: false pid=6812, uid=10170
08-26 21:10:48.552  1018  1490 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 21:10:48.552  1018  1490 D SecContentProvider2: mCursor = null
08-26 21:10:48.552  1018  1490 D SettingsProvider: name = wifi_on,
,08-26 21:10:48.562  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 21:10:48.572  7633  7633 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-26 21:10:48.572  7633  7633 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 21:10:48.572  7633  7633 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 21:10:48.572  7633  7633 I dhcpcd  : bssid match
08-26 21:10:48.572  1018  1127 E WifiNative-wlan0: do suspend true,
08-26 21:10:48.572  7633  7633 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-26 21:10:48.592  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-26 21:10:48.592  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 21:10:48.592   279  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:48.602  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.602  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.602  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 21:10:48.602  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 21:10:48.602  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:10:48.602  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-26 21:10:48.602   279  1016 E Netd    : no such netId 503,
08-26 21:10:48.602  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-26 21:10:48.602  1018  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 21:10:48.602  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.602  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 21:10:48.602  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 21:10:48.612  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:48.602  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:48.612  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-26 21:10:48.612  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.612  1018  1129 V NetworkStats: performPollLocked() took 5ms
08-26 21:10:48.612  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 21:10:48.612  1018  7631 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:48.612  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 21:10:48.612  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 21:10:48.612  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 21:10:48.612  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.612  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:48.612  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1,
08-26 21:10:48.612  1018  7631 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 21:10:48.612  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:10:48.612  1018  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:10:48.612  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-26 21:10:48.612  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:48.612  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:48.622  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 21:10:48.612  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:10:48.622  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.612  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.622  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-26 21:10:48.622  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:10:48.622  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 21:10:48.622  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:48.622  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:48.622  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:48.622  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:10:48.622  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 21:10:48.622  2191  2191 I Hs20UtilService: Starting #15
08-26 21:10:48.622  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 21:10:48.622  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 21:10:48.622  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:10:48.622  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 21:10:48.622  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 21:10:48.622  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:10:48.632  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:48.632  1018  1126 D WifiP2pService: P2pDisablingState
08-26 21:10:48.632  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 21:10:48.632  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-26 21:10:48.632  1018  1126 D WifiP2pService: p2p socket connection lost
08-26 21:10:48.632  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 21:10:48.632  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:48.632  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 21:10:48.632  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:48.632  1018  1126 D WifiP2pService: P2pDisabledState
08-26 21:10:48.632  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 21:10:48.632  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 21:10:48.632  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 21:10:48.632  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:10:48.632  1018  1048 D WifiDisplayController: disconnect
,08-26 21:10:48.632  1018  1048 D WifiDisplayController: updateConnection
08-26 21:10:48.632  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:10:48.632  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:10:48.632  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-26 21:10:48.632  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 21:10:48.632  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 21:10:48.632  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 21:10:48.642  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 21:10:48.642  1018  1321 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 21:10:48.642  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 21:10:48.642  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 21:10:48.642  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:48.642  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 21:10:48.642  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 21:10:48.642  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:48.642  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:10:48.642  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:48.652  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:48.652  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 21:10:48.652  7614  7614 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 21:10:48.652  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:10:48.662  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 21:10:48.662   279  1016 D CommandListener: Clearing all IP addresses on wlan0,
08-26 21:10:48.662  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-26 21:10:48.662  7493  7493 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 21:10:48.662  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 21:10:48.662  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.662  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.672  7633  7633 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:48.672  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.672  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:10:48.682  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:10:48.682  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:10:48.682  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:48.682  1018  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:10:48.682  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:10:48.682  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:48.682  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:10:48.682  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.692  1177  1177 D HotspotTile: onReceive : 0, 0
08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.682  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:48.682  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 21:10:48.682  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 21:10:48.682  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:48.682  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:48.682  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:48.692  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:48.692  2191  2191 I Hs20UtilService: Starting #16
08-26 21:10:48.692  2191  2216 I Hs20UtilService: Message received 5007
08-26 21:10:48.692  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:48.692  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:48.692  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:48.692  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:48.692  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 21:10:48.692  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 21:10:48.692  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:48.692  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:10:48.692  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:10:48.702  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 21:10:48.702  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:10:48.702  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:10:48.702  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:10:48.702  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:48.702  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:48.702  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:48.702  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:48.702  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:48.712  2191  2191 I Hs20UtilService: Starting #17,
08-26 21:10:48.712  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:10:48.712  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 21:10:48.712  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:10:48.712  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:48.712  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:10:48.762  7633  7633 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-26 21:10:48.792   292   292 E SMD     : DCD OFF,
,08-26 21:10:48.882  7493  7493 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 21:10:48.962  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 21:10:48.962  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:10:48.962  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 21:10:48.962  7493  7493 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-26 21:10:48.982  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 21:10:48.982  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.982  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:10:48.982  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.982  1018  1130 D Tethering: InitialState.processMessage what=4
08-26 21:10:48.982  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 21:10:48.982  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:48.992  1018  1130 E Tethering: No numeric data
08-26 21:10:48.992  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:10:48.992  1018  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:10:48.992  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:10:48.992  1018  1130 D Tethering: clearTetheredNotification()
08-26 21:10:48.992  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 21:10:48.992  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:48.992  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:10:48.992  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 21:10:48.992  7493  7493 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-26 21:10:48.992  7493  7493 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 21:10:48.992  7493  7493 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 21:10:48.992  7493  7493 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 21:10:48.992  7493  7493 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 21:10:48.992  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.992  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:10:48.992  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:49.002  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:49.002  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-26 21:10:49.002  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:10:49.002  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:10:49.182  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 21:10:49.182  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:49.182  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:49.242  7493  7493 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 21:10:49.342  7493  7493 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-26 21:10:49.342  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:10:49.342  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 21:10:49.342  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:10:49.412   341   341 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 21:10:49.452  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 21:10:49.452  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 21:10:49.452  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:10:49.452  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 21:10:49.452  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 21:10:49.452  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:49.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:49.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:49.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:10:49.462  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:10:49.462  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:49.462  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 21:10:49.462  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 21:10:49.462  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:10:49.462  1605  2074 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:10:49.462  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 21:10:49.462  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:10:49.462  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:49.462  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:49.462  1018  1320 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:10:49.462  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:10:49.462  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:49.472  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:49.472  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:10:49.472  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 21:10:49.472  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:10:49.472  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:10:49.472  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 21:10:49.472  2191  2191 I Hs20UtilService: Starting #18
,08-26 21:10:49.472  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:10:50.202   279  1010 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-26 21:10:50.202  1018  1045 D Tethering: interfaceRemoved wlan0
,08-26 21:10:50.202  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 21:10:50.362  1018  1045 D Tethering: interfaceRemoved p2p0
,08-26 21:10:50.362  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 21:10:51.042  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-26 21:10:51.172  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 21:10:51.182  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 21:10:51.182   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:10:51.182   279  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 21:10:51.192  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:51.202  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:51.202  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 21:10:51.562  6812  6969 D BluetoothAdapter: enable()
,08-26 21:10:51.572  1018  1321 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 21:10:51.572  1018  1321 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 21:10:51.572  1018  1321 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 21:10:51.572  1018  1321 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 21:10:51.572  1018  1321 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 21:10:51.592  1018  1321 D SettingsProvider: name = bluetooth_on,
,08-26 21:10:51.592  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 21:10:51.592  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 21:10:51.592  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 21:10:51.602  3219  3277 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 21:10:51.602  3219  3277 D BluetoothAdapterProperties: Setting state to 11
08-26 21:10:51.602  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 21:10:51.602  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:51.602  3219  3277 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 21:10:51.602  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:51.602  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 21:10:51.602  3219  3277 D BtConfig.SecureMode: isSecureModeOn:false,
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12,
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-26 21:10:51.602  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 21:10:51.602  1018  1018 I InputMethodManagerService: [BT Setting State] State =11,
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10,
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10,
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 21:10:51.602  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 21:10:51.602  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 21:10:51.622  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:51.622  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 21:10:51.622  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-26 21:10:51.622  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
08-26 21:10:51.622  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 21:10:51.632  1998  1998 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:10:51.632  1018  1139 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:51.632  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:51.632  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 21:10:51.632  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 21:10:51.632  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:51.632  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.632  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.632  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.632  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.632  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.632  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:51.632  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 21:10:51.632  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 21:10:51.642  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:51.642  3219  3219 D HeadsetService: Received start request. Starting profile...
,08-26 21:10:51.642  3219  3219 D HeadsetService: start()
08-26 21:10:51.642  3219  3219 D HeadsetStateMachine: make
,08-26 21:10:51.642  1018  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:51.642  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.642  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:51.642  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:51.642  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:51.642  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:51.652  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-26 21:10:51.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:51.652  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.652  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 21:10:51.652  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 21:10:51.652  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.652  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.652  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.652  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 21:10:51.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 21:10:51.652  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 21:10:51.652  3219  3219 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 21:10:51.662  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:51.662  1018  1265 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 21:10:51.662  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.662  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.662  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.662  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 21:10:51.662  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.662  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.662  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.662  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.662  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.662  1018  1139 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 21:10:51.662  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 21:10:51.662  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 21:10:51.662  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 21:10:51.662  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.672  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.672  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.672  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 21:10:51.672  3219  3219 I bluedroid: get_profile_interface handsfree
,08-26 21:10:51.672  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.672  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.672  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:51.672  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.672  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.672  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
08-26 21:10:51.672  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:51.672  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 21:10:51.672  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.672  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.672  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.672  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.672  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.682  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 21:10:51.682  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:51.682  3219  3277 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 21:10:51.682  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:51.682  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 21:10:51.682  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.682  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.682  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.682  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.682  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:51.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:51.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 21:10:51.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 21:10:51.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 21:10:51.692  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 21:10:51.692  3219  3277 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 21:10:51.692  3219  3219 E DualScoManager: Dual Sco Manager already instantiated
08-26 21:10:51.692  3219  3219 I DualScoManager: Set HeadsetServiceHelper
08-26 21:10:51.692  3219  3219 D BluetoothAtMessage: createCMTIContentObservers
,08-26 21:10:51.692  1018  1031 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 21:10:51.692  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:51.692  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:51.692  1018  1031 D SettingsProvider: selectionArgs: false
08-26 21:10:51.692  1018  1031 D SettingsProvider: selectionArgs: 1002
08-26 21:10:51.692  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:51.692  1018  1031 D SettingsProvider: ret = -1
,08-26 21:10:51.692  3219  7666 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 21:10:51.692  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 21:10:51.692  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:51.692  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:51.692  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:51.692  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:51.702  7667  7667 E Zygote  : MountEmulatedStorage(),
08-26 21:10:51.702  7667  7667 E Zygote  : v2
08-26 21:10:51.702  7667  7667 I libpersona: KNOX_SDCARD checking this for 10055
08-26 21:10:51.702  7667  7667 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:51.712  7667  7667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:10:51.712  7667  7667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:10:51.712  1018  1265 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7667 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 21:10:51.712  3219  3219 D HeadsetService: mStartError = false
08-26 21:10:51.712  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:51.712  7667  7667 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:10:51.712  3219  3219 D A2dpService: Received start request. Starting profile...
08-26 21:10:51.712  3219  3219 D A2dpService: start()
08-26 21:10:51.712  3219  3219 I bluedroid: get_profile_interface avrcp
08-26 21:10:51.712  3219  7666 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 21:10:51.722  3219  7666 D HeadsetStateMachine: map size, before remove : 0
08-26 21:10:51.722  3219  7666 D HeadsetStateMachine: map size, after remove: 0
,08-26 21:10:51.722  3219  3219 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 21:10:51.722  3219  3219 D Avrcp   : Initialize Media Controller
08-26 21:10:51.722  3219  3219 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 21:10:51.722  3219  3219 E Avrcp   : getActiveSessions,
08-26 21:10:51.722  3219  3219 D Avrcp   : pick active media Controller,
08-26 21:10:51.722  3219  3219 D Avrcp   : Get the active Media Controller 
,08-26 21:10:51.732  3219  3219 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 21:10:51.732  3219  7673 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 21:10:51.732  3219  3219 D A2dpStateMachine: make
,08-26 21:10:51.732  3219  3219 I bluedroid: get_profile_interface a2dp
,08-26 21:10:51.732  3219  7684 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 21:10:51.732  3219  3219 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 21:10:51.732  3219  3219 D A2dpService: mStartError = false
08-26 21:10:51.732  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:51.742  3219  7681 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:10:51.742  3219  3219 D HidService: Received start request. Starting profile...
08-26 21:10:51.742  3219  3219 D HidService: start()
08-26 21:10:51.742  3219  3219 I bluedroid: get_profile_interface hidhost
08-26 21:10:51.742  3219  3219 D HidService: setHidService(): set to: null
08-26 21:10:51.742  3219  3219 D HidService: mStartError = false
08-26 21:10:51.742  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:51.742  3219  3219 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 21:10:51.742  1457  3396 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 21:10:51.742  1457  1457 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 21:10:51.742  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 21:10:51.742  1457  3396 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 21:10:51.742  7667  7667 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:51.742  7667  7667 D ActivityThread: Added TimaKeyStore provider
08-26 21:10:51.752  3219  3219 D HealthService: Received start request. Starting profile...
08-26 21:10:51.752  3219  3219 D HealthService: start()
,08-26 21:10:51.752  3219  3219 I bluedroid: get_profile_interface health
08-26 21:10:51.752  3219  3219 D HealthService: mStartError = false
08-26 21:10:51.752  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:51.752  3219  3219 D HeadsetStateMachine: Proxy object connected
08-26 21:10:51.752  3219  3219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 21:10:51.752  3219  7666 D HeadsetStateMachine: Disconnected process message: 11
,08-26 21:10:51.752  3219  3219 D PanService: Received start request. Starting profile...
08-26 21:10:51.752  3219  3219 D PanService: start()
08-26 21:10:51.752  3219  3219 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 21:10:51.752  3219  3219 I bluedroid: get_profile_interface pan
08-26 21:10:51.752  3219  3219 D PanService: mStartError = false
08-26 21:10:51.752  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:51.752  3219  3219 D BluetoothMapService: Received start request. Starting profile...
08-26 21:10:51.752  3219  3219 D BluetoothMapService: start()
,08-26 21:10:51.752  3219  3219 D BluetoothMapService: mStartError = false
08-26 21:10:51.752  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:51.752  3219  3219 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 21:10:51.752  3219  3219 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-26 21:10:51.752  3219  7666 D HeadsetStateMachine: Disconnected process message: 18
,08-26 21:10:51.752  3219  3219 D SapService: Received start request. Starting profile...
08-26 21:10:51.752  3219  3219 D SapService: start()
08-26 21:10:51.752  3219  3219 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 21:10:51.752  3219  3219 I bluedroid: get_profile_interface sap
08-26 21:10:51.752  3219  3219 D SapService: mStartError = false
08-26 21:10:51.752  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:51.752  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 21:10:51.752  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 21:10:51.752  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 21:10:51.752  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 21:10:51.752  3219  7666 D HeadsetStateMachine: Disconnected process message: 10
08-26 21:10:51.752  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 21:10:51.752  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-26 21:10:51.752  3219  7666 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 21:10:51.752  3219  7666 D HeadsetStateMachine: Disconnected process message: 11
,08-26 21:10:51.762  3219  7673 D BluetoothMediaBrowser: no now playing list
08-26 21:10:51.762  3219  7673 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 21:10:51.782  7667  7667 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 21:10:51.792  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
08-26 21:10:51.792  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 21:10:51.792  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 21:10:51.792  3219  3277 I bluedroid: enable
08-26 21:10:51.792   292   292 E SMD     : DCD OFF
,08-26 21:10:51.802  3219  3280 E bt-btif : Calling BTA_HhEnable
,08-26 21:10:51.802  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 21:10:51.802  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 21:10:51.802  3219  3280 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-26 21:10:51.802  3219  3280 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-26 21:10:51.802  3219  3280 E BluetoothServiceJni: populateRssiValuesNative
08-26 21:10:51.802  3219  3280 I bluedroid: getModelRssiValues
08-26 21:10:51.802  3219  3280 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 21:10:51.802  3219  3280 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 21:10:51.802  3219  3280 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 21:10:51.802  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 21:10:51.812  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:51.812  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:51.812  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 21:10:51.812  3219  3280 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:10:51.812  3219  3280 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:10:51.812  3219  3280 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 21:10:51.812  3219  3280 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,08-26 21:10:51.812  3219  3280 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-26 21:10:51.812  3219  3280 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 21:10:51.812  3219  3280 E bt-btif : JVenable fails
,08-26 21:10:51.812  3219  3280 D bte_conf: Device ID record 1 : primary
,08-26 21:10:51.812  3219  3280 D bte_conf:   vendorId            = 0075
08-26 21:10:51.812  3219  3280 D bte_conf:   vendorIdSource      = 0001
08-26 21:10:51.812  3219  3280 D bte_conf:   product             = 0100
08-26 21:10:51.812  3219  3280 D bte_conf:   version             = 0200
,08-26 21:10:51.822  3219  3280 D bte_conf:   clientExecutableURL = 
08-26 21:10:51.822  3219  3280 D bte_conf:   serviceDescription  = 
08-26 21:10:51.822  3219  3280 D bte_conf:   documentationURL    = 
,08-26 21:10:51.822  3219  3280 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 21:10:51.822  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 21:10:51.822  3219  3277 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:10:51.822  3219  3277 D BluetoothAdapterProperties: State =  11
,08-26 21:10:51.822  1018  1514 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 21:10:51.822  3219  3277 D BluetoothAdapterProperties: Setting state to 12
08-26 21:10:51.822  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 21:10:51.822  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 21:10:51.822  3219  3280 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 21:10:51.822  7667  7667 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 21:10:51.822  7667  7667 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 21:10:51.822  7667  7667 D UserAnalysis: Create SecureDbHelper
08-26 21:10:51.822  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 21:10:51.822  3219  3280 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:10:51.822  3219  3280 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:10:51.822  1018  1320 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 21:10:51.822  1018  1320 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:10:51.822  1018  1320 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:10:51.832  1018  1320 D SettingsProvider: selectionArgs: false
08-26 21:10:51.832  1018  1320 D SettingsProvider: selectionArgs: 1002
08-26 21:10:51.832  1018  1320 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:10:51.832  1018  1320 D SettingsProvider: ret = -1
,08-26 21:10:51.832  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:51.832  3219  3277 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 21:10:51.832  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:51.832  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.832  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.832  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:51.832  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.832  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:51.832  7667  7667 D IntelligenceServiceApplication: onCreate()
,08-26 21:10:51.832  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 21:10:51.832  3219  3277 D BluetoothAdapterService: starting service from this receiver
,08-26 21:10:51.832  1018  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:51.832  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.842  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.842  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.842  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:51.842  4815  4830 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 21:10:51.842  4815  4830 D Bluetoothsap: Binding service...
,08-26 21:10:51.842  3219  3277 I BluetoothAdapterState: Entering On State from state = 11,
,08-26 21:10:51.842  1018  1320 I ActivityManager: Killing 7196:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 21:10:51.842  7667  7667 D IntelligenceServiceApplication: no applications having user consent for prediction
08-26 21:10:51.842  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:51.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:51.842  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 21:10:51.852  4815  4830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 21:10:51.852  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 21:10:51.852  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 21:10:51.852  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 21:10:51.852  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:51.852  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.852  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.852  4815  4830 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-26 21:10:51.852  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:10:51.852  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 21:10:51.852  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:51.852  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:10:51.852  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.852  1605  1614 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:10:51.852  1605  1614 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.852  4815  7225 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 21:10:51.852  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 21:10:51.852  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.852  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.852  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.852  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.862  3219  7178 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.862  3219  7178 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.862  4815  4824 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:10:51.862  3219  3219 I BluetoothPbapService: Handler(): got msg=1
,08-26 21:10:51.862  1018  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 21:10:51.862  4815  4824 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 21:10:51.862  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:10:51.862  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.862  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.862  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.862  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.862  4815  4830 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:51.862  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:51.862  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 21:10:51.872  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 21:10:51.872  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.872  3219  7691 V BluetoothPbapService: PBAP Service initSocket try: 0
08-26 21:10:51.872  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:51.872  4815  4815 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 21:10:51.872  4815  4815 D SapProfile: Bluetooth service connected
08-26 21:10:51.872  4815  4815 D Bluetoothsap: getConnectedDevices()
08-26 21:10:51.872  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.872  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.872  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.872  6812  6823 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.872  6812  6823 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:10:51.872  1018  1018 D BluetoothA2dp: Proxy object connected
,08-26 21:10:51.872  4815  7225 D BluetoothPan: Binding service...
,08-26 21:10:51.872  4815  4815 D BluetoothA2dp: Proxy object connected
,08-26 21:10:51.872  4815  4815 D A2dpProfile: Bluetooth service connected
,08-26 21:10:51.872  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 21:10:51.872  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.872  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.882  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.882  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.882  3219  3233 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:10:51.882  3219  3233 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.882  3219  7691 D BluetoothSocket: bindListen(): myUserId = 0
08-26 21:10:51.882  3219  7691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:10:51.882  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:10:51.882  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.882  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.882  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.882  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.882  3219  3219 D BluetoothA2dp: Proxy object connected
,08-26 21:10:51.882  1018  1047 D BluetoothPan: Binding service...
08-26 21:10:51.882  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 21:10:51.882  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 21:10:51.882  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:10:51.882  1177  1209 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.882  1177  1209 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:10:51.882  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 21:10:51.882  3219  7691 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 21:10:51.882  3219  7691 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:10:51.882  3219  7691 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 21:10:51.882  3219  7691 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c01d4d9
08-26 21:10:51.882  3219  7691 D BluetoothSocket: channel: 19
08-26 21:10:51.882  3219  7691 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 21:10:51.882  4815  4815 D BluetoothInputDevice: Proxy object connected
08-26 21:10:51.882  4815  4815 D HidProfile: Bluetooth service connected
,08-26 21:10:51.882  1483  1500 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.882  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:10:51.882  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:10:51.892  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.892  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.892  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.892  1483  1500 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:10:51.892  1457  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.892  4815  4815 D BluetoothPbap: Proxy object connected
08-26 21:10:51.892  4815  4815 D PbapServerProfile: Bluetooth service connected
08-26 21:10:51.892  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:10:51.892  4815  4815 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:10:51.892  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 21:10:51.892  4815  4815 D PanProfile: Bluetooth service connected
,08-26 21:10:51.892  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.892  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.892  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.892  1457  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:10:51.892  1464  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:10:51.892  1464  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.892  1660  4241 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.892  1660  4241 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.892  1457  3396 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.892  1457  3396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.892  1457  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.892  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:10:51.892  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 21:10:51.892  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:51.902  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.902  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.902  1457  1476 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 21:10:51.902  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.902  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:10:51.902  4815  4824 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.902  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:10:51.902  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:10:51.902  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.902  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.902  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:51.902  4815  4824 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 21:10:51.902  4815  4815 D HeadsetProfile: Bluetooth service connected
,08-26 21:10:51.902  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 21:10:51.902  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:10:51.902  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 21:10:51.902  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:10:51.962  1018  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #21
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: android.os.DeadObjectException
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:10:51.962  1018  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 21:10:51.962  1457  3396 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:10:51.962  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 21:10:51.972  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:10:51.972  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.972  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.972  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 21:10:51.972  1457  3396 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:10:51.972  4815  4830 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.972  4815  4830 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:10:51.972  4815  7225 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:10:51.972  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 21:10:51.972  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 21:10:51.972  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:51.972  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:51.972  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 21:10:51.972  1483  1498 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:10:51.972  1483  1498 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:10:51.972  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 21:10:51.972  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-26 21:10:51.972  4815  4815 D BluetoothMap: Proxy object connected
,08-26 21:10:51.972  4815  4815 D MapProfile: Bluetooth service connected
08-26 21:10:51.972  4815  4815 D BluetoothMap: getConnectedDevices()
,08-26 21:10:51.972  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:51.972  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
,08-26 21:10:51.972  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 21:10:51.982  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 21:10:51.982  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 21:10:51.992  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:10:51.992  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 21:10:51.992  1457  1457 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3a8668eb, true
,08-26 21:10:51.992  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:51.992  1457  1457 D BluetoothHeadset: registerMessageListener
,08-26 21:10:51.992  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:51.992  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:51.992  1998  1998 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:10:52.002  3219  7178 D HeadsetService: registerMessageListener
,08-26 21:10:52.002  3219  7178 D HeadsetService: registerMessageListener
08-26 21:10:52.002  3219  7666 D HeadsetStateMachine: Disconnected process message: 70
08-26 21:10:52.002  1018  1522 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 21:10:52.002  1457  1457 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 21:10:52.002  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 21:10:52.002  3219  7666 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1477ee9e
,08-26 21:10:52.002  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:52.002  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:52.012  1018  1321 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 21:10:52.012  1457  1457 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 21:10:52.012  1457  1457 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 21:10:52.012  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 21:10:52.012  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 21:10:52.012  3219  7692 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 21:10:52.012  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:52.012  3219  7666 D HeadsetStateMachine: Disconnected process message: 9
08-26 21:10:52.012  3219  7666 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 21:10:52.022  4815  4815 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 21:10:52.022  4815  4815 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 21:10:52.022  4815  4815 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 21:10:52.022  4815  4815 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 21:10:52.022   287   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 21:10:52.022   287   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-26 21:10:52.022  3219  7692 D BluetoothSocket: bindListen(): myUserId = 0
08-26 21:10:52.022  3219  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:10:52.022   287   693 V voice   : voice_set_parameters: exit with code(-2)
,08-26 21:10:52.022   287   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 21:10:52.022   287   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 21:10:52.022   287   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 21:10:52.022   287   693 V audio_hw_primary: adev_set_parameters: exit
,08-26 21:10:52.022  3219  7692 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 21:10:52.022  3219  7692 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:10:52.022  3219  7692 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 21:10:52.022  3219  7692 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2df8ed7f
08-26 21:10:52.022  3219  7666 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 21:10:52.022  3219  7692 D BluetoothSocket: channel: 5
,08-26 21:10:52.032  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:52.032  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 21:10:52.032  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:10:52.032  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:52.032  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:52.032  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:10:52.042  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:52.042  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:52.052  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:52.052  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:52.052  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 21:10:52.062  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:52.062  3219  3219 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 21:10:52.062  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:52.062  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 21:10:52.062  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:52.062  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:52.062  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:52.072  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 21:10:52.072  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:52.072  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:52.072  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:10:52.072  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:10:52.082  7695  7695 E Zygote  : MountEmulatedStorage()
,08-26 21:10:52.082  7695  7695 E Zygote  : v2
08-26 21:10:52.082  7695  7695 I libpersona: KNOX_SDCARD checking this for 10105
08-26 21:10:52.082  7695  7695 I libpersona: KNOX_SDCARD not a persona
,08-26 21:10:52.092  7695  7695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:10:52.092  7695  7695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:10:52.092  1018  1490 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7695 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-26 21:10:52.102  7695  7695 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 21:10:52.102  1018  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 21:10:52.112  3219  7705 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 21:10:52.112  3219  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:10:52.112  3219  7705 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-26 21:10:52.112  3219  7705 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:10:52.112  3219  7705 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 21:10:52.112  3219  7705 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4b8e29b
,08-26 21:10:52.112  3219  7705 D BluetoothSocket: channel: 12
08-26 21:10:52.112  3219  7705 I BtOppRfcommListener: Accept thread started.
,08-26 21:10:52.132  7695  7695 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:10:52.132  7695  7695 D ActivityThread: Added TimaKeyStore provider
,08-26 21:10:52.252   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 21:10:52.252   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:52.252  7695  7716 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 21:10:52.252   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 21:10:52.252   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:10:52.252  7695  7716 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 21:10:52.412  7695  7695 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.412  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  7695  7695 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:10:52.422  7695  7695 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:10:52.422  1018  1139 I ActivityManager: Killing 7306:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 21:10:52.492  7695  7720 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 21:10:52.512  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 21:10:52.512  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:52.512  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:52.512  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 21:10:53.112  1018  3318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 21:10:53.692  1018  3300 D SSRM:n  : SIOP:: AP = 390
,08-26 21:10:54.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 21:10:54.592  6812  6969 D BluetoothAdapter: disable(),
,08-26 21:10:54.592  1018  1030 D SettingsProvider: name = bluetooth_on
,08-26 21:10:54.612  3219  3277 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 21:10:54.612  3219  3277 D BluetoothAdapterProperties: Setting state to 13
,08-26 21:10:54.612  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:10:54.612  1018  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:54.612  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:54.612  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 21:10:54.612  3219  3277 D BluetoothAdapterService: updateAdapterState state is 13
08-26 21:10:54.612  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:54.612  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.612  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.612  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:54.612  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 21:10:54.612  3219  3277 D BluetoothAdapterService: terminating service from this receiver
,08-26 21:10:54.612  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.612  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
,08-26 21:10:54.622  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:54.622  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.622  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:54.622  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36a5e638, channel: 19, state: LISTENING
08-26 21:10:54.622  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36a5e638, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c01d4d9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18184611mSocket: android.net.LocalSocket@29d53376 impl:android.net.LocalSocketImpl@8b90d77 fd:FileDescriptor[80]
08-26 21:10:54.622  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29d53376 impl:android.net.LocalSocketImpl@8b90d77 fd:FileDescriptor[80]
,08-26 21:10:54.622  3219  3277 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 21:10:54.622  3219  3277 D BluetoothAdapterProperties: mDiscovering is false
,08-26 21:10:54.622  1018  1320 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
,08-26 21:10:54.622  3219  3277 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 21:10:54.632  4815  4815 D BluetoothPbap: Proxy object disconnected
08-26 21:10:54.632  4815  4815 D PbapServerProfile: Bluetooth service disconnected
,08-26 21:10:54.632  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 21:10:54.632  3219  3280 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:10:54.632  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 21:10:54.632  3219  3277 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 21:10:54.632  3219  3277 E bt-btif : cmd socket is not created
08-26 21:10:54.632  3219  7705 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 21:10:54.642  3219  3277 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 21:10:54.642  3219  3281 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 21:10:54.642  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:54.642  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:54.642  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:54.642  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:54.652  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:54.652  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:54.652  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:54.652  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:54.652  3219  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 21:10:54.662  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.662  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 21:10:54.672  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 21:10:54.672  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 21:10:54.672  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:54.672  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:10:54.682  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.682  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 21:10:54.682  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 21:10:54.682  1018  1522 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:54.682  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 21:10:54.682  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 21:10:54.692  1998  1998 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 21:10:54.692  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.692  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d2a324d, channel: 5, state: LISTENING
08-26 21:10:54.692  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d2a324d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2df8ed7f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ad91102mSocket: android.net.LocalSocket@2b270a13 impl:android.net.LocalSocketImpl@22634450 fd:FileDescriptor[82]
08-26 21:10:54.692  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b270a13 impl:android.net.LocalSocketImpl@22634450 fd:FileDescriptor[82]
,08-26 21:10:54.692  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:54.692  3219  3219 I BtOppRfcommListener: stopping Accept Thread
,08-26 21:10:54.692  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:54.692  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8f4a649, channel: 12, state: LISTENING
,08-26 21:10:54.692  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8f4a649, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4b8e29b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4b3b4emSocket: android.net.LocalSocket@386e346f impl:android.net.LocalSocketImpl@17c0557c fd:FileDescriptor[85]
08-26 21:10:54.692  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@386e346f impl:android.net.LocalSocketImpl@17c0557c fd:FileDescriptor[85]
08-26 21:10:54.692  3219  7705 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 21:10:54.692  3219  3219 V BluetoothOppManager: cleanUp...
,08-26 21:10:54.702  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:54.702  1018  1522 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 21:10:54.702  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.702  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:54.702  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.702  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:10:54.712  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:54.712  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:54.712  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:54.712  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.712  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 21:10:54.802   292   292 E SMD     : DCD OFF
,08-26 21:10:54.842  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 21:10:54.842  3219  3277 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 21:10:54.842  3219  3277 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 21:10:54.842  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 21:10:54.842  3219  3277 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,08-26 21:10:54.842  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 21:10:54.842  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 21:10:54.842  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 21:10:54.842  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:54.842  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.842  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:54.842  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.842  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.852  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
08-26 21:10:54.852  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:54.852  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 21:10:54.852  1018  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:54.852  3219  3219 D HeadsetService: Received stop request...Stopping profile...
08-26 21:10:54.852  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.852  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:54.852  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:54.852  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.852  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 21:10:54.852  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:54.852  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 21:10:54.862  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:10:54.862  1018  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:54.862  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.862  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:54.862  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.862  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.862  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 21:10:54.862  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 21:10:54.862  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 21:10:54.862  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:10:54.862  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 21:10:54.862  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:10:54.862  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.862  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.862  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 21:10:54.862  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 21:10:54.862  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 21:10:54.862  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 21:10:54.862  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 21:10:54.862  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-26 21:10:54.862  4815  4815 D HeadsetProfile: Bluetooth service disconnected
08-26 21:10:54.872  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:54.872  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.872  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 21:10:54.872  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.872  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.872  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:54.872  1018  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:54.872  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.872  1018  1139 W ActivityManager: userId = 0, bbcId = -10000,
08-26 21:10:54.872  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.872  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.872  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-26 21:10:54.872  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:54.872  3219  3277 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 21:10:54.872  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:10:54.872  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.872  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:54.872  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:10:54.872  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 21:10:54.882  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:54.882  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 21:10:54.882  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 21:10:54.882  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 21:10:54.882  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 21:10:54.882  3219  3277 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 21:10:54.882  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 21:10:54.882  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:10:54.882  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 21:10:54.882  3219  3219 D A2dpService: Received stop request...Stopping profile...
08-26 21:10:54.882  3219  7681 D A2dpStateMachine: Exit Disconnected: -1
,08-26 21:10:54.882  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.882  4815  4815 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:54.882  4815  4815 D A2dpProfile: Bluetooth service disconnected
08-26 21:10:54.882  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:54.882  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 21:10:54.882  3219  3219 D HidService: Received stop request...Stopping profile...
08-26 21:10:54.882  3219  3219 D HidService: Stopping Bluetooth HidService
08-26 21:10:54.882  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:10:54.882  3219  3219 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 21:10:54.882  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:10:54.882  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.882  4815  4815 D BluetoothInputDevice: Proxy object disconnected
08-26 21:10:54.882  4815  4815 D HidProfile: Bluetooth service disconnected
08-26 21:10:54.892  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:10:54.892  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:10:54.892  3219  3219 D HealthService: Received stop request...Stopping profile...
,08-26 21:10:54.892  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.892  3219  3219 D PanService: Received stop request...Stopping profile...
08-26 21:10:54.892  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.892  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:10:54.892  3219  3219 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:10:54.892  4815  4815 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 21:10:54.892  4815  4815 D PanProfile: Bluetooth service disconnected
,08-26 21:10:54.892  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.892  3219  3219 D SapService: Received stop request...Stopping profile...
08-26 21:10:54.892  3219  3219 D SapService: Stopping Bluetooth SapService
08-26 21:10:54.892  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:10:54.902  4815  4815 D BluetoothMap: Proxy object disconnected
,08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 21:10:54.902  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 21:10:54.902  3219  3219 D BluetoothA2dp: Proxy object disconnected
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 21:10:54.902  3219  7684 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 21:10:54.902  3219  3219 I GKI_LINUX: GKI_exit_task 2 done
08-26 21:10:54.902  3219  3219 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true,
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:54.902  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:54.902  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 21:10:54.902  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:10:54.902  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-26 21:10:54.902  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 21:10:54.902  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:10:54.902  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:54.902  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-26 21:10:54.902  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 21:10:54.902  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 21:10:54.902  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 21:10:54.902  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 21:10:54.902  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-26 21:10:54.902  3219  3277 D BluetoothAdapterProperties: Setting state to 10
08-26 21:10:54.902  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 21:10:54.902  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:10:54.902  3219  3277 D BluetoothAdapterService: updateAdapterState state is 10
08-26 21:10:54.902  3219  3277 D BluetoothAdapterService: Autoconnection is available 
08-26 21:10:54.902  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10,
08-26 21:10:54.902  3219  3277 I BluetoothAdapterState: Entering OffState
08-26 21:10:54.902  4815  4815 D MapProfile: Bluetooth service disconnected
08-26 21:10:54.902  4815  4824 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 21:10:54.902  4815  4824 D Bluetoothsap: Unbinding service...
08-26 21:10:54.902  4815  4815 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-26 21:10:54.902  4815  4815 D SapProfile: Bluetooth service disconnected
08-26 21:10:54.912  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:54.912  1605  1622 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:54.912  1605  1622 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.912  4815  7225 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 21:10:54.912  3219  3326 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:54.912  3219  3326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.912  4815  4830 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:54.912  4815  4824 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 21:10:54.912  6812  6820 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.912  6812  6820 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.912  6812  6820 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 21:10:54.912  6812  6820 D BluetoothLeAdvertiser: Exit stop advertising
,08-26 21:10:54.912  6812  6820 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 21:10:54.912  6812  6820 D BluetoothLeScanner: Exiting stopAllScan
,08-26 21:10:54.912  7695  7709 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.912  7695  7709 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.912  3219  7178 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:54.922  1177  1209 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 21:10:54.922  1177  1209 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  1464  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.922  1464  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  1660  1669 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.922  1660  1669 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  1457  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.922  1457  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.922  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  4815  4824 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.922  4815  4824 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.922  4815  7225 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 21:10:54.932  1483  1500 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 21:10:54.932  1483  1500 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 21:10:54.932  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.932  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,08-26 21:10:54.932  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 21:10:54.932  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 21:10:54.942  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.942  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 21:10:54.942  1998  1998 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:10:54.942  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.942  1018  1494 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:10:54.942  1018  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 21:10:54.942  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 21:10:54.952  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:54.952  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:54.952  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:54.952  1018  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 21:10:54.952  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:10:54.952  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:54.952  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:10:54.952  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:10:54.962  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:54.962  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:54.962  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:10:54.962  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:54.962  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 21:10:55.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 21:10:55.912  1018  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 21:10:55.912  1018  1514 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4306, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 21:10:55.912  1018  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 21:10:55.912  1018  1514 D BatteryService: stay LED for charging
,08-26 21:10:55.912  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 21:10:55.922  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 21:10:55.922  1018  1018 I MotionRecognitionService: Plugged,
08-26 21:10:55.922  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 21:10:55.922  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 21:10:55.922  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 21:10:55.922  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 21:10:55.942  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 21:10:55.942  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 21:10:55.942  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:55.942  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 21:10:55.942  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:10:56.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 21:10:57.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 21:10:57.612  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:10:57.612  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:57.802   292   292 E SMD     : DCD OFF
,08-26 21:10:58.412   341   341 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 21:10:59.022  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 21:10:59.032   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:10:59.032   279  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 21:10:59.062  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:10:59.062  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:10:59.062  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 21:10:59.412   341   341 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 21:10:59.992  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 21:11:00.612  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:00.612  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e98eb19 added. We now have 6 listener(s)
,08-26 21:11:00.612  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:00.612  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:00.622  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d13e7de added. We now have 7 listener(s)
,08-26 21:11:00.622  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:00.622  6812  6969 I System.out: IsBluetoothEnabled
,08-26 21:11:00.622  6812  6969 D BluetoothAdapter: disable()
,08-26 21:11:00.622  1018  1490 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 21:11:00.632  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:00.632  6812  6969 D BluetoothAdapter: enable()
,08-26 21:11:00.632  1018  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 21:11:00.632  1018  1494 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 21:11:00.632  1018  1494 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 21:11:00.632  1018  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 21:11:00.632  1018  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 21:11:00.632  1018  1494 D SettingsProvider: name = bluetooth_on
,08-26 21:11:00.642  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 21:11:00.642  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 21:11:00.652  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 21:11:00.652  3219  3277 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 21:11:00.652  3219  3277 D BluetoothAdapterProperties: Setting state to 11
08-26 21:11:00.652  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 21:11:00.652  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:11:00.652  3219  3277 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 21:11:00.652  3219  3277 D BluetoothAdapterService: Autoconnection is available 
,08-26 21:11:00.652  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 21:11:00.652  3219  3277 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 21:11:00.652  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 21:11:00.652  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 21:11:00.652  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 21:11:00.652  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 21:11:00.662  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 21:11:00.662  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:00.662  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-26 21:11:00.662  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:11:00.662  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 21:11:00.662  1018  1321 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:11:00.662  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 21:11:00.672  1998  1998 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:11:00.672  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 21:11:00.672  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:11:00.672  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:11:00.672  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.682  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.682  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.682  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.682  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:00.682  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 21:11:00.682  3219  3219 D HeadsetService: Received start request. Starting profile...
08-26 21:11:00.682  3219  3219 D HeadsetService: start()
08-26 21:11:00.682  3219  3219 D HeadsetStateMachine: make
,08-26 21:11:00.682  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 21:11:00.682  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 21:11:00.682  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:00.682  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.682  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.682  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:00.682  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.682  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 21:11:00.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 21:11:00.692  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 21:11:00.692  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.692  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.692  3219  3219 E HeadsetStateMachine: # of Max HF connection is 2
08-26 21:11:00.692  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.692  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.692  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.692  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 21:11:00.692  1018  1265 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.692  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 21:11:00.692  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.692  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 21:11:00.692  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.692  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.692  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.702  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-26 21:11:00.702  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 21:11:00.702  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 21:11:00.702  1018  1321 W ActivityManager: userId = 0, bbcId = -10000,
08-26 21:11:00.702  1018  1321 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 21:11:00.702  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.702  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-26 21:11:00.702  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
08-26 21:11:00.702  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.702  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 21:11:00.702  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.702  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.702  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-26 21:11:00.702  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 21:11:00.702  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 21:11:00.702  3219  3277 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 21:11:00.712  1018  1320 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 21:11:00.712  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:11:00.712  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-26 21:11:00.712  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.712  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.712  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 21:11:00.712  3219  3219 I bluedroid: get_profile_interface handsfree
,08-26 21:11:00.712  1018  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:11:00.712  1018  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.712  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:00.712  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.712  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.722  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 21:11:00.722  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 21:11:00.722  3219  3277 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 21:11:00.722  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:11:00.722  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 21:11:00.722  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 21:11:00.722  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.732  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:00.732  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.732  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.732  3219  3219 E DualScoManager: Dual Sco Manager already instantiated
,08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:11:00.732  3219  3219 I DualScoManager: Set HeadsetServiceHelper
08-26 21:11:00.732  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:11:00.732  3219  3219 D BluetoothAtMessage: createCMTIContentObservers
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService,
08-26 21:11:00.732  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 21:11:00.732  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 21:11:00.732  3219  3277 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 21:11:00.732  3219  3277 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 21:11:00.732  3219  3277 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 21:11:00.732  1018  1139 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 21:11:00.732  1018  1139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:11:00.732  1018  1139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:11:00.732  1018  1139 D SettingsProvider: selectionArgs: false
08-26 21:11:00.732  1018  1139 D SettingsProvider: selectionArgs: 1002
08-26 21:11:00.732  1018  1139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 21:11:00.732  1018  1139 D SettingsProvider: ret = -1
,08-26 21:11:00.732  3219  7742 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 21:11:00.742  3219  3219 D HeadsetService: mStartError = false
,08-26 21:11:00.742  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:11:00.742  3219  7742 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 21:11:00.742  3219  7742 D HeadsetStateMachine: map size, before remove : 0
,08-26 21:11:00.742  3219  7742 D HeadsetStateMachine: map size, after remove: 0
,08-26 21:11:00.742  3219  3219 D A2dpService: Received start request. Starting profile...
08-26 21:11:00.742  3219  3219 D A2dpService: start(),
08-26 21:11:00.742  3219  3219 I bluedroid: get_profile_interface avrcp
,08-26 21:11:00.742  3219  3219 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:11:00.742  3219  3219 D Avrcp   : Initialize Media Controller
08-26 21:11:00.742  3219  3219 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 21:11:00.742  3219  3219 E Avrcp   : getActiveSessions
,08-26 21:11:00.742  3219  3219 D Avrcp   : pick active media Controller
08-26 21:11:00.752  3219  3219 D Avrcp   : Get the active Media Controller 
,08-26 21:11:00.752  3219  3219 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 21:11:00.752  3219  3219 D A2dpStateMachine: make
,08-26 21:11:00.752  3219  7743 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 21:11:00.762  3219  3219 I bluedroid: get_profile_interface a2dp
,08-26 21:11:00.762  3219  7745 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 21:11:00.762  3219  3219 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 21:11:00.762  3219  3219 D A2dpService: mStartError = false
08-26 21:11:00.762  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:11:00.762  3219  7744 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:11:00.762  3219  3219 D HidService: Received start request. Starting profile...
,08-26 21:11:00.762  3219  3219 D HidService: start()
08-26 21:11:00.762  3219  3219 I bluedroid: get_profile_interface hidhost
08-26 21:11:00.762  3219  3219 D HidService: setHidService(): set to: null
08-26 21:11:00.762  3219  3219 D HidService: mStartError = false
08-26 21:11:00.762  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:11:00.762  3219  3219 D HealthService: Received start request. Starting profile...
08-26 21:11:00.762  3219  3219 D HealthService: start()
,08-26 21:11:00.762  3219  3219 I bluedroid: get_profile_interface health
08-26 21:11:00.762  3219  3219 D HealthService: mStartError = false
08-26 21:11:00.762  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:11:00.762  3219  3219 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 21:11:00.772  1457  3396 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 21:11:00.772  1457  1457 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 21:11:00.772  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 21:11:00.772  1457  3396 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 21:11:00.772  3219  3219 D PanService: Received start request. Starting profile...
,08-26 21:11:00.772  3219  3219 D PanService: start()
08-26 21:11:00.772  3219  3219 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 21:11:00.772  3219  3219 I bluedroid: get_profile_interface pan
08-26 21:11:00.772  3219  3219 D PanService: mStartError = false
,08-26 21:11:00.772  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:11:00.772  3219  3219 D HeadsetStateMachine: Proxy object connected
,08-26 21:11:00.772  3219  3219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 21:11:00.772  3219  7742 D HeadsetStateMachine: Disconnected process message: 11
,08-26 21:11:00.772  3219  3219 D BluetoothMapService: Received start request. Starting profile...
08-26 21:11:00.772  3219  3219 D BluetoothMapService: start()
,08-26 21:11:00.782  3219  7743 D BluetoothMediaBrowser: no now playing list
08-26 21:11:00.782  3219  3219 D BluetoothMapService: mStartError = false
08-26 21:11:00.782  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:11:00.782  3219  3219 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 21:11:00.782  3219  3219 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-26 21:11:00.782  3219  3219 D SapService: Received start request. Starting profile...
08-26 21:11:00.782  3219  3219 D SapService: start()
08-26 21:11:00.782  3219  3219 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 21:11:00.782  3219  3219 I bluedroid: get_profile_interface sap
08-26 21:11:00.782  3219  3219 D SapService: mStartError = false
08-26 21:11:00.782  3219  7743 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 21:11:00.782  3219  7742 D HeadsetStateMachine: Disconnected process message: 18
08-26 21:11:00.782  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
08-26 21:11:00.782  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 21:11:00.782  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 21:11:00.782  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 21:11:00.782  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 21:11:00.782  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 21:11:00.782  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-26 21:11:00.782  3219  7742 D HeadsetStateMachine: Disconnected process message: 10
,08-26 21:11:00.782  3219  7742 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 21:11:00.782  3219  7742 D HeadsetStateMachine: Disconnected process message: 11
,08-26 21:11:00.792  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 21:11:00.792  3219  3219 E BluetoothAdapterService(81464420): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 21:11:00.802  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 21:11:00.802  3219  3277 I bluedroid: enable
,08-26 21:11:00.802   292   292 E SMD     : DCD OFF
,08-26 21:11:00.802  3219  3280 E bt-btif : Calling BTA_HhEnable
,08-26 21:11:00.802  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 21:11:00.812  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 21:11:00.812  3219  3280 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 21:11:00.812  3219  3280 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-26 21:11:00.812  3219  3280 E BluetoothServiceJni: populateRssiValuesNative
08-26 21:11:00.812  3219  3280 I bluedroid: getModelRssiValues
08-26 21:11:00.812  3219  3280 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 21:11:00.812  3219  3280 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 21:11:00.812  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 21:11:00.812  3219  3280 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 21:11:00.812  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:00.812  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 21:11:00.812  3219  3280 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:11:00.812  3219  3280 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:11:00.822  3219  3280 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 21:11:00.822  3219  3280 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-26 21:11:00.822  3219  3280 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-26 21:11:00.822  3219  3280 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 21:11:00.822  3219  3280 E bt-btif : JVenable fails
,08-26 21:11:00.822  3219  3280 D bte_conf: Device ID record 1 : primary
08-26 21:11:00.822  3219  3280 D bte_conf:   vendorId            = 0075
08-26 21:11:00.822  3219  3280 D bte_conf:   vendorIdSource      = 0001
08-26 21:11:00.822  3219  3280 D bte_conf:   product             = 0100
08-26 21:11:00.822  3219  3280 D bte_conf:   version             = 0200
08-26 21:11:00.822  3219  3280 D bte_conf:   clientExecutableURL = 
08-26 21:11:00.822  3219  3280 D bte_conf:   serviceDescription  = 
08-26 21:11:00.822  3219  3280 D bte_conf:   documentationURL    = 
08-26 21:11:00.822  3219  3280 D bte_conf: bte_load_did_conf no section named DID2.
08-26 21:11:00.822  3219  3280 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 21:11:00.822  3219  3280 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 21:11:00.822  3219  3277 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 21:11:00.822  3219  3277 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:11:00.822  3219  3277 D BluetoothAdapterProperties: State =  11
,08-26 21:11:00.822  1018  1265 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 21:11:00.822  3219  3277 D BluetoothAdapterProperties: Setting state to 12
08-26 21:11:00.822  3219  3277 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 21:11:00.822  3219  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 21:11:00.822  3219  3280 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:11:00.822  3219  3280 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:11:00.822  1018  1494 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 21:11:00.822  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 21:11:00.822  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 21:11:00.822  1018  1494 D SettingsProvider: selectionArgs: false
,08-26 21:11:00.822  1018  1494 D SettingsProvider: selectionArgs: 1002
08-26 21:11:00.822  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 21:11:00.822  1018  1494 D SettingsProvider: ret = -1
,08-26 21:11:00.832  3219  3277 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 21:11:00.832  3219  3277 D BluetoothAdapterService: updateAdapterState state is 12
08-26 21:11:00.832  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.832  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.832  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.832  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.832  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.832  3219  3277 D BluetoothAdapterService: Autoconnection is available 
,08-26 21:11:00.832  3219  3277 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 21:11:00.832  3219  3277 D BluetoothAdapterService: starting service from this receiver
,08-26 21:11:00.832  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:00.832  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.832  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.832  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.832  4815  4824 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 21:11:00.832  4815  4824 D Bluetoothsap: Binding service...
,08-26 21:11:00.832  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.842  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 21:11:00.842  3219  3219 I BluetoothPbapService: Handler(): got msg=1
,08-26 21:11:00.842  3219  3277 I BluetoothAdapterState: Entering On State from state = 11
08-26 21:11:00.842  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:00.842  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:00.842  4815  4824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 21:11:00.842  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:00.842  3219  7750 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 21:11:00.852  3219  7750 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 21:11:00.852  3219  7750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:00.852  3219  7750 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 21:11:00.852  3219  7750 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:11:00.852  3219  7750 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 21:11:00.852  3219  7750 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29782861
,08-26 21:11:00.852  3219  7750 D BluetoothSocket: channel: 19
08-26 21:11:00.852  3219  7750 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 21:11:00.992  1018  1047 I art     : Explicit concurrent mark sweep GC freed 56725(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.347ms total 145.067ms
,08-26 21:11:00.992  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 21:11:00.992  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 21:11:00.992  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.992  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.992  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:00.992  4815  4824 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-26 21:11:00.992  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:11:00.992  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 21:11:00.992  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:11:00.992  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.992  1605  1839 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:00.992  1605  1839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:11:00.992  4815  7225 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 21:11:00.992  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 21:11:00.992  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 21:11:00.992  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:00.992  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:00.992  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.002  3219  3234 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:01.002  3219  3234 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.002  4815  4824 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:11:01.002  1018  1018 D BluetoothA2dp: Proxy object connected
08-26 21:11:01.002  4815  4824 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 21:11:01.002  4815  4815 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-26 21:11:01.002  4815  4815 D SapProfile: Bluetooth service connected
08-26 21:11:01.002  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:11:01.002  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 21:11:01.002  4815  4815 D Bluetoothsap: getConnectedDevices()
08-26 21:11:01.002  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.002  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.002  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.002  4815  7225 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 21:11:01.002  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 21:11:01.002  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.002  4815  4815 D BluetoothA2dp: Proxy object connected
08-26 21:11:01.002  4815  4815 D A2dpProfile: Bluetooth service connected
08-26 21:11:01.002  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.002  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.002  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 21:11:01.002  6812  6823 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:11:01.002  6812  6823 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:11:01.002  7695  7709 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:01.002  7695  7709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.012  4815  4830 D BluetoothPan: Binding service...
,08-26 21:11:01.012  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 21:11:01.012  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.012  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.012  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.012  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.012  3219  3234 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:11:01.012  3219  3234 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.012  4815  4815 D BluetoothInputDevice: Proxy object connected
08-26 21:11:01.012  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 21:11:01.012  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.012  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.012  4815  4815 D HidProfile: Bluetooth service connected
08-26 21:11:01.012  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.012  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.012  1018  1047 D BluetoothPan: Binding service...
08-26 21:11:01.012  3219  3219 D BluetoothA2dp: Proxy object connected
08-26 21:11:01.012  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 21:11:01.012  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.012  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:11:01.012  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 21:11:01.012  1177  1209 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:01.012  1177  1209 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.022  1483  1500 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.022  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:11:01.022  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:11:01.022  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.022  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.022  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.022  1483  1500 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:11:01.022  4815  4815 D BluetoothPbap: Proxy object connected
08-26 21:11:01.022  4815  4815 D PbapServerProfile: Bluetooth service connected
,08-26 21:11:01.022  4815  4815 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 21:11:01.022  1457  3396 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 21:11:01.022  4815  4815 D PanProfile: Bluetooth service connected
,08-26 21:11:01.022  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:11:01.022  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:11:01.022  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:01.022  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.022  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.022  1457  3396 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:11:01.022  1464  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:11:01.032  1464  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.032  1660  4241 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:11:01.032  1660  4241 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:11:01.032  1457  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:11:01.032  1457  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.032  1457  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.032  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 21:11:01.032  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:11:01.032  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:01.032  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.032  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.032  1457  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:11:01.032  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:01.032  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 21:11:01.032  4815  4824 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.032  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 21:11:01.042  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:11:01.042  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.042  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:11:01.042  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 21:11:01.042  4815  4824 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 21:11:01.042  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.042  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:11:01.042  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 21:11:01.042  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:11:01.042  4815  4815 D HeadsetProfile: Bluetooth service connected
08-26 21:11:01.042  1457  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 21:11:01.042  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 21:11:01.042  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 21:11:01.042  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.042  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.042  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.042  1457  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 21:11:01.042  4815  7225 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 21:11:01.042  4815  7225 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:11:01.042  4815  4824 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 21:11:01.042  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 21:11:01.042  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.042  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:01.052  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.052  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.052  4815  4815 D BluetoothMap: Proxy object connected
,08-26 21:11:01.052  4815  4815 D MapProfile: Bluetooth service connected
08-26 21:11:01.052  1483  1657 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 21:11:01.052  1483  1657 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 21:11:01.052  4815  4815 D BluetoothMap: getConnectedDevices()
08-26 21:11:01.052  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 21:11:01.052  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 21:11:01.052  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:11:01.052  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
,08-26 21:11:01.052  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 21:11:01.052  1457  1457 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2ff47648, true
,08-26 21:11:01.062  1457  1457 D BluetoothHeadset: registerMessageListener
,08-26 21:11:01.062  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 21:11:01.062  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 21:11:01.062  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:11:01.062  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:11:01.072  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-26 21:11:01.072  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 21:11:01.072  1998  1998 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 21:11:01.072  1018  1320 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:11:01.072  4815  4815 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:01.072  1018  1265 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 21:11:01.082  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 21:11:01.082  3219  7177 D HeadsetService: registerMessageListener
08-26 21:11:01.082  4815  4815 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 21:11:01.082  1177  1704 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 21:11:01.082  4815  4815 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 21:11:01.082  4815  4815 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 21:11:01.082  4815  4815 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 21:11:01.082  3219  7177 D HeadsetService: registerMessageListener
,08-26 21:11:01.082  3219  7742 D HeadsetStateMachine: Disconnected process message: 70
08-26 21:11:01.082  3219  7742 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@13ade99d
08-26 21:11:01.082  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:01.082  1457  1457 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 21:11:01.082  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 21:11:01.082  3219  7751 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 21:11:01.082  1457  1457 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 21:11:01.082  1457  1457 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 21:11:01.082  1457  1457 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 21:11:01.092  3219  7742 D HeadsetStateMachine: Disconnected process message: 9
,08-26 21:11:01.092  3219  7742 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 21:11:01.092  3219  7751 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 21:11:01.092  3219  7751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:01.092   287   287 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 21:11:01.092   287   287 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 21:11:01.092   287   287 V voice   : voice_set_parameters: exit with code(-2)
08-26 21:11:01.092   287   287 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-26 21:11:01.092   287   287 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 21:11:01.092   287   287 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 21:11:01.092   287   287 V audio_hw_primary: adev_set_parameters: exit
,08-26 21:11:01.092  3219  7742 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 21:11:01.092  3219  7751 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-26 21:11:01.092  3219  7751 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:11:01.092  3219  7751 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 21:11:01.092  3219  7751 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa87e12
08-26 21:11:01.092  3219  7751 D BluetoothSocket: channel: 5
,08-26 21:11:01.102  4815  4815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:11:01.102  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 21:11:01.102  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.102  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:01.102  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.102  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 21:11:01.112  1660  1660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:01.112  4815  4815 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:11:01.112  4815  4815 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 21:11:01.122  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:11:01.122  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 21:11:01.122  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4db0c64
,08-26 21:11:01.122  3219  3219 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 21:11:01.132  1018  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 21:11:01.132  1018  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 21:11:01.132  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:01.132  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:01.132  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 21:11:01.142  1018  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 21:11:01.152  3219  7756 D BluetoothSocket: bindListen(): myUserId = 0
08-26 21:11:01.152  3219  7756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:01.152  3219  7756 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-26 21:11:01.152  3219  7756 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 21:11:01.152  3219  7756 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 21:11:01.152  3219  7756 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@328c695e
,08-26 21:11:01.152  3219  7756 D BluetoothSocket: channel: 12
08-26 21:11:01.152  3219  7756 I BtOppRfcommListener: Accept thread started.
,08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:01.662  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:01.662  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:01.662  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:01.662  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25d38dbf added. We now have 8 listener(s)
08-26 21:11:01.662  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:01.672  1018  1504 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-26 21:11:01.672  1018  1504 D WifiService: setWifiEnabled: false pid=6812, uid=10170
08-26 21:11:01.672  1018  1504 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 21:11:01.672  1018  1504 D SecContentProvider2: mCursor = null
08-26 21:11:01.672  1018  1504 D SettingsProvider: name = wifi_on
,08-26 21:11:01.682  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:01.682  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-26 21:11:01.682  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 21:11:01.682  1018  1031 D SecContentProvider2: mCursor = null
,08-26 21:11:01.682  1018  1031 D WifiService: setWifiEnabled: true pid=6812, uid=10170
,08-26 21:11:01.682  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 21:11:01.682  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-26 21:11:01.682  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 21:11:01.682  1018  1031 W WifiService: ,	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 21:11:01.682  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 21:11:01.682  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
,08-26 21:11:01.682  1018  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 21:11:01.682  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 21:11:01.682  1018  1031 D SettingsProvider: name = wifi_on
,08-26 21:11:01.692  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 21:11:02.052  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 21:11:02.052  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 21:11:02.052  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
08-26 21:11:02.052  1018  1045 D Tethering: interfaceAdded wlan0,
,08-26 21:11:02.062   279  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-26 21:11:02.062   279  1016 D SoftapController: Softap fwReload - Ok,
08-26 21:11:02.062  1018  1130 E Tethering: No numeric data,
08-26 21:11:02.062  1018  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 21:11:02.062  1018  1130 D Tethering: clearTetheredNotification(),
08-26 21:11:02.062  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:11:02.062  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:11:02.062  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:11:02.072  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:11:02.072   279  1016 D CommandListener: Setting iface cfg
,08-26 21:11:02.072   279  1016 D CommandListener: Trying to bring down wlan0
08-26 21:11:02.072  1018  1045 D Tethering: interfaceAdded p2p0
08-26 21:11:02.072   279  1016 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:11:02.072  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 21:11:02.082  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:02.082  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:11:02.082  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:02.082  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 21:11:02.082  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:02.082  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:02.082  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-26 21:11:02.082  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 21:11:02.082  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:02.082  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:02.092  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 21:11:02.092  1018  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-26 21:11:02.092  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:11:02.102  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:11:02.102  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:11:02.102  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:02.102  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:02.102  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:02.102  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:02.112  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:02.112  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:02.112  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:11:02.112  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:11:02.112  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 21:11:02.112  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 21:11:02.112  2191  2191 I Hs20UtilService: Starting #19
,08-26 21:11:02.112  1177  1177 D HotspotTile: onReceive : 2, 0
08-26 21:11:02.112  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:11:02.112  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 21:11:02.112  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:11:02.112  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 21:11:02.112  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:11:02.142  7769  7769 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
,08-26 21:11:02.142  7769  7769 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 21:11:02.142  7769  7769 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 21:11:02.152  7769  7769 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 21:11:02.162   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7769
08-26 21:11:02.162   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 21:11:02.162  7769  7769 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-26 21:11:02.162  7769  7769 I wpa_supplicant: ssSupport state is = 1
08-26 21:11:02.162  7769  7769 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 21:11:02.162  7769  7769 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 21:11:02.162   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7769
08-26 21:11:02.162   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 21:11:02.312   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-26 21:11:02.312  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-26 21:11:02.352  7769  7769 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 21:11:02.362  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 21:11:02.362  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 21:11:02.362   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7769
08-26 21:11:02.372   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 21:11:02.372  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 21:11:02.372  7769  7769 I wpa_supplicant: ssSupport state is = 1
08-26 21:11:02.372  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 21:11:02.372  7769  7769 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:11:02.372  7769  7769 E wpa_supplicant: SIM READ ERROR
08-26 21:11:02.372  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:11:02.372  7769  7769 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 21:11:02.372  7769  7769 E wpa_supplicant: SIM READ ERROR
08-26 21:11:02.372  7769  7769 I wpa_supplicant: Blacklist: Clear (all) 
08-26 21:11:02.372  7769  7769 I wpa_supplicant: wpa_default_ap_write_once
08-26 21:11:02.372  7769  7769 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 21:11:02.372  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-26 21:11:02.372  7769  7769 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 21:11:02.372  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 21:11:02.372  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:11:02.372  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:11:02.372  7769  7769 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:11:02.382  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:11:02.372  7769  7769 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 21:11:02.382  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 21:11:02.372  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 21:11:02.382  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-26 21:11:02.372  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:11:02.372  1018  1130 D Tethering: InitialState.processMessage what=4
,08-26 21:11:02.372  1018  1130 E Tethering: No numeric data
08-26 21:11:02.372  1018  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 21:11:02.372  1018  1130 D Tethering: clearTetheredNotification()
08-26 21:11:02.372  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:02.382  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:02.382  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:02.382  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:02.382  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:02.382  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:02.422  7769  7769 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 21:11:02.572  7769  7769 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 21:11:02.572  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 21:11:02.582  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 21:11:02.582   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7769
08-26 21:11:02.582   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 21:11:02.582  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 21:11:02.582  7769  7769 I wpa_supplicant: ssSupport state is = 1
,08-26 21:11:02.582  7769  7769 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 21:11:02.582  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 21:11:02.602  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 21:11:02.602   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7769
08-26 21:11:02.602   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 21:11:02.602  7769  7769 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 21:11:02.602  7769  7769 I wpa_supplicant: ssSupport state is = 1,
08-26 21:11:02.602  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:11:02.602  7769  7769 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 21:11:02.602  7769  7769 E wpa_supplicant: SIM READ ERROR
08-26 21:11:02.602  7769  7769 I wpa_supplicant: wpa_default_ap_write_once
08-26 21:11:02.602  7769  7769 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-26 21:11:02.602  7769  7769 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 21:11:02.602  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:11:02.602  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 21:11:02.602  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:11:02.602  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:11:02.602  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:11:02.602  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:11:02.682  7769  7769 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 21:11:02.682  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 21:11:02.722  7769  7769 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 21:11:02.722  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 21:11:02.722  7769  7769 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 21:11:03.042  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 21:11:03.042  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 21:11:03.042  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 21:11:03.092  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 21:11:03.102  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 21:11:03.102  7769  7769 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 21:11:03.102  7769  7769 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 21:11:03.102  7769  7769 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 21:11:03.102  7769  7769 E wpa_supplicant: SIM READ ERROR
08-26 21:11:03.102  7769  7769 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 21:11:03.122  7769  7769 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 21:11:03.132  7769  7769 I wpa_supplicant: Skip scan - bUseNetwork false,
08-26 21:11:03.132  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:11:03.142  4815  4815 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:03.142  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:03.142  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:03.142  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 21:11:03.142  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 21:11:03.142  1177  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 21:11:03.152  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:11:03.152  1177  1177 D HotspotTile: onReceive : 3, 0
,08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:03.152  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:03.152  1018  1127 E WifiConfigStore: Not a HS20
,08-26 21:11:03.152  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:03.162  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 21:11:03.162  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 21:11:03.162  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:03.162  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:11:03.162  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:03.162  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:11:03.162  2191  2191 I Hs20UtilService: Starting #20
08-26 21:11:03.162  2191  2216 I Hs20UtilService: Message received 5011
,08-26 21:11:03.172  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 21:11:03.172  7769  7769 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 21:11:03.172  7769  7769 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 21:11:03.172  7769  7769 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 21:11:03.172  7769  7769 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 21:11:03.172  7769  7769 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-26 21:11:03.172  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 21:11:03.172  7769  7769 I wpa_supplicant: First Scan Start
08-26 21:11:03.172  7769  7769 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 21:11:03.172  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 21:11:03.172  7065  7065 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 21:11:03.172  7065  7065 D SecurityLogAgent: StateMachine : Current State = 1
08-26 21:11:03.172  7065  7065 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 21:11:03.182  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-26 21:11:03.182  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 21:11:03.182  1018  1127 I WifiNative-HAL: startHal
08-26 21:11:03.182  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f2c088c
08-26 21:11:03.182  1018  1127 I WifiNative-HAL: Could not start hal
,08-26 21:11:03.182  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 21:11:03.182  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 21:11:03.182  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 21:11:03.182  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:11:03.182   279  1016 D CommandListener: Setting iface cfg
08-26 21:11:03.182   279  1016 D CommandListener: Trying to bring up p2p0
,08-26 21:11:03.182  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:11:03.182  1018  1126 D WifiP2pService: P2pEnablingState
,08-26 21:11:03.192  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 21:11:03.192  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 21:11:03.192  1018  1126 D WifiP2pService: P2p socket connection successful
08-26 21:11:03.192  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:11:03.192  1018  1151 I WifiNative-HAL: startHal
08-26 21:11:03.192  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e1829bc
08-26 21:11:03.192  1018  1151 I WifiNative-HAL: Could not start hal
08-26 21:11:03.192  1018  1151 E WifiScanningService: could not start HAL
08-26 21:11:03.192  1018  1126 D WifiP2pService: P2pEnabledState
,08-26 21:11:03.192  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 21:11:03.192  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-26 21:11:03.192  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 21:11:03.192  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 21:11:03.192  1018  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:11:03.192  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 21:11:03.192  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 21:11:03.192  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 21:11:03.192  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 21:11:03.192  7769  7769 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 21:11:03.192  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 21:11:03.192  7769  7769 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-26 21:11:03.192  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 21:11:03.192  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:11:03.192  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 21:11:03.192  1018  1048 D WifiDisplayController: disconnect
08-26 21:11:03.192  1018  1048 D WifiDisplayController: updateConnection
08-26 21:11:03.192  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 21:11:03.192  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 21:11:03.202  7769  7769 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 21:11:03.202  1018  1127 E WifiStateMachine: Failed to set frequency band 0
08-26 21:11:03.202  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 21:11:03.202  1018  1321 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 21:11:03.202  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 21:11:03.202  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:11:03.202  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:03.202  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 21:11:03.202  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-26 21:11:03.202  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
,08-26 21:11:03.202  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 21:11:03.202  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 21:11:03.202  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-26 21:11:03.212  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:11:03.212  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:03.212  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 21:11:03.212  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  secondary type: null
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  wps: 0
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  grpcapab: 0
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  devcapab: 0
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  status: 3
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  wfdInfo: null
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-26 21:11:03.212  1018  1048 D WifiDisplayController:  SConnectInfo : null
08-26 21:11:03.212  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 21:11:03.212  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:11:03.212  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-26 21:11:03.212  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 21:11:03.212  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:11:03.212  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 21:11:03.212  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:11:03.222  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:11:03.222  7614  7614 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 21:11:03.222  7614  7614 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 21:11:03.222  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 21:11:03.232  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 21:11:03.232  1018  1126 D WifiP2pService: InactiveState
,08-26 21:11:03.232  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-26 21:11:03.232  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 21:11:03.232  7769  7769 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 21:11:03.232  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-26 21:11:03.232  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:03.712  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:03.722  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:03.722  1018  3300 D SSRM:n  : SIOP:: AP = 350
,08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16e8a132 Bundle[{}]
,08-26 21:11:03.722  6812  6969 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 21:11:03.722  6812  6969 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 21:11:03.722  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 21:11:03.732  6812  6969 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 21:11:03.732  6812  6969 I System.out: Running OutgoingSocketThread
,08-26 21:11:03.742  6812  7778 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1365)
,08-26 21:11:03.742  6812  7778 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56282
,08-26 21:11:03.742  6812  7778 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 21:11:03.802   292   292 E SMD     : DCD OFF
,08-26 21:11:04.352  7769  7769 I wpa_supplicant: nl80211: Received scan results (36 BSSes),
08-26 21:11:04.352  7769  7769 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 21:11:04.352  7769  7769 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 21:11:04.352  7769  7769 I wpa_supplicant: Trying to associate with  'G700'
08-26 21:11:04.362  1018  7775 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 21:11:04.362  7769  7769 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 21:11:04.362  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 21:11:04.382  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 21:11:04.382  1018  1127 D SecContentProvider2: mCursor = null,
,08-26 21:11:04.472  7769  7769 E wpa_supplicant: Cmd 35605 not handled
,08-26 21:11:04.472  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 21:11:04.472  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:11:04.472  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
08-26 21:11:04.472  7769  7769 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 21:11:04.472  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 21:11:04.472  7769  7769 I wpa_supplicant: Associated with F4.99.3E
08-26 21:11:04.472  7769  7769 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 21:11:04.482  7769  7769 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 21:11:04.482  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 21:11:04.482  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:11:04.482  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:11:04.482  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 21:11:04.482  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 21:11:04.482  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 21:11:04.482  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 21:11:04.482  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 21:11:04.482  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 21:11:04.482  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-26 21:11:04.492  1018  1130 E Tethering: No numeric data
,08-26 21:11:04.492  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:11:04.492  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:04.492  1018  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 21:11:04.492  1018  1130 D Tethering: clearTetheredNotification()
,08-26 21:11:04.492  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 21:11:04.492  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:04.492  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 21:11:04.492  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 21:11:04.492  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 21:11:04.492  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 21:11:04.492  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:11:04.492  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:04.502  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:04.502  1018  1124 V NetworkStats: performPollLocked() took 7ms
,08-26 21:11:04.502  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:04.502  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:04.512  7769  7769 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 21:11:04.512  7769  7769 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 21:11:04.512  7769  7769 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 21:11:04.512  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
08-26 21:11:04.512  7769  7769 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:11:04.512  7769  7769 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 21:11:04.512  7769  7769 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 21:11:04.512  7769  7769 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 21:11:04.512  7769  7769 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 21:11:04.512  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 21:11:04.512  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 21:11:04.512  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-26 21:11:04.512  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 21:11:04.522  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-26 21:11:04.522  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 21:11:04.532  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 21:11:04.532  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:11:04.532  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 21:11:04.532  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:11:04.532  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:11:04.532  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:04.532  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:11:04.532  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:04.532  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:11:04.542  2191  2191 I Hs20UtilService: Starting #21
,08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:04.542  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:04.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.542  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:11:04.542  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:11:04.542  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 21:11:04.552  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 21:11:04.552  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:11:04.552  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-26 21:11:04.552  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:11:04.552  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 21:11:04.552  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 21:11:04.552   279  1016 D CommandListener: Setting iface cfg
08-26 21:11:04.562  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 21:11:04.562  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 21:11:04.562  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:04.572  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:04.572  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:04.582  1018  1127 E WifiNative-wlan0: do suspend false
,08-26 21:11:04.582  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-26 21:11:04.582  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 21:11:04.582  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 21:11:04.582  1018  1127 D SecContentProvider2: mCursor = null
,08-26 21:11:04.742  6812  6969 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1366)
,08-26 21:11:04.742  6812  6969 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1366)
,08-26 21:11:04.742  6812  6969 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1371)
,08-26 21:11:04.742  6812  6969 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 21:11:04.742  6812  6969 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1372)
,08-26 21:11:04.752  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:11:04.752  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30fdbc8c added. We now have 2 listener(s)
,08-26 21:11:04.752  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 21:11:04.762  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:11:04.762  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:11:04.762  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:04.762  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc41fd5 added. We now have 9 listener(s)
,08-26 21:11:04.762  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:04.762  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-26 21:11:04.762  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:04.772  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:04.772  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:04.772  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:11:04.772  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313d46db added. We now have 3 listener(s)
,08-26 21:11:04.782  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b101578 added. We now have 10 listener(s)
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:04.782  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:11:04.782  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:04.782  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:04.782  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30fdbc8c removed from the list
08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:04.782  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc41fd5 removed from the list
,08-26 21:11:04.782  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.782  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:04.782  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:04.782  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc41fd5 not in the list
08-26 21:11:04.782  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:04.782  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b101578 removed from the list
08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:04.792  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.792  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313d46db removed from the list
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f33e451 added. We now have 2 listener(s)
08-26 21:11:04.792  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-26 21:11:04.792  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:04.792  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:04.792  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104f14b6 added. We now have 9 listener(s)
08-26 21:11:04.792  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:04.792  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:04.802  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:04.802  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:04.802  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:11:04.802  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:04.802  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ded1124 added. We now have 3 listener(s)
,08-26 21:11:04.802  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:04.802  7781  7781 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 21:11:04.812  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:04.812  7781  7781 I dhcpcd  : version 5.5.6 starting
,08-26 21:11:04.812  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:04.812  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:04.812  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:04.812  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:04.812  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f01748d added. We now have 10 listener(s)
08-26 21:11:04.812  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:04.812  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:04.812  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:04.812  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:11:04.812  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:11:04.812  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:11:04.812  7781  7781 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 21:11:04.822  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:11:04.822  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:11:04.822  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:04.832  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:04.832  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:11:04.832  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:11:04.832  3219  3326 D BtGatt.GattService: registerClient() - UUID=12410556-b025-4ce3-9cbe-7843f4290a64
,08-26 21:11:04.862  7781  7781 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-26 21:11:04.862  7781  7781 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 21:11:04.862  7781  7781 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 21:11:04.862  7781  7781 I dhcpcd  : bssid match,
08-26 21:11:04.862  7781  7781 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-26 21:11:04.872  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=12410556-b025-4ce3-9cbe-7843f4290a64, clientIf=6
,08-26 21:11:04.872  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 21:11:04.872  3219  7177 D BtGatt.GattService: start scan with filters
08-26 21:11:04.882  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: handling starting scan
08-26 21:11:04.882  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:11:04.882  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:11:04.882  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:11:04.882  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-26 21:11:04.882  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: allow scan with filters
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6,
08-26 21:11:04.882  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 21:11:04.882  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:11:04.882  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 21:11:04.882  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 21:11:04.882  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:04.892  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 21:11:04.892  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:04.892  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:04.892  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:11:04.892  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:04.892  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:04.892  6812  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:11:04.892  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:04.892  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 21:11:04.892  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.892  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 21:11:04.902  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:11:04.902  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:11:04.902  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 21:11:04.902  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:11:04.902  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:11:04.902  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:11:04.902  3219  3233 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:11:04.902  3219  3328 D BtGatt.ScanManager: filter size is 1
,08-26 21:11:04.902  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 6
,08-26 21:11:04.902  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 21:11:04.902  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.902  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:11:04.902  3219  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:11:04.902  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 21:11:04.902  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.902  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 21:11:04.912  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 21:11:04.912  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:04.912  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 21:11:04.912  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:04.912  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:04.912  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:11:04.912  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:04.912  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:04.912  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:04.912  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f33e451 removed from the list
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:04.912  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104f14b6 removed from the list
08-26 21:11:04.912  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.912  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:04.912  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104f14b6 not in the list
08-26 21:11:04.912  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:04.912  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f01748d removed from the list
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:04.912  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:04.912  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:04.912  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:04.912  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ded1124 removed from the list
,08-26 21:11:04.922  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:04.922  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9dcc89 added. We now have 2 listener(s)
,08-26 21:11:04.922  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:04.922  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:04.922  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:04.922  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:04.922  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1578048e added. We now have 9 listener(s)
08-26 21:11:04.922  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:04.922  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:04.922  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:04.922  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:04.932  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:04.932  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:11:04.932  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:04.932  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12af60bc added. We now have 3 listener(s)
,08-26 21:11:04.932  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:04.932  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:04.932  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:04.932  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:04.932  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:04.932  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:04.932  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318da845 added. We now have 10 listener(s)
08-26 21:11:04.932  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:04.932  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:04.932  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:04.932  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:04.932  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:11:04.932  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:11:04.932  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:11:04.932  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:11:04.942  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:11:04.942  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:04.942  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:04.942  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:11:04.942  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:11:04.952  3219  7177 D BtGatt.GattService: registerClient() - UUID=bb878a98-6c3e-4d90-a0f7-7db39cea3409
,08-26 21:11:04.952  7781  7781 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-26 21:11:04.992  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=bb878a98-6c3e-4d90-a0f7-7db39cea3409, clientIf=6
08-26 21:11:04.992  6812  7610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 21:11:04.992  3219  7178 D BtGatt.GattService: start scan with filters
,08-26 21:11:04.992  3219  3328 D BtGatt.ScanManager: handling starting scan
,08-26 21:11:04.992  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:11:04.992  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:11:04.992  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:11:04.992  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:11:04.992  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 21:11:04.992  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:04.992  3219  3328 D BtGatt.ScanManager: allow scan with filters
08-26 21:11:04.992  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 21:11:04.992  3219  3328 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-26 21:11:05.002  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 21:11:05.002  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:05.002  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:11:05.002  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 21:11:05.002  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:05.002  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:11:05.002  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:11:05.002  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 21:11:05.002  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.002  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:05.002  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 21:11:05.012  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.012  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:11:05.012  6812  6969 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 21:11:05.012  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:11:05.012  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:05.012  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:05.022  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:05.022  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9dcc89 removed from the list
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.022  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1578048e removed from the list
08-26 21:11:05.022  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:05.022  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 21:11:05.022  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.022  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1578048e not in the list
,08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 21:11:05.022  3219  3326 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:11:05.022  3219  3328 D BtGatt.ScanManager: filter size is 1
,08-26 21:11:05.022  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 7
08-26 21:11:05.022  3219  7177 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:11:05.022  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:11:05.022  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:11:05.022  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.022  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:11:05.022  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318da845 removed from the list
08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:05.032  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12af60bc removed from the list
,08-26 21:11:05.032  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ee583c1 added. We now have 2 listener(s)
,08-26 21:11:05.032  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:05.032  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:05.032  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 21:11:05.032  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.032  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:05.032  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e241766 added. We now have 9 listener(s)
08-26 21:11:05.032  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:05.032  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:11:05.032  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 21:11:05.032  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.042  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:05.042  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:05.042  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:05.042  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:11:05.042  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:05.042  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1490b54 added. We now have 3 listener(s)
,08-26 21:11:05.052  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:05.052  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 21:11:05.052  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:05.052  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 21:11:05.052  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:05.052  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:05.052  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24859afd added. We now have 10 listener(s)
,08-26 21:11:05.052  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:05.052  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:05.052  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:05.052  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-26 21:11:05.052  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:11:05.052  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-26 21:11:05.052  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:11:05.062  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:11:05.062  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:05.062  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:05.062  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 21:11:05.062  6812  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:11:05.062  3219  3233 D BtGatt.GattService: registerClient() - UUID=932c99b5-03cc-437e-8a66-f74f12715e7a
,08-26 21:11:05.112  3219  3280 D BtGatt.GattService: onClientRegistered() - UUID=932c99b5-03cc-437e-8a66-f74f12715e7a, clientIf=6
,08-26 21:11:05.112  6812  6823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 21:11:05.112  3219  3326 D BtGatt.GattService: start scan with filters
,08-26 21:11:05.112  3219  3328 D BtGatt.ScanManager: handling starting scan
,08-26 21:11:05.112  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:11:05.112  3219  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 21:11:05.112  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:05.112  3219  3328 D BtGatt.ScanManager: allow scan with filters
,08-26 21:11:05.112  3219  3328 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 21:11:05.112  3219  3328 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-26 21:11:05.112  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 21:11:05.112  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:05.112  3219  3328 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:11:05.122  7781  7781 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-26 21:11:05.122  3219  3328 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 21:11:05.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:11:05.122  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:11:05.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:11:05.122  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 21:11:05.122  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 21:11:05.122  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:11:05.122  3219  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 21:11:05.122  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.122  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:05.132  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 21:11:05.132  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.142  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 21:11:05.142  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:05.142  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:05.142  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:05.142  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ee583c1 removed from the list
,08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.142  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e241766 removed from the list
08-26 21:11:05.142  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:05.142  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 21:11:05.142  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.142  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e241766 not in the list
08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:11:05.142  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:11:05.142  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:11:05.142  3219  7178 D BtGatt.GattService: stopScan() - queue size =1
08-26 21:11:05.142  3219  3328 D BtGatt.ScanManager: filter size is 1
08-26 21:11:05.142  3219  3328 D BtGatt.ScanManager: delete FilterIndex - 8
,08-26 21:11:05.152  3219  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 21:11:05.152  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.152  3219  3328 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:11:05.152  3219  7177 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:11:05.152  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-26 21:11:05.152  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:11:05.152  3219  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 21:11:05.152  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 21:11:05.152  3219  3328 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 21:11:05.152  3219  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 21:11:05.152  3219  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:11:05.152  6812  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:11:05.152  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:11:05.162  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-26 21:11:05.162  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:05.162  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 21:11:05.162  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:05.162  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24859afd removed from the list
08-26 21:11:05.162  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:11:05.162  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.162  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:05.162  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:11:05.162  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1490b54 removed from the list
08-26 21:11:05.162  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:11:05.162  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:05.162  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:05.172  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:11:05.172  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2315e9f9 added. We now have 2 listener(s)
,08-26 21:11:05.172  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:05.172  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:05.172  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:05.172  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:05.172  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d34ad3e added. We now have 9 listener(s)
08-26 21:11:05.172  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:05.172  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:05.172  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:05.182  6812  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:05.182  6812  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:05.182  6812  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:11:05.182  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:05.182  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bea70ec added. We now have 3 listener(s)
,08-26 21:11:05.182  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:05.192  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:05.192  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c22cb5 added. We now have 10 listener(s)
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:05.192  6812  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:11:05.192  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:05.192  6812  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:05.192  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:05.192  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2315e9f9 removed from the list
08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.192  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d34ad3e removed from the list
,08-26 21:11:05.192  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:05.192  6812  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:05.192  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:05.192  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:11:05.192  6812  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d34ad3e not in the list
08-26 21:11:05.192  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.192  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:05.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:05.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:05.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:05.202  6812  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c22cb5 removed from the list
08-26 21:11:05.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:05.202  6812  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:05.202  6812  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:05.202  6812  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:05.202  6812  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bea70ec removed from the list
,08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 21:11:05.202  6812  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:05.202  6812  7800 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1379, name: My test thread name)
,08-26 21:11:05.202  6812  7800 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1379, thread name: My test thread name)
08-26 21:11:05.202  6812  7800 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1379, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 21:11:05.212  6812  7802 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1381, name: My test thread name),
08-26 21:11:05.212  6812  7802 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1381, thread name: My test thread name)
08-26 21:11:05.212  6812  7802 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1381, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 21:11:05.212  6812  6969 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-26 21:11:05.212  6812  6969 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 21:11:05.212  6812  6969 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 21:11:05.212  6812  6969 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0,
08-26 21:11:05.212  6812  6969 D com.test.thalitest.ThaliTestRunner: Total duration: 23272 ms
08-26 21:11:05.212  6812  6969 I jxcore-log: *Native tests were executed*
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: Total number of executed tests:  80,
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: Number of passed tests:  80
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: Number of failed tests:  0
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: Number of ignored tests:  0,
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: Total duration:  23272
08-26 21:11:05.212  6812  6969 I jxcore-log: 
08-26 21:11:05.212  6812  6969 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 21:11:05.212  6812  6969 I jxcore-log: 
,08-26 21:11:05.222  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.222  6812  6969 I jxcore-log: 
08-26 21:11:05.222  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.222  6812  6969 I jxcore-log: 
08-26 21:11:05.222  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.222  6812  6969 I jxcore-log: 
08-26 21:11:05.222  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.222  6812  6969 I jxcore-log: 
08-26 21:11:05.222  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.222  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.232  6812  6812 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 21:11:05.232  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.232  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
,08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
,08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
,08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.242  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 21:11:05.242  6812  6969 I jxcore-log: 
08-26 21:11:05.252  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.252  6812  6969 I jxcore-log: 
,08-26 21:11:05.252  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.252  6812  6969 I jxcore-log: 
,08-26 21:11:05.252  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.252  6812  6969 I jxcore-log: 
,08-26 21:11:05.252  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:05.252  6812  6969 I jxcore-log: 
,08-26 21:11:05.392  1018  1127 E WifiNative-wlan0: do suspend true,
,08-26 21:11:05.412  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 21:11:05.412  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:05.412  6812  6969 I jxcore-log: 
,08-26 21:11:05.422  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-26 21:11:05.422  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 21:11:05.422  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 21:11:05.422  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,08-26 21:11:05.432  1018  1129 E ConnectivityService: updateNetworkInfo(),
08-26 21:11:05.432  1018  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 21:11:05.432  1018  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-26 21:11:05.432  1018  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 21:11:05.432  1018  1129 D ConnectivityService: Adding iface wlan0 to network 504
08-26 21:11:05.432  1018  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-26 21:11:05.432  1018  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 21:11:05.432  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 21:11:05.432  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:11:05.432  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.432  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.442  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.442  1018  1265 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:11:05.452  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 21:11:05.452  1018  1265 W ActivityManager: userId = 0, bbcId = -10000,
08-26 21:11:05.452  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:05.452  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 21:11:05.452  2191  2191 I Hs20UtilService: Starting #22
08-26 21:11:05.452  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:11:05.462  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-26 21:11:05.462  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:11:05.462  4815  4815 I NearbySettings: MountReceiver.onReceive - Keep current state,
,08-26 21:11:05.472  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 21:11:05.472  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 21:11:05.482  1018  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 21:11:05.482  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:11:05.482  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.482  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.482  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.482  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:05.482  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:05.482  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 21:11:05.482  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 21:11:05.482  2191  2191 I Hs20UtilService: Starting #23
,08-26 21:11:05.482  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 21:11:05.482  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 21:11:05.482  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
08-26 21:11:05.492  2191  2216 I Hs20UtilService: Message received 5007
,08-26 21:11:05.492  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 21:11:05.492  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.492  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 21:11:05.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:05.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.492  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:11:05.492  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-26 21:11:05.492  4815  4815 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 21:11:05.492  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 21:11:05.502  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 21:11:05.502  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 21:11:05.502  4815  4815 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 21:11:05.502  4815  4815 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 21:11:05.502  4815  4858 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 21:11:05.502  1018  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-26 21:11:05.502  1018  1129 D ConnectivityService: LTETest block dns file not exists
,08-26 21:11:05.512  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.512  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 21:11:05.512  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-26 21:11:05.512  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:05.512  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:05.512  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.512  1018  1129 V NetworkStats: performPollLocked() took 6ms
08-26 21:11:05.522  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.522  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.522  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 21:11:05.522  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:11:05.522  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 21:11:05.522  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:11:05.522  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.522  1018  1129 V NetworkStats: updateIfacesLocked()
,08-26 21:11:05.522  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-26 21:11:05.522  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:05.522  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:05.522  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.522  1018  1129 V NetworkStats: performPollLocked() took 5ms
,08-26 21:11:05.532  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.532  1018  1522 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 21:11:05.532  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.532  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 21:11:05.532  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-26 21:11:05.532  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:11:05.532  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 21:11:05.532  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:11:05.532  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-26 21:11:05.532  1018  7779 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 21:11:05.532  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:05.532  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:05.532  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 21:11:05.532  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 21:11:05.532  1018  1129 D ConnectivityService:    accepting network in place of null
,08-26 21:11:05.532  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 21:11:05.532  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 21:11:05.532  1483  1483 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 21:11:05.532  1483  1483 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 21:11:05.532  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 21:11:05.532  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 21:11:05.532   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 21:11:05.532  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:11:05.532   279  1012 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-26 21:11:05.532  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-26 21:11:05.532  2191  2191 I Hs20UtilService: Starting #24
,08-26 21:11:05.542  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:05.542  6812  6969 I jxcore-log: 
,08-26 21:11:05.542  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 21:11:05.542  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 21:11:05.542  4815  4815 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 21:11:05.542  4815  4815 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 21:11:05.542  1018  1130 D Tethering: MasterInitialState.processMessage what=3
08-26 21:11:05.542  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 21:11:05.542  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 21:11:05.542  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.542  1018  1124 V NetworkStats: updateIfacesLocked()
08-26 21:11:05.542  2191  2216 I Hs20UtilService: Message received 5007
08-26 21:11:05.542  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 21:11:05.542  1177  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 21:11:05.542  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:05.542  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 21:11:05.552  7812  7812 D AndroidRuntime: 
08-26 21:11:05.552  7812  7812 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 21:11:05.552  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.552  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.552  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.552  7812  7812 D AndroidRuntime: CheckJNI is OFF
08-26 21:11:05.552  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 21:11:05.552  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 21:11:05.552  7812  7812 D AndroidRuntime: readGMSProperty: start
08-26 21:11:05.552  7812  7812 D AndroidRuntime: readGMSProperty: already setted!!,
08-26 21:11:05.552  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 21:11:05.552  7812  7812 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 21:11:05.552  7812  7812 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 21:11:05.552  7812  7812 D AndroidRuntime: readGMSProperty: end
08-26 21:11:05.552  7812  7812 D AndroidRuntime: addProductProperty: start
,08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.552  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.552  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 21:11:05.562  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.562  1018  1124 V NetworkStats: performPollLocked() took 15ms
,08-26 21:11:05.562  1018  1321 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
08-26 21:11:05.562  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:05.562  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:05.562  1018  1320 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 21:11:05.562  1018  1320 D SecContentProvider2: mCursor = null
,08-26 21:11:05.562  1018  1265 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-26 21:11:05.562  1018  1265 D SecContentProvider2: mCursor = null
,08-26 21:11:05.572  1018  1494 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 21:11:05.572  1018  1494 D SecContentProvider2: mCursor = null
08-26 21:11:05.572  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 21:11:05.572  1018  1031 D SecContentProvider2: mCursor = null
,08-26 21:11:05.572  1018  1522 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 21:11:05.572  1018  1522 D SecContentProvider2: mCursor = null
,08-26 21:11:05.572  1018  1504 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 21:11:05.572  1018  1504 D SecContentProvider2: mCursor = null
,08-26 21:11:05.592   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 21:11:05.602  1018  1031 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-26 21:11:05.612  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 21:11:05.632  1018  7779 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-26 21:11:05.662  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:11:05.662  6812  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:05.662  6812  6969 I jxcore-log: 
,08-26 21:11:05.682  7812  7812 E AffinityControl: AffinityControl: registerfunction enter
,08-26 21:11:05.692  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:11:05 GMT], X-Android-Received-Millis=[1472238665702], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472238665668]}
08-26 21:11:05.692  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 21:11:05.692  1018  7779 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 21:11:05.692  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 21:11:05.692  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 21:11:05.692  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 21:11:05.692  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-26 21:11:05.702  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 21:11:05.702  1177  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: EthernetConnected: false,
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 21:11:05.702  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0,
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte,
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 21:11:05.702  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.702  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 21:11:05.712  7812  7812 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 21:11:05.722  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 21:11:05.722  1018  1031 D PackageManager: START PACKAGE DELETE: observer{674787147}
08-26 21:11:05.722  1018  1031 D PackageManager: pkg{<packageName>}
08-26 21:11:05.722  1018  1031 D PackageManager: user{0}
08-26 21:11:05.722  1018  1031 D PackageManager: caller{2000}
08-26 21:11:05.722  1018  1031 D PackageManager: flags{2}
08-26 21:11:05.722  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 21:11:05.722  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
,08-26 21:11:05.722  1018  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 21:11:05.722  1018  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-26 21:11:05.732  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-26 21:11:05.732  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 21:11:05.732  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-26 21:11:05.732  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 21:11:05.732  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 21:11:05.732  1018  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-26 21:11:05.742  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-26 21:11:05.742  1018  1043 I ActivityManager: Killing 6812:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 21:11:05.872   259   817 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 21:11:05.872  1018  1320 I WindowState: WIN DEATH: Window{14ffe7ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 21:11:05.872   259   438 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 21:11:05.892  1018  1320 D InputDispatcher: Focus left window: 6812
,08-26 21:11:05.902  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{36544285 u0 com.test.thalitest/.MainActivity t163}
,08-26 21:11:05.902  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 21:11:05.902  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 21:11:05.912  1018  1514 W ActivityManager: Spurious death for ProcessRecord{30f26d28 6812:com.test.thalitest/u0a170}, curProc for 6812: null
,08-26 21:11:05.922  1018  1043 D InputDispatcher: Focused application released
,08-26 21:11:05.932  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-26 21:11:05.942  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 21:11:05.962  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 21:11:05.962  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 21:11:05.962  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 21:11:05.962  1018  1321 D BatteryService: stay LED for charging
,08-26 21:11:05.982  2830  2830 I art     : Explicit concurrent mark sweep GC freed 16604(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 785us total 35.476ms
,08-26 21:11:06.002  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 21:11:06.002  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 21:11:06.002  1998  1998 E SamsungIME: mOCRHelper is null
,08-26 21:11:06.022  1605  1856 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 21:11:06.052  1464  1464 D PersonaManager: isKioskContainerExistOnDevice
,08-26 21:11:06.052  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:11:06.052  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 21:11:06 GMT+02:00 2016
,08-26 21:11:06.062  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-26 21:11:06.062  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 21:11:06.062  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-26 21:11:06.062  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 21:11:06.062  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 21:11:06.062  1464  1464 D RegisteredServicesCache: empty dynamic service
,08-26 21:11:06.062  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-26 21:11:06.062  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:06.072  1018  1265 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 21:11:06.072  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.072  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.072  1018  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:06.072  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 21:11:06.072  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-26 21:11:06.072  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 21:11:06.072  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-26 21:11:06.082  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 21:11:06.082  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-26 21:11:06.082  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-26 21:11:06.082  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-26 21:11:06.082  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-26 21:11:06.082  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 21:11:06.082  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 21:11:06.082  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 21:11:06.082  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 21:11:06.092  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 21:11:06.092  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.092  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 21:11:06.102  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 21:11:06.112  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 21:11:06.112  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 21:11:06.112  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 21:11:06.112  3219  7742 D HeadsetStateMachine: Disconnected process message: 10
,08-26 21:11:06.112  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 21:11:06.112  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 21:11:06.112  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 21:11:06.112  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 21:11:06.122  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 21:11:06.122  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:11:06.122  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 21:11:06.122  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.122  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-26 21:11:06.132  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-26 21:11:06.142  1018  1321 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,08-26 21:11:06.142  1018  1321 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-26 21:11:06.142  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:06.142  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 21:11:06.142  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-26 21:11:06.142  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 21:11:06.142  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.142  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.142  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.142  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.152  7832  7832 E Zygote  : MountEmulatedStorage()
,08-26 21:11:06.152  7832  7832 I libpersona: KNOX_SDCARD checking this for 10090
08-26 21:11:06.152  7832  7832 E Zygote  : v2
08-26 21:11:06.152  7832  7832 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:06.162  7832  7832 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:11:06.162  7832  7832 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:11:06.162  1018  1321 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7832 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-26 21:11:06.162  1018  1490 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 21:11:06.162  1018  1490 D SecContentProvider2: mCursor = null
08-26 21:11:06.162  7832  7832 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.182   325   325 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 23.195ms
08-26 21:11:06.192  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-26 21:11:06.192  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.192  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.192  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.192  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.212  7832  7832 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:11:06.212  7832  7832 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.212   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 20.436ms
,08-26 21:11:06.232   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.665ms,
,08-26 21:11:06.232  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.232  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 21:11:06.242  7847  7847 E Zygote  : MountEmulatedStorage()
,08-26 21:11:06.242  7847  7847 E Zygote  : v2
08-26 21:11:06.242  7847  7847 I libpersona: KNOX_SDCARD checking this for 10052
08-26 21:11:06.242  7847  7847 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:06.242  7847  7847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.242  7847  7847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:11:06.242  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7847 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-26 21:11:06.242  2814  7830 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-26 21:11:06.252  7847  7847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.252  2814  7830 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-26 21:11:06.252  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 21:11:06.252  1464  1464 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 21:11:06.252  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.252  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.252  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.252  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.252  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 21:11:06.262  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 21:11:06.262  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 21:11:06.262  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 21:11:06.272  7858  7858 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.272  7858  7858 E Zygote  : v2
08-26 21:11:06.272  7858  7858 I libpersona: KNOX_SDCARD checking this for 10032
08-26 21:11:06.272  7858  7858 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:06.272  7858  7858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.272  7858  7858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:11:06.272  1018  1321 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7858 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:11:06.272  7858  7858 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
08-26 21:11:06.272  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-26 21:11:06.282  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.282  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.282  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.282  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.282  7847  7847 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.282  7847  7847 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.292  1018  1057 I art     : Explicit concurrent mark sweep GC freed 69714(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 3.444ms total 274.393ms
,08-26 21:11:06.302  7872  7872 E Zygote  : MountEmulatedStorage()
,08-26 21:11:06.302  7872  7872 E Zygote  : v2
08-26 21:11:06.302  7872  7872 I libpersona: KNOX_SDCARD checking this for 10098
08-26 21:11:06.302  7872  7872 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.302  7872  7872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.302  7872  7872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:11:06.302  1464  1464 D PersonaManager: isKioskContainerExistOnDevice
08-26 21:11:06.302  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7872 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 21:11:06.302  7872  7872 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.312  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 21:11:06.312  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy(),
,08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-26 21:11:06.312  1018  3300 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 21:11:06.312  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 21:11:06.322  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-26 21:11:06.322  7858  7858 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:11:06.332  7858  7858 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.342  1018  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-26 21:11:06.352  7872  7872 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.352  7872  7872 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.382  1018  1018 I MotionRecognitionService: Plugged
08-26 21:11:06.382  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 21:11:06.382  7832  7832 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 21:11:06.382  7832  7832 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 21:11:06.392  7832  7832 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 21:11:06.392  1018  1504 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 21:11:06.392  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.392  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.392  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:06.392  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 21:11:06.392  1018  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-26 21:11:06.392  7832  7832 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-26 21:11:06.402  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.402  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.402  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.402  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.402  7832  7832 D elm:15121: ElmAgentService : onCreate()
,08-26 21:11:06.402  7832  7892 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-26 21:11:06.412  7832  7892 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-26 21:11:06.412  7832  7892 D elm:15121: MDMBridge.getInstance()
08-26 21:11:06.412  7832  7892 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 21:11:06.412  7893  7893 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.412  7893  7893 E Zygote  : v2
08-26 21:11:06.412  7893  7893 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:11:06.412  7893  7893 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.412  7893  7893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 21:11:06.412  7893  7893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:11:06.412  1018  1139 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7893 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 21:11:06.412  1018  1139 I ActivityManager: Killing 7323:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 21:11:06.422  7893  7893 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.432  7832  7892 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 21:11:06.442  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 21:11:06.442  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.452  1660  1660 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-26 21:11:06.452  1660  1660 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-26 21:11:06.452  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.452  7832  7832 D elm:15121: ElmAgentService : onDestroy().
,08-26 21:11:06.462  7893  7893 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.462  1018  1030 I ActivityManager: Killing 7340:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-26 21:11:06.462  7893  7893 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.472  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 21:11:06.472  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.472  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.472  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.472  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 21:11:06.492  1822  7911 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-26 21:11:06.492  1822  7911 D AccountUtils: Clearing selected account for com.test.thalitest
,08-26 21:11:06.492  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.492  7858  7910 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 21:11:06.492  7858  7910 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 21:11:06.502  1018  1265 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-26 21:11:06.502  1018  1265 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.502  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.502  1018  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 21:11:06.502  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-26 21:11:06.512  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 21:11:06.512  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 21:11:06.512  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 21:11:06.512  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:11:06.512  7858  7910 D SPPClientService: PushLog.txt file is not deleted.
08-26 21:11:06.512  7858  7910 D SPPClientService: PushLog.txt file is not deleted.
08-26 21:11:06.512  7858  7910 D SPPClientService: ============PushLog. stop!
,08-26 21:11:06.522  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.522  1018  1522 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-26 21:11:06.522  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.532  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.532  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.532  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.532  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-26 21:11:06.532  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 21:11:06.532  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 21:11:06.532  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.532  1018  1321 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-26 21:11:06.532  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.542  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 21:11:06.542  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 21:11:06.542  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 21:11:06.542  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
08-26 21:11:06.542  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-26 21:11:06.552  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 21:11:06.552  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.552  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 21:11:06.552  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
08-26 21:11:06.552  1018  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 21:11:06.562  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.562  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.562  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 21:11:06.562  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 21:11:06.562  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.562  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.562  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 21:11:06.562  1018  1057 D PackageManager: delete codoeFile: 
08-26 21:11:06.572  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-26 21:11:06.572  1018  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-26 21:11:06.572  1018  1057 D PackageManager: result of delete: 1{674787147}
08-26 21:11:06.572  1018  1139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 21:11:06.572  1018  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
08-26 21:11:06.572  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.572  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.572  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:11:06.582  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-26 21:11:06.582  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.582  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.582  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.582  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.592  7812  7812 D AndroidRuntime: Shutting down VM,
,08-26 21:11:06.592  1822  7911 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-26 21:11:06.592  7921  7921 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:11:06.592  7921  7921 E Zygote  : MountEmulatedStorage()
,08-26 21:11:06.592  7921  7921 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:06.592  7921  7921 E Zygote  : v2
08-26 21:11:06.602  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.602  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:11:06.602  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.612  1018  1320 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-26 21:11:06.612  1018  1320 I ActivityManager: Killing 7356:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 21:11:06.622  1018  1504 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 21:11:06.622  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.622  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.622  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.622  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:11:06.622  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 21:11:06.632  1018  1265 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 21:11:06.632  7667  7667 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-26 21:11:06.632  1018  1265 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.632  1018  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.632  1018  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:11:06.632  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.632  7921  7921 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.642  1018  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 21:11:06.642  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.642  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.642  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.642  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 21:11:06.642  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.642  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.642  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.642  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.652  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 21:11:06.662  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:11:06.672  7938  7938 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.672  7938  7938 E Zygote  : v2
08-26 21:11:06.672  7938  7938 I libpersona: KNOX_SDCARD checking this for 10011
08-26 21:11:06.672  7938  7938 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.672  7938  7938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 21:11:06.672  1822  7920 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
08-26 21:11:06.672  1822  7920 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-26 21:11:06.672  1822  7920 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-26 21:11:06.672  1822  7920 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-26 21:11:06.672  7938  7938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:11:06.672  7938  7938 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 21:11:06.672  1018  1504 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7938 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 21:11:06.682  1018  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-26 21:11:06.682  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.682  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.682  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.682  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.692  7950  7950 E Zygote  : MountEmulatedStorage(),
,08-26 21:11:06.702  7950  7950 E Zygote  : v2,
08-26 21:11:06.702  7950  7950 I libpersona: KNOX_SDCARD checking this for 10039,
08-26 21:11:06.702  1822  7920 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-26 21:11:06.702  1822  7920 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
08-26 21:11:06.702  1822  7920 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-26 21:11:06.702  7950  7950 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.702  7950  7950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.702  1822  7920 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
08-26 21:11:06.702  1822  7920 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2,
08-26 21:11:06.712  1822  7920 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
08-26 21:11:06.712  7950  7950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:11:06.712  7950  7950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 21:11:06.712  7938  7938 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:11:06.712  7938  7938 D ActivityThread: Added TimaKeyStore provider
08-26 21:11:06.712  1822  7920 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
08-26 21:11:06.712  1822  7920 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
08-26 21:11:06.712  1822  7920 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-26 21:11:06.722  1018  1514 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7950 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-26 21:11:06.722  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false,
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false,
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.,
08-26 21:11:06.732  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-26 21:11:06.732  7921  7921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-26 21:11:06.742  1018  1514 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-26 21:11:06.742  1018  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.742  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.742  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:06.742  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-26 21:11:06.752  1822  1822 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 21:11:06.752  1822  1822 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 21:11:06.752  1018  1265 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-26 21:11:06.762  7950  7950 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.762  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.762  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.762  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.762  1018  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.762  7950  7950 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.762  7938  7938 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 21:11:06.762  7938  7938 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 21:11:06.772  7971  7971 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.772  7667  7667 D BluetoothAdapter: cancelDiscovery
08-26 21:11:06.772  7971  7971 E Zygote  : v2
,08-26 21:11:06.772  7971  7971 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:11:06.772  7971  7971 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.782  7971  7971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:11:06.782  7971  7971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 21:11:06.782  7971  7971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.782  1018  1265 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 21:11:06.802  1018  1514 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 21:11:06.802  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:06.802  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:06.802  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 21:11:06.802   292   292 E SMD     : DCD OFF
08-26 21:11:06.802  7938  7938 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-26 21:11:06.802  7938  7938 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 21:11:06.812  7812  7812 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 21:11:06.812  7938  7938 I MultiDex: VM with version 2.1.0 has multidex support
08-26 21:11:06.812  7938  7938 I MultiDex: install
08-26 21:11:06.812  7938  7938 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 21:11:06.812  1018  1494 D LocationManagerService: getProviders()=[passive, gps]
,08-26 21:11:06.822  7971  7971 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.822  3219  3234 D BluetoothAdapterProperties: mDiscovering is false
08-26 21:11:06.822  3219  3234 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-26 21:11:06.822  7667  7667 D BluetoothAdapter: cancelDiscovery = true
08-26 21:11:06.822  7667  7667 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-26 21:11:06.822  1822  1822 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 21:11:06.822  1822  1822 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 21:11:06.822  7950  7950 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 21:11:06.822  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-26 21:11:06.822  3219  3278 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 21:11:06.822  7971  7971 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.832  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.832  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.832  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.832  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.852  7992  7992 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.852  7992  7992 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:11:06.852  7992  7992 E Zygote  : v2
08-26 21:11:06.852  7992  7992 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:06.852  7992  7992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 21:11:06.852  1018  1320 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 21:11:06.852  1018  1504 I ActivityManager: Killing 7373:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-26 21:11:06.852  7992  7992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:11:06.862  7992  7992 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 21:11:06.862  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 21:11:06.862  1018  1057 D PackageManager: userId{-1}
08-26 21:11:06.862  1018  1057 D PackageManager: andCode{true}
,08-26 21:11:06.872  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 21:11:06.872  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.872  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.872  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.872  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.882  8009  8009 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.882  8009  8009 E Zygote  : v2
08-26 21:11:06.882  8009  8009 I libpersona: KNOX_SDCARD checking this for 1000
08-26 21:11:06.882  8009  8009 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.882  8009  8009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.892  8009  8009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 21:11:06.892  1018  1504 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 21:11:06.892  8009  8009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.902  7992  7992 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.902  7992  7992 D ActivityThread: Added TimaKeyStore provider
08-26 21:11:06.902  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 21:11:06.902  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.902  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.902  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.902  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.912  8022  8022 E Zygote  : MountEmulatedStorage()
08-26 21:11:06.912  8022  8022 E Zygote  : v2
08-26 21:11:06.912  8022  8022 I libpersona: KNOX_SDCARD checking this for 10003
08-26 21:11:06.912  8022  8022 I libpersona: KNOX_SDCARD not a persona
,08-26 21:11:06.922  8022  8022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:06.922  8022  8022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 21:11:06.922  8022  8022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 21:11:06.922  8009  8009 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 21:11:06.922  7971  7971 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 21:11:06.932  8009  8009 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.942  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8022 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 21:11:06.942   325   325 I art     : Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 22.300ms
08-26 21:11:06.942  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-26 21:11:06.942  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-26 21:11:06.942  7667  7667 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-26 21:11:06.952  8022  8022 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:11:06.952  8022  8022 D ActivityThread: Added TimaKeyStore provider
,08-26 21:11:06.962   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.059ms
,08-26 21:11:06.972  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup,
,08-26 21:11:06.982  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 21:11:06.982  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.982  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 21:11:06.982  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 21:11:06.982   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 20.346ms
,08-26 21:11:07.002  8041  8041 E Zygote  : MountEmulatedStorage(),
08-26 21:11:07.002  8041  8041 E Zygote  : v2,
08-26 21:11:07.002  1018  1030 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8041 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
08-26 21:11:07.012  7992  8040 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED,
08-26 21:11:07.012  8041  8041 I libpersona: KNOX_SDCARD checking this for 10014
08-26 21:11:07.012  8041  8041 I libpersona: KNOX_SDCARD not a persona
08-26 21:11:07.012  8041  8041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 21:11:07.012  8009  8009 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 21:11:07.012  8009  8009 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 21:11:07.012  8009  8009 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-26 21:11:07.022  8041  8041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 21:11:07.022  8041  8041 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 21:11:07.022  7992  8040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-26 21:11:07.032  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-26 21:11:07.032  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-26 21:11:07.032  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 21:11:07.032  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 21:11:07.032  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-26 21:11:07.042  8009  8009 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 21:11:07.042  8009  8009 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:11:07.042  8009  8009 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 21:11:07.042  8041  8041 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 21:11:07.042  8009  8009 D AndroidRuntime: Shutting down VM
08-26 21:11:07.042  8009  8009 E AndroidRuntime: FATAL EXCEPTION: main
08-26 21:11:07.042  8009  8009 E AndroidRuntime: Process: com.sec.pcw.device, PID: 8009
08-26 21:11:07.042  8009  8009 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java,:1729)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 21:11:07.042  8009  8009 E AndroidRuntime: 	... 11 more
08-26 21:11:07.042  8041  8041 D ActivityThread: Added TimaKeyStore provider
08-26 21:11:07.042  1018  1494 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-26 21:11:07.042  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-26 21:11:07.042  7992  7992 D AcmsService: Enter Oncreate
,08-26 21:11:07.042  7992  7992 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 21:11:07.042  7992  7992 D AcmsService: creating AcmsCore
08-26 21:11:07.042  7992  7992 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-26 21:11:07.042  7992  7992 D AcmsCore: AcmsCore
,08-26 21:11:07.052  1018  1514 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,08-26 21:11:07.052  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:07.052  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:07.052  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-26 21:11:07.052  7992  7992 D AcmsCore: init
,08-26 21:11:07.052  7992  7992 D AcmsCore: Looper handler is not null
,08-26 21:11:07.052  7992  7992 D AcmsCore: Post to AcmsCoreHandler
08-26 21:11:07.052  7992  7992 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 21:11:07.052  7992  7992 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-26 21:11:07.052  7992  7992 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-26 21:11:07.052  7992  7992 D AcmsService: onStartCommand
08-26 21:11:07.052  7992  7992 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-26 21:11:07.052  7992  7992 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-26 21:11:07.052  7992  7992 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-26 21:11:07.052  7992  7992 D AcmsService: Incremented Counter Value : onStartCommand
,08-26 21:11:07.062  7938  7938 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 21:11:07.062  1018  1504 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-26 21:11:07.072  7992  7992 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-26 21:11:07.072  7847  7915 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 21:11:07.072  7992  8058 D AcmsCertificateMngr: AcmsCertificateMngr
,08-26 21:11:07.072  7992  7992 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,08-26 21:11:07.082  7992  8058 D AcmsRevocationMngr: AcmsRevocationMngr
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 21:11:07.082  1018  8060 E DropBoxManagerService: 	... 5 more
,08-26 21:11:07.082  1018  1320 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-26 21:11:07.082  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-26 21:11:07.082  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-26 21:11:07.082  1018  1320 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 21:11:07.082  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-26 21:11:07.092  7992  7992 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
08-26 21:11:07.092  7992,  7992 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:11:07.092  7992  7992 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:11:07.092  7992  7992 D AndroidRuntime: Shutting down VM
,08-26 21:11:07.092  7992  7992 E AndroidRuntime: FATAL EXCEPTION: main,
08-26 21:11:07.092  7992  7992 E AndroidRuntime: Process: ACMS.Process, PID: 7992
08-26 21:11:07.092  7992  7992 E AndroidRuntime: java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@2b18dcb8 with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3457)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:145)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:473)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:433)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
,08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	... 9 more
08-26 21:11:07.092  7992  7992 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 21:11:07.092  7992  7992 E AndroidRuntime: 	... 20 more
08-26 21:11:07.102  7971  7971 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)

```
