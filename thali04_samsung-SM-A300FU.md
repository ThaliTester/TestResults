#### Test 845006541b10566_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-09 16:05:43.687  1456  1857 D TP/MmsSmsProvider: match 2117:Elapsed time : 5.238 ms
09-09 16:05:43.697  6834  6834 D EasySignUpManager_1.0.1: isAuth is false
09-09 16:05:43.697  6834  6834 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-09 16:05:43.697  6834  6834 E CscParser: mps_code.dat does not exist
09-09 16:05:43.697  6834  6834 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:05:43.697  6834  6834 E CscParser: fileName + /system/csc/customer.xml
09-09 16:05:43.707  6834  6834 E CscParser: mps_code.dat does not exist
09-09 16:05:43.707  6834  6834 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:05:43.707  6834  6834 E CscParser: fileName + /system/csc/customer.xml
09-09 16:05:43.717  6834  6834 D CscParser: getInstance fileName =/system/csc/customer.xml
09-09 16:05:43.717  6834  6834 D Mms/MmsConfig:  enable multiwindow = false
09-09 16:05:43.727  6834  6834 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-09 16:05:43.727  6834  6834 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-09 16:05:43.727  6834  6834 D Mms/MmsConfig: [end]    init() consume time = 87.239375
09-09 16:05:43.727  6834  6834 D Mms/Contact: [start]    init() consume time = 0.648906
09-09 16:05:43.737  6834  6834 D Mms/Contact: [end]    init consume time = 9.358594
09-09 16:05:43.747  1456  1480 D TP/MmsSmsProvider: query,matched:13, calling pid = 6834
09-09 16:05:43.747  1456  1480 D TP/MmsSmsProvider: match 13:Elapsed time : 0.873 ms
09-09 16:05:43.757  6834  6954 D Mms/DraftCache: [start]    rebuildCache consume time = 22.58625
09-09 16:05:43.767  6834  6834 D Mms/MethodReflector: getSubId is called
09-09 16:05:43.767  6834  6834 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-09 16:05:43.767  1456  1857 D TP/MmsSmsProvider: query,matched:12, calling pid = 6834
09-09 16:05:43.767  1456  1857 D TP/MmsSmsProvider: match 12:Elapsed time : 1.166 ms
09-09 16:05:43.767  6834  6954 D Mms/DraftCache: [end]    rebuildCache consume time = 7.525573
09-09 16:05:43.777  6834  6834 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-09 16:05:43.777  6834  6834 D Mms/MethodReflector: getSubId is called
09-09 16:05:43.777  6834  6834 D Mms/MethodReflector: getDefaultSmsSubId is called
09-09 16:05:43.777  6834  6834 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-09 16:05:43.777  6834  6834 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-09 16:05:43.777  6834  6834 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: auto download during roaming secondary -> false
09-09 16:05:43.777  6834  6834 D Mms/DownloadManager: mAutoDownload ------> true
,09-09 16:05:43.817  6834  6834 D ComposerPerformance: 1473429943826 ms / [DONE] Composer constructor
09-09 16:05:43.817  6834  6834 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-09 16:05:43.817  6834  6834 I Mms/ReservationManager: ReservationManager()
09-09 16:05:43.817  6834  6834 I Mms/ReservationManager: resetAfterConnected()
09-09 16:05:43.817  1456  1480 D TP/MmsSmsProvider: query,matched:7, calling pid = 6834
09-09 16:05:43.827  1456  1480 D TP/MmsSmsProvider: match 7:Elapsed time : 1.788 ms
09-09 16:05:43.827  6834  6834 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-09 16:05:43.827  6834  6834 D Mms/MmsApp: [end]    onCreate() consume time = 61.300104
09-09 16:05:43.827  6834  6834 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
09-09 16:05:43.837  6834  6958 D Mms/Conversation: [start]    init() consume time = 3.335573
--------- beginning of system
09-09 16:05:43.837  1015  1479 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-09 16:05:43.837  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-09 16:05:43.837  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:43.837  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:43.837  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-09 16:05:43.837  6834  6834 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-09 16:05:43.837  6834  6834 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-09 16:05:43.847  1456  2212 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-09 16:05:43.847  1456  2212 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-09 16:05:43.847  1456  2212 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-09 16:05:43.847  1456  2212 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-09 16:05:43.847  1456  2212 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-09 16:05:43.857  6834  6834 D Mms/MethodReflector: getSubId is called
09-09 16:05:43.857  1456  2212 D TP/MmsSmsProvider: need read changed broadcast:false
09-09 16:05:43.857  6834  6834 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-09 16:05:43.867  6834  6958 D Mms/Conversation: [end]    init consume time = 29.606354
09-09 16:05:43.867  6834  6958 D Mms/MessagingNotification: [start]    init() consume time = 2.683802
09-09 16:05:43.867  6834  6834 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:05:43.867  6834  6834 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-09 16:05:43.867  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:05:43.867  6834  6834 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:43.867  6834  6834 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-09 16:05:43.867  6834  6834 D Mms/DownloadManager: mAutoDownload ------> true
09-09 16:05:43.877  6834  6961 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-09 16:05:43.877  6834  6961 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
09-09 16:05:43.877  6834  6958 D Mms/MessagingNotification: [end]    init consume time = 8.841719
09-09 16:05:43.887  1456  1469 D TP/MmsSmsProvider: query,matched:0, calling pid = 6834
09-09 16:05:43.887  1456  1469 V TP/MmsSmsProvider: getSimpleConversations entered.
09-09 16:05:43.887  1456  1469 D TP/MmsSmsProvider: match 0:Elapsed time : 2.164 ms
09-09 16:05:43.897  6834  6962 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 18.489063
09-09 16:05:43.897  1015  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-09 16:05:43.897  6834  6963 D Mms/Synchronizer: [start]    doSync consume time = 2.390208
09-09 16:05:43.897  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.897  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.897  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.897  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.897  1456  2212 D TP/MmsSmsProvider: update, matched:300, calling pid = 6834
09-09 16:05:43.897  1456  2212 V TP/MmsSmsProvider: syncDBData start
09-09 16:05:43.907  1456  2212 V TP/MmsSmsProvider: syncDBData sms end
09-09 16:05:43.907  1456  2212 V TP/MmsSmsProvider: syncDBData mms end
09-09 16:05:43.907  1456  2212 V TP/MmsSmsProvider: syncDBData end
09-09 16:05:43.917  6964  6964 E Zygote  : MountEmulatedStorage()
09-09 16:05:43.917  6964  6964 E Zygote  : v2
09-09 16:05:43.917  6964  6964 I libpersona: KNOX_SDCARD checking this for 10068
09-09 16:05:43.917  6964  6964 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:43.917  6964  6964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:43.917  1015  1028 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6964 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-09 16:05:43.927  6834  6963 D Mms/Synchronizer: [end]    doSync consume time = 28.191406
09-09 16:05:43.927  1456  1480 D TP/MmsSmsProvider: query,matched:400, calling pid = 6834
09-09 16:05:43.927  6834  6962 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 3.355938
09-09 16:05:43.927  6964  6964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:43.937  6964  6964 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-09 16:05:43.947  6964  6964 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:43.947  6964  6964 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:43.957  1015  1498 I ActivityManager: Killing 6549:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-09 16:05:43.957  1015  5718 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gsf
09-09 16:05:43.957  6834  6937 D Mms/ArtClassLoader: init [DONE] art
09-09 16:05:43.967  1015  5718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.967  1015  5718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.967  1015  5718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.967  1015  5718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:43.987  6981  6981 E Zygote  : MountEmulatedStorage()
09-09 16:05:43.987  1015  5718 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6981 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-09 16:05:43.987  6981  6981 E Zygote  : v2
09-09 16:05:43.987  6981  6981 I libpersona: KNOX_SDCARD checking this for 10011
09-09 16:05:43.987  6981  6981 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:43.987  6981  6981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:43.997  6981  6981 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:43.997  6981  6981 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 16:05:44.017  6981  6981 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.017  6981  6981 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:44.067  6959  6959 D AndroidRuntime: 
09-09 16:05:44.067  6959  6959 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 16:05:44.067  6959  6959 D AndroidRuntime: CheckJNI is OFF
09-09 16:05:44.067  6959  6959 D AndroidRuntime: readGMSProperty: start
09-09 16:05:44.067  6959  6959 D AndroidRuntime: readGMSProperty: already setted!!
09-09 16:05:44.067  6959  6959 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 16:05:44.067  6959  6959 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 16:05:44.067  6959  6959 D AndroidRuntime: readGMSProperty: end
09-09 16:05:44.067  6959  6959 D AndroidRuntime: addProductProperty: start
09-09 16:05:44.137  1015  1472 I art     : Explicit concurrent mark sweep GC freed 177491(9MB) AllocSpace objects, 2(2MB) LOS objects, 33% free, 24MB/37MB, paused 2.547ms total 174.767ms
09-09 16:05:44.167  6964  6964 D BadgeProvider: onCreate
09-09 16:05:44.167  6964  6964 D BadgeProvider: DatabaseHelper
09-09 16:05:44.187  6834  6958 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-09 16:05:44.187  1456  1480 D TP/SmsProvider: query,matched:26, calling pid = 6834
09-09 16:05:44.197  6981  6981 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-09 16:05:44.197  1456  1480 D TP/SmsProvider: match 26:Elapsed time : 2.056 ms
09-09 16:05:44.197  1456  1469 D TP/MmsSmsProvider: query,matched:6, calling pid = 6834
09-09 16:05:44.207  1456  1469 D TP/MmsSmsProvider: match 6:Elapsed time : 1.160 ms
09-09 16:05:44.207  6959  6959 E AffinityControl: AffinityControl: registerfunction enter
09-09 16:05:44.217  1015  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-09 16:05:44.217  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.217  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.217  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.217  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.227  6959  6959 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 16:05:44.237  1015  1481 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7003 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-09 16:05:44.237  7003  7003 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.237  7003  7003 E Zygote  : v2
09-09 16:05:44.237  7003  7003 I libpersona: KNOX_SDCARD checking this for 10023
09-09 16:05:44.237  7003  7003 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.237  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.247  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:44.247  1015  1330 E PersonaManagerService: inState():  stateMachine is null !!
09-09 16:05:44.247  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:44.247  1015  1330 I PersonaManagerService: PersonaId don't exist
09-09 16:05:44.247  1015  1330 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 16:05:44.257  1015  1330 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:05:44.267  6981  6981 I GoogleHttpClient: GMS http client unavailable, use old client
09-09 16:05:44.267  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.277  7003  7003 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:44.277  1015  1330 W ActivityManager: mDVFSHelper.acquire()
09-09 16:05:44.287   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-09 16:05:44.287   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-09 16:05:44.297  1015  1330 D FocusedStackFrame: Set to : 0
09-09 16:05:44.307  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 16:05:44.307  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 16:05:44.317  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.317  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.317  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.317  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.317  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 16:05:44.317  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 16:05:44.327   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-09 16:05:44.327  7023  7023 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.327  7023  7023 E Zygote  : v2
09-09 16:05:44.327  7023  7023 I libpersona: KNOX_SDCARD checking this for 10171
09-09 16:05:44.327  7023  7023 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.327  7023  7023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.327  7023  7023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:44.327  1015  1330 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7023 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 16:05:44.327  1015  1330 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 16:05:44.327  1015  1330 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:05:44.327  1015  1330 D InputDispatcher: Focused application set to: xxxx
09-09 16:05:44.327  1015  1330 D InputDispatcher: Focus left window: 1483
09-09 16:05:44.337  6959  6959 D AndroidRuntime: Shutting down VM
09-09 16:05:44.337  1015  1027 I ActivityManager: Killing 6582:com.sec.pcw.device/1000 (adj 15): empty #21
09-09 16:05:44.337  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:05:44.337  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 16:05:44.337  7023  7023 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 16:05:44.357  7023  7023 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.357  7023  7023 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:44.377  1015  1027 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 16:05:44.377  1015  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-09 16:05:44.377  1015  1015 V ActivityManager: Display changed displayId=0
09-09 16:05:44.377  6981  6981 I GoogleHttpClient: GMS http client unavailable, use old client
09-09 16:05:44.387  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 16:05:44.387  1015  1045 W DisplayManagerService: Failed to notify process 6582 that displays changed, assuming it died.
09-09 16:05:44.387  1015  1045 W DisplayManagerService: android.os.TransactionTooLargeException
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:05:44.387  1015  1045 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 16:05:44.397  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
09-09 16:05:44.417  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 16:05:44.427  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:05:44.427  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-09 16:05:44.427  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.427  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.437  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-09 16:05:44.447  7003  7003 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-09 16:05:44.457  1015  1134 I ActivityManager: Killing 6599:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
09-09 16:05:44.457  6834  6958 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-09 16:05:44.467   257  1100 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-09 16:05:44.467   257  1865 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-09 16:05:44.477  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:05:44.477  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
09-09 16:05:44.477  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.477  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.477  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-09 16:05:44.487  1015  1479 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-09 16:05:44.497  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{226efe9f token=android.os.BinderProxy@220db64 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 16:05:44.497  1483  1483 D Launcher: onTrimMemory. Level: 20
09-09 16:05:44.497  1441  1441 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
09-09 16:05:44.507  1015  1462 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=20, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
09-09 16:05:44.507  1015  1462 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
09-09 16:05:44.507  6295  6295 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
09-09 16:05:44.507  6295  6295 I AASAservice-TokenRule: parseToken()
09-09 16:05:44.517  6295  6295 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-09 16:05:44.517  6295  6295 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 16:05:44.517  6295  6295 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:05:44.517  6295  6295 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-09 16:05:44.517  6295  6295 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-09 16:05:44.517  6295  6295 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:05:44.517  6295  6295 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 16:05:44.517  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:05:44.517  6295  6295 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 16:05:44.517  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 16:05:44.517  6295  6295 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 16:05:44.517  6295  6295 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-09 16:05:44.517  6295  6295 W System.err: 	at libcore.io.Posix.open(Native Method)
09-09 16:05:44.517  6295  6295 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:05:44.517  6295  6295 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 16:05:44.517  6295  6295 W System.err: 	... 14 more
09-09 16:05:44.517  6295  6295 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-09 16:05:44.517  6295  6295 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
09-09 16:05:44.527  6295  6295 I art     : System.exit called, status: 0
09-09 16:05:44.527  6295  6295 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 16:05:44.537  6834  6834 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-09 16:05:44.537  1015  1481 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-09 16:05:44.537  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-09 16:05:44.537  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-09 16:05:44.537  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-09 16:05:44.537  6959  6959 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 16:05:44.537  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-09 16:05:44.547  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-09 16:05:44.547  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-09 16:05:44.547  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:44.547  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:44.547  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-09 16:05:44.547  2828  2828 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
,09-09 16:05:44.547  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-09 16:05:44.557  1015  4362 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-09 16:05:44.557  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-09 16:05:44.557  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.557  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.557  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.557  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.567  6834  7043 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-09 16:05:44.567  6834  7043 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-09 16:05:44.567  7003  7003 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-09 16:05:44.577  7044  7044 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.577  7044  7044 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:44.577  7044  7044 E Zygote  : v2
09-09 16:05:44.577  7044  7044 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.577  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.577  1015  4362 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:05:44.577  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:44.577  1015  1134 I ActivityManager: Process com.samsung.aasaservice (pid 6295)(adj 0) has died(187,638)
09-09 16:05:44.577  1015  1134 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-09 16:05:44.587  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:05:44.587  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,09-09 16:05:44.587  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 16:05:44.587  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.597   290   290 E SMD     : DCD OFF
09-09 16:05:44.587  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.587  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.607  7055  7055 E Zygote  : MountEmulatedStorage(),
09-09 16:05:44.607  7055  7055 E Zygote  : v2,
09-09 16:05:44.607  7055  7055 I libpersona: KNOX_SDCARD checking this for 10014
09-09 16:05:44.607  7055  7055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.607  7055  7055 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.607  1015  1040 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7055 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-09 16:05:44.607  1015  4362 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-09 16:05:44.607  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.607  7055  7055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:44.607  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.607  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.607  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.607  7055  7055 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 16:05:44.617  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.617  7044  7044 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:44.627  7070  7070 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.627  7070  7070 I libpersona: KNOX_SDCARD checking this for 10042
09-09 16:05:44.627  7070  7070 E Zygote  : v2
09-09 16:05:44.627  7070  7070 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:44.627  7070  7070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:44.627  7070  7070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 16:05:44.637  7070  7070 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
09-09 16:05:44.637  1015  4362 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7070 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,09-09 16:05:44.637  7055  7055 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:44.637  7055  7055 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:44.647  1015  1330 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 16:05:44.647  7023  7023 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-09 16:05:44.647  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.647  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.647  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.647  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.657  7044  7044 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-09 16:05:44.657  7087  7087 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.657  7087  7087 E Zygote  : v2
09-09 16:05:44.657  7087  7087 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:44.657  7087  7087 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:44.657  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:44.667  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:44.667  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:05:44.667  7070  7070 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.667  7044  7044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:182 android.app.ActivityThread.handleReceiver:3125 
09-09 16:05:44.667  7070  7070 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:44.677  1015  1330 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 16:05:44.677  1015  1330 I ActivityManager: Killing 6616:com.sec.knox.bridge/1000 (adj 15): empty #21
,09-09 16:05:44.677  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
09-09 16:05:44.677  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.677  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.677  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:44.677  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,09-09 16:05:44.697  6730  6730 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-09 16:05:44.697  6730  6730 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-09 16:05:44.697  6730  6730 I TapandpayWidget:Utils: Clear T&P info.
,09-09 16:05:44.697  6730  6730 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-09 16:05:44.697  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.697  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 16:05:44.697  7087  7087 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:44.697  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.697  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.697  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.697  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.697  7070  7070 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:44.707  7070  7070 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:05:44.707  7070  7070 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:44.717  7105  7105 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.717  7105  7105 E Zygote  : v2
09-09 16:05:44.717  7105  7105 I libpersona: KNOX_SDCARD checking this for 10009
09-09 16:05:44.717  7105  7105 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:44.727  7105  7105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:44.727  7105  7105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:44.727  7105  7105 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 16:05:44.737  1015  1472 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7105 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 16:05:44.747  7070  7070 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-09 16:05:44.747  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-09 16:05:44.747  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.747  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:44.757  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.757  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-09 16:05:44.767  7105  7105 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:44.767  7105  7105 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:44.777   286   286 E installd: system dir 0 : /system/app/
09-09 16:05:44.777   286   286 E installd: system dir 1 : /system/priv-app/
09-09 16:05:44.777   286   286 E installd: system dir 2 : /vendor/app/
09-09 16:05:44.777   286   286 E installd: system dir 3 : /oem/app/
,09-09 16:05:44.777  1015  1250 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-09 16:05:44.777  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
09-09 16:05:44.777  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.777  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.777  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-09 16:05:44.777  1015  1462 I ActivityManager: Killing 6631:com.sec.android.app.themechooser/u0a145 (adj 15): empty #21
,09-09 16:05:44.787  1015  1462 I TactileAssist: enable value -1
09-09 16:05:44.787  1015  1462 I TactileAssist: internal enable value -1
09-09 16:05:44.787  1015  1462 I TactileAssist: intensity value -1
09-09 16:05:44.787  1015  1462 I TactileAssist: saveAppList value true
,09-09 16:05:44.787  1015  1462 I TactileAssist: List of disabled apps :
,09-09 16:05:44.797  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 16:05:44.797  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.797  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.797  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.797  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.797  7087  7087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:05:44.807  7124  7124 E Zygote  : MountEmulatedStorage()
,09-09 16:05:44.807  7124  7124 E Zygote  : v2
09-09 16:05:44.807  7124  7124 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:44.807  7124  7124 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.817  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.817  1015  1028 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:05:44.817  1015  5718 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 16:05:44.817  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-09 16:05:44.817  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.817  1015  5718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:44.817  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:05:44.827  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:44.827  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:44.827  7023  7023 I cr.library_loader: Time to load native libraries: 31 ms (timestamps 9164-9195)
09-09 16:05:44.827  7023  7023 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:05:44.837   307   307 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 24.986ms
,09-09 16:05:44.847  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:44.857  7124  7124 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:44.857  1015  1028 I ActivityManager: Killing 6646:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-09 16:05:44.867  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-09 16:05:44.867   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.285ms total 21.781ms
,09-09 16:05:44.867  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.867  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.867  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:44.867  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:44.877  7023  7023 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6670663}
,09-09 16:05:44.877  7023  7023 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:05:44.887   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.638ms
,09-09 16:05:44.887  7023  7023 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:05:44.887  1015  1055 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-09 16:05:44.897  7144  7144 E Zygote  : MountEmulatedStorage()
09-09 16:05:44.897  7144  7144 I libpersona: KNOX_SDCARD checking this for 10048
09-09 16:05:44.897  7144  7144 E Zygote  : v2
09-09 16:05:44.897  7144  7144 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:44.897  7144  7144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:44.897  1015  1028 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7144 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-09 16:05:44.897  7144  7144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:44.907  7144  7144 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
09-09 16:05:44.907  1015  1028 I ActivityManager: Killing 6712:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-09 16:05:44.907  6818  6818 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-09 16:05:44.907  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:05:44.917  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{296d7699 u0 com.test.thalitest/.MainActivity t2}
09-09 16:05:44.917  1015  1028 I ActivityManager: Killing 6749:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #21
,09-09 16:05:44.917  1015  1472 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-09 16:05:44.917  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.917  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-09 16:05:44.917  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:44.917  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-09 16:05:44.927  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:44.927  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.927  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.927  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.927  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:05:44.927  4787  6770 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:05:44.937  4787  6766 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
09-09 16:05:44.937  4787  6770 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:05:44.937  1015  1250 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:44.937  7144  7144 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:44.937  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.937  6849  6849 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-09 16:05:44.937  6849  6849 D PackageIntentReceiver: Not GearManger package! 
,09-09 16:05:44.947  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.947  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.947  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:44.947  7144  7144 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:44.947  7023  7023 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 16:05:44.947  6818  6818 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-09 16:05:44.947  7023  7023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:05:44.957  1015  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:44.957  7023  7023 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 16:05:44.957  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.957  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:44.967  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.967  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:44.967  7124  7124 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 16:05:44.967  7124  7124 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 16:05:44.967  7124  7124 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 16:05:44.967  6818  7156 E FilterInstaller: installFilters
,09-09 16:05:44.967  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:44.967  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.977  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.977  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.977  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:44.977  6818  7156 E FilterInstaller: There is no requred permission
,09-09 16:05:44.977  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:44.977  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:44.987  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:44.987  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:44.987  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:44.987  4787  4787 D AsyncTaskServiceImpl: Submit a task: nzm
,09-09 16:05:44.987  1015  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:44.987  4787  6770 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:05:44.987  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:44.987  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:44.987  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:44.987  4787  6770 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:05:44.997  6912  7161 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,09-09 16:05:44.997  7124  7124 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:05:44.997  7124  7124 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:05:44.997  7124  7124 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 16:05:44.997  7124  7124 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,09-09 16:05:45.007  1015  5718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:45.007  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.007  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.007  6912  7161 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-09 16:05:45.007  1015  5718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:45.007  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.007  1015  1330 I ActivityManager: Killing 5950:com.android.vending/u0a26 (adj 15): empty #21
,09-09 16:05:45.007  7144  7144 D Compatibility: onReceive() it will make start service
,09-09 16:05:45.017  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 16:05:45.017  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.017  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.017  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:45.017  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-09 16:05:45.017  6912  6912 D AcmsService: onStartCommand
09-09 16:05:45.017  6912  6912 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-09 16:05:45.017  6912  6912 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 2
09-09 16:05:45.017  6912  6912 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-09 16:05:45.017  6912  6912 D AcmsService: Incremented Counter Value : onStartCommand
09-09 16:05:45.017  6912  6912 D AcmsService: Inside handle Intent
09-09 16:05:45.017  6912  6912 D AcmsService: App added - package name: com.test.thalitest
09-09 16:05:45.017  6912  6912 D AcmsCore: Post to AcmsCoreHandler
09-09 16:05:45.017  6912  6912 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:05:45.017  6912  6912 D AcmsServiceMonitor: Incrementing - Counter value: 4
09-09 16:05:45.017  6912  6912 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-09 16:05:45.017  6912  6912 D AcmsService: Decremented Counter Value : handleStartIntent
09-09 16:05:45.017  6912  6912 D AcmsServiceMonitor: Decrementing - Counter value: 3
,09-09 16:05:45.027  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:45.027  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.027  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.027  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.027  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.027  4787  5228 D nzm     : Processing package: com.test.thalitest
,09-09 16:05:45.027  1015  6615 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-09 16:05:45.027  1015  6615 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-09 16:05:45.027  1015  6615 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.027  1015  6615 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:45.027  1015  6615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-09 16:05:45.037  1015  1250 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:05:45.037  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.037  4787  5228 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-09 16:05:45.037  4787  5228 D nzm     : Found info for package com.test.thalitest in db.
,09-09 16:05:45.037  7023  7023 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 16:05:45.037  7023  7023 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 16:05:45.037  7023  7023 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 16:05:45.037  7023  7023 I Adreno-EGL: Local Branch: 
09-09 16:05:45.037  7023  7023 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 16:05:45.037  7023  7023 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 16:05:45.037  7023  7023 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 16:05:45.047  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.047  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.047  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-09 16:05:45.047  1015  1330 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-09 16:05:45.047  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.047  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.047  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.047  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.057  7170  7170 E Zygote  : MountEmulatedStorage()
09-09 16:05:45.057  7170  7170 I libpersona: KNOX_SDCARD checking this for 10029
09-09 16:05:45.057  7170  7170 E Zygote  : v2
09-09 16:05:45.057  7170  7170 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:45.057  1015  1330 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7170 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-09 16:05:45.067  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:45.067  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.067  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.067  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.067  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:05:45.067  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:45.067  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:45.067  7144  7169 D Compatibility: onHandleIntent()
09-09 16:05:45.067  1015  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 16:05:45.067  1015  1498 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.067  1015  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.067  1015  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.077  7144  7169 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-09 16:05:45.087  1015  1330 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-09 16:05:45.087  7144  7169 D Compatibility: found: 2
,09-09 16:05:45.087  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.087  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.087  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.087  1015  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.087  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.087  7170  7170 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.097  7144  7169 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:05:45.097  7144  7169 D Compatibility: skipping ResolveInfo{2ea958e1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:05:45.097  7144  7169 D Compatibility: considering ResolveInfo{16359606 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,09-09 16:05:45.097  7144  7169 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:05:45.097  7144  7169 D Compatibility: enabling receiver ResolveInfo{172ae4c7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:05:45.107  7144  7169 D Compatibility: enabling receiver ResolveInfo{27e23af4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,09-09 16:05:45.107  7186  7186 E Zygote  : MountEmulatedStorage()
,09-09 16:05:45.107  7186  7186 E Zygote  : v2
09-09 16:05:45.107  7144  7169 D Compatibility: enabling receiver ResolveInfo{3601a21d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-09 16:05:45.107  7186  7186 I libpersona: KNOX_SDCARD checking this for 10052,
,09-09 16:05:45.107  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 16:05:45.107  7186  7186 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:45.107  1015  1330 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7186 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-09 16:05:45.117  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 16:05:45.117  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:05:45.117  7144  7169 D Compatibility: enabling receiver ResolveInfo{3d850c92 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:05:45.127  1015  1498 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:45.127  1015  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.127  1015  1498 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.127  1015  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.127  1015  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.127  7144  7169 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 16:05:45.137  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:05:45.137  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.137  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.137  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.137  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 16:05:45.147  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.147  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.147  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.147  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.157  1015  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:45.157  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.157  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.157  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.157  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.157  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.157  7186  7186 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.167  1015  1330 I ActivityManager: Killing 6777:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-09 16:05:45.177  6912  6938 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-09 16:05:45.177  1015  6615 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-09 16:05:45.177  7023  7023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 16:05:45.187  1015  1330 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:45.187  7023  7023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 16:05:45.187  7023  7023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 16:05:45.197  1015  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.197  1015  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.197  1015  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:05:45.197  7023  7023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 16:05:45.197  7023  7023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 16:05:45.197  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,09-09 16:05:45.207  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.207  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.207  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.207  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.207  7170  7213 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-09 16:05:45.227  7216  7216 E Zygote  : MountEmulatedStorage()
,09-09 16:05:45.227  7216  7216 E Zygote  : v2
09-09 16:05:45.227  7216  7216 I libpersona: KNOX_SDCARD checking this for 10026
09-09 16:05:45.227  7216  7216 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:45.227  7216  7216 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:45.227  1015  1472 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7216 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 16:05:45.227  7216  7216 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:45.237  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:45.237  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.237  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.237  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.237  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.237  7216  7216 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:05:45.247  2828  2828 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,09-09 16:05:45.247  1015  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 16:05:45.257  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.257  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.257  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.257  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.257  7170  7213 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 16:05:45.257  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:45.257  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.257  7170  7213 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 16:05:45.257  7170  7213 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:05:45.267  7216  7216 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.267  7216  7216 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.277  6912  6938 I AcmsKeyStoreHelper: Key Store exist
,09-09 16:05:45.277  6912  6938 I AcmsKeyStoreHelper: Hence loading the keystore file
09-09 16:05:45.277  1015  1481 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7230 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 16:05:45.277  7230  7230 E Zygote  : MountEmulatedStorage()
09-09 16:05:45.277  7230  7230 I libpersona: KNOX_SDCARD checking this for 10032
09-09 16:05:45.277  7230  7230 E Zygote  : v2
09-09 16:05:45.277  7230  7230 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.287  7170  7213 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 16:05:45.287  1015  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:45.287  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.287  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.287  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.307  7230  7230 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:45.307  7170  7213 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:45.307  7230  7230 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:45.307  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:45.307  7230  7230 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 16:05:45.307  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:05:45.317  6981  6989 E SQLiteLog: (283) recovered 252 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,09-09 16:05:45.317  7170  7213 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 16:05:45.317  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.317  7170  7213 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:05:45.327  1015  6615 I ActivityManager: Killing 6865:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #21
,09-09 16:05:45.337  7230  7230 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.337  7230  7230 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.347  1015  1250 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-09 16:05:45.347  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.347  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.347  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.347  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:05:45.357  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:05:45.357  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.367  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.367  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:45.367  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:05:45.367  7170  7213 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:45.377  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:45.387  7023  7023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:05:45.387  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.387  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:45.387  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.397  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.397  7170  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:05:45.397  7170  7213 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:45.407  7023  7023 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 16:05:45.417  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:45.417  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.417  7170  7213 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 16:05:45.417  7170  7213 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:45.417  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.417  7170  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:05:45.417  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.417  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.417  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:45.417  4787  7215 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-09 16:05:45.427  7023  7023 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 16:05:45.427  7023  7023 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 16:05:45.427  7170  7213 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 16:05:45.427  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.427  7170  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:05:45.427  7170  7213 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:45.427  7023  7023 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 16:05:45.437  6912  6938 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-09 16:05:45.437  6912  6938 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-09 16:05:45.437  6912  6938 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-09 16:05:45.437  6912  6938 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:05:45.437  6912  6938 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-09 16:05:45.437  6912  6938 D AcmsCertificateMngr: handleAppRemoved() Enter com.test.thalitest
,09-09 16:05:45.437  1015  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 16:05:45.437  6912  6938 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.provider: com.samsung.android.mirrorlink.acms.provider.AcmsDbProvider
,09-09 16:05:45.447  7023  7023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 16:05:45.447  7023  7023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:05:45.457  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:45.457  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.457  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:45.457  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:45.457  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:05:45.457  7170  7213 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 16:05:45.457  7170  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:45.457  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.457  7170  7213 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:45.467  6912  6938 D AcmsAppEntryInterface: App not found in DB Hence ignore
,09-09 16:05:45.467  6912  6938 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>5
09-09 16:05:45.467  6912  6938 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-09 16:05:45.477  6912  6938 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-09 16:05:45.477  6912  6938 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-09 16:05:45.477  6912  6938 D AcmsCore: This is NOT a valid MirrorLink app
,09-09 16:05:45.477  6912  6938 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-09 16:05:45.477  6912  6938 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:05:45.477  6912  6938 D AcmsServiceMonitor: Decrementing - Counter value: 0
,09-09 16:05:45.477  6912  6938 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-09 16:05:45.477  7230  7254 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 16:05:45.477  7230  7254 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 16:05:45.477  1015  1463 I ActivityManager: Killing 6896:com.android.keychain/1000 (adj 15): empty #21
,09-09 16:05:45.487  7170  7213 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-09 16:05:45.487  6912  6912 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-09 16:05:45.487  6912  6912 D AcmsService: Enter onDestroy
09-09 16:05:45.487  6912  6912 I AcmsService: cleanUp(): inside service clean up
09-09 16:05:45.487  6912  6912 D AcmsCore: AcmsCore: inside DeInit
09-09 16:05:45.487  6912  6912 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-09 16:05:45.487  6912  6912 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-09 16:05:45.487  6912  6912 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-09 16:05:45.487  6912  6912 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
,09-09 16:05:45.487  6912  6912 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-09 16:05:45.487  7230  7254 D SPPClientService: PushLog.txt file is not deleted.
09-09 16:05:45.487  7230  7254 D SPPClientService: PushLog.txt file is not deleted.
09-09 16:05:45.487  7230  7254 D SPPClientService: ============PushLog. stop!
,09-09 16:05:45.497  1015  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-09 16:05:45.507  6912  6912 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-09 16:05:45.507  6912  6912 D AcmsService: killing acms process
09-09 16:05:45.507  6912  6912 I Process : Sending signal. PID: 6912 SIG: 9
,09-09 16:05:45.507  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.507  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.507  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.507  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.507  7170  7213 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 16:05:45.507  7170  7213 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-09 16:05:45.507  7170  7213 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:45.517  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.517  7170  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:05:45.517  7259  7259 E Zygote  : MountEmulatedStorage()
09-09 16:05:45.517  7259  7259 E Zygote  : v2
09-09 16:05:45.517  7259  7259 I libpersona: KNOX_SDCARD checking this for 10039
09-09 16:05:45.517  7259  7259 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:45.517  7259  7259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:45.527  7259  7259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:45.527  7259  7259 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:05:45.527  1015  1479 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7259 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-09 16:05:45.527  1015  1027 I ActivityManager: Process ACMS.Process (pid 6912)(adj 0) has died(163,660)
,09-09 16:05:45.537  7170  7213 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-09 16:05:45.537  7170  7213 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:05:45.547  7170  7213 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-09 16:05:45.567  7259  7259 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.567  7259  7259 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.577  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.577  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.577  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:45.577  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:05:45.587  7259  7259 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:45.597  7280  7280 E Zygote  : MountEmulatedStorage()
09-09 16:05:45.597  7280  7280 E Zygote  : v2
09-09 16:05:45.597  7280  7280 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:45.597  7280  7280 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:45.597  7280  7280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:45.597  7280  7280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 16:05:45.597  7280  7280 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:45.597  1015  1040 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7280 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 16:05:45.627  7023  7287 D OpenGLRenderer: Render dirty regions requested: true
,09-09 16:05:45.637  7280  7280 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:45.637  7280  7280 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:45.637  1015  1472 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 16:05:45.637  1015  1472 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 16:05:45.637  1015  1472 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 16:05:45.647  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 16:05:45.647  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 16:05:45.657  7023  7023 V ActivityThread: updateVisibility : ActivityRecord{116e3bf2 token=android.os.BinderProxy@3d9e4354 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 16:05:45.657  7023  7200 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-09 16:05:45.667  7023  7023 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 16:05:45.667  7023  7023 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 16:05:45.687  7280  7280 D AASAservice: onCreate()
,09-09 16:05:45.687  7280  7280 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,09-09 16:05:45.827  7216  7216 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
,09-09 16:05:45.827  1015  1028 I art     : Explicit concurrent mark sweep GC freed 25217(1459KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.627ms total 152.850ms
,09-09 16:05:45.827  1015  1479 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-09 16:05:45.827  2828  2828 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
09-09 16:05:45.827  6834  6834 I Mms/MmsApp:  start initViewCache mms
09-09 16:05:45.827  6834  6834 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1903.415363
09-09 16:05:45.827  6834  6834 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-09 16:05:45.827  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.837  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.837  1015  1463 D LocationManagerService: getProviders()=[passive]
09-09 16:05:45.837  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:45.837  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 16:05:45.837   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-09 16:05:45.847  7216  7216 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 16:05:45.847  7216  7216 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 16:05:45.857  1015  1250 D InputDispatcher: Focus entered window: 7023
,09-09 16:05:45.857  7023  7023 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 16:05:45.857  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 16:05:45.867  7023  7287 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 16:05:45.867  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 16:05:45.867  7259  7259 D NearbySource: Nearby Source Create!
,09-09 16:05:45.867  7259  7259 D NearbyContext: Nearby Context Create!
,09-09 16:05:45.877  7023  7287 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 16:05:45.877  7023  7287 D OpenGLRenderer: Enabling debug mode 0
,09-09 16:05:45.917  1015  5718 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 16:05:45.917  1015  4362 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-09 16:05:45.917  1015  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-09 16:05:45.917  1015  4362 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:45.917  1015  4362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:45.917  1015  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:05:45.927  1173  1173 I StatusBar: Icon Only
,09-09 16:05:45.927  1173  1173 D PanelView: There is/are notification(s) 
,09-09 16:05:45.927   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 16:05:45.927   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:05:45.937  7259  7259 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 16:05:45.937  7259  7259 D SLinkSource: Samsung link source created
,09-09 16:05:45.937  1015  7325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 16:05:45.947  1015  1045 I ActivityManager: Displayed Component not be shown by security: +1s543ms (total +1s635ms)
,09-09 16:05:45.947  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-09 16:05:45.947  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{296d7699 u0 com.test.thalitest/.MainActivity t2} time:90317
,09-09 16:05:45.957   257   456 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-09 16:05:45.957   257  1865 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-09 16:05:45.967  7023  7023 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 16:05:45.967  7023  7023 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d9e4354 time:90335
,09-09 16:05:45.977  7216  7216 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,09-09 16:05:45.987  7186  7251 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-09 16:05:45.987  1895  1895 I SamsungIME: getCurrentCandidateView
,09-09 16:05:46.007  7259  7329 D ContactProvider: getAllContactInfoList Start
,09-09 16:05:46.007  1015  1462 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 16:05:46.047  1015  1330 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 16:05:46.047  1015  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.047  1015  1330 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.047  1015  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.047  1015  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-09 16:05:46.047  6834  6834 D AbsListView: Get MotionRecognitionManager
,09-09 16:05:46.047  1015  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 16:05:46.047  7259  7259 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-09 16:05:46.057  1015  4362 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 16:05:46.057  1015  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.057  1015  4362 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.057  1015  4362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.057  1015  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:05:46.067  1015  1462 D MotionRecognitionService:  ssp status : false
,09-09 16:05:46.067  7259  7329 D ContactProvider: getAllContactInfoList End
09-09 16:05:46.067  1015  1481 I splitIntent: Queue : background intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart  false.
,09-09 16:05:46.077  7259  7329 I syncContacts: thread: 1358, sync time = 88
,09-09 16:05:46.077  6834  6834 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 250.557188
,09-09 16:05:46.087  7216  7216 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
,09-09 16:05:46.087  7216  7216 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-09 16:05:46.087  7216  7216 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
09-09 16:05:46.087  7023  7023 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7023
09-09 16:05:46.087  7124  7124 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:05:46.087  7124  7124 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:05:46.087  7124  7124 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 16:05:46.087  7124  7124 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REPLACED
09-09 16:05:46.087  7124  7124 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_PACKAGE_REPLACED_START
09-09 16:05:46.087  1015  6615 I splitIntent: Split this intent : android.intent.action.PACKAGE_REPLACED, mSplitNum[0]=5, mSplitNum[1]=9, mSplitNum[2]=13, mBgSplitQueueNum=3 divideNum= 4 r.nextReceiver= 1 receivers.size=17
09-09 16:05:46.087  1015  6615 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REPLACED !! Enqueue -> schedule it!!
,09-09 16:05:46.097  7144  7144 D Compatibility: onReceive() it will make start service
,09-09 16:05:46.097  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 16:05:46.097  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:46.097  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:46.097  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:46.097  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:46.117  7334  7334 E Zygote  : MountEmulatedStorage()
09-09 16:05:46.117  7334  7334 E Zygote  : v2
09-09 16:05:46.117  7334  7334 I libpersona: KNOX_SDCARD checking this for 10110
09-09 16:05:46.117  7334  7334 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
09-09 16:05:46.127  7216  7333 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
09-09 16:05:46.127  1015  1040 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7334 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 16:05:46.127  7334  7334 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:46.127  1015  1462 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-09 16:05:46.127  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-09 16:05:46.127  7334  7334 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:46.127  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.127  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:46.127  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
09-09 16:05:46.137  7334  7334 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:05:46.147  7144  7345 D Compatibility: onHandleIntent()
,09-09 16:05:46.147  7144  7345 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
09-09 16:05:46.147  1015  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:46.147  1015  1498 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.147  1015  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.147  1015  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.157  7144  7345 D Compatibility: found: 2
,09-09 16:05:46.157  7144  7345 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:05:46.167  7144  7345 D Compatibility: skipping ResolveInfo{3e9b4319 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:05:46.167  7144  7345 D Compatibility: considering ResolveInfo{34e35fde com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 16:05:46.167  7144  7345 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:05:46.167  1015  5718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:46.167  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.177  7144  7345 D Compatibility: enabling receiver ResolveInfo{fb9a5bf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:05:46.177  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:46.177  1015  5718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:46.177  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.177  4787  6770 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-09 16:05:46.197  7334  7334 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:46.197  7334  7334 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:46.197  7144  7345 D Compatibility: enabling receiver ResolveInfo{3345f48c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:05:46.197  1015  1250 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:46.197  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.207  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.207  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.207  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.217  6834  6834 D Mms/BubbleViewCache: fillCache bubble = 1
,09-09 16:05:46.227  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:46.227  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.227  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:46.237  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.237  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.237  1015  5718 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:46.237  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.237  1015  5718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.237  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.247  7144  7345 D Compatibility: enabling receiver ResolveInfo{1593f7d5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:05:46.247  1895  1895 D SamsungIME: Dismiss ExpandCandiate
,09-09 16:05:46.257  7216  7216 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
09-09 16:05:46.257  4787  4787 D AsyncTaskServiceImpl: Submit a task: nzm
,09-09 16:05:46.257  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:46.267  1993  1993 D WearableService: callingUid 10011, callindPid: 1993
,09-09 16:05:46.267  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:46.267  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:46.267  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.267  1015  1481 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-09 16:05:46.267  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.267  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:46.277  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.277  7144  7345 D Compatibility: enabling receiver ResolveInfo{9419bea com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-09 16:05:46.277  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:05:46.277  4787  5097 D nzm     : Processing package: com.test.thalitest
,09-09 16:05:46.277  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:46.277  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.277  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.277  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.277  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.277  7144  7345 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 16:05:46.287  4787  6770 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-09 16:05:46.297  7023  7023 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 16:05:46.297  4787  5097 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-09 16:05:46.297  4787  5097 D nzm     : Found info for package com.test.thalitest in db.
,09-09 16:05:46.307  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:05:46.307  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.307  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.307  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.307  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.317  7087  7087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:05:46.317  1015  1481 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 16:05:46.317  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.317  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.317  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:46.317  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:05:46.327  1015  5718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:46.327  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.327  7216  7216 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-09 16:05:46.327  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.327  1015  5718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.327  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.337  7216  7216 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,09-09 16:05:46.337  1015  6615 I ActivityManager: Killing 6964:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-09 16:05:46.347  1993  1993 E NetworkScheduler.SR: Invalid parameter app
,09-09 16:05:46.347  1993  1993 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-09 16:05:46.347  1015  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:46.347  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.347  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.347  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.367  1015  1028 I ActivityManager: Killing 7003:com.wsomacp/u0a23 (adj 15): empty #21
,09-09 16:05:46.377  1015  5718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:46.377  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.377  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:46.377  1015  5718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.377  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.377  1015  1481 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 16:05:46.377  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.377  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.377  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:05:46.377  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 16:05:46.397  7216  7216 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-09 16:05:46.397  7216  7216 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-09 16:05:46.397  7216  7216 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-09 16:05:46.427  1015  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:46.427  1015  1330 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:46.427  1015  1330 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:46.427  1015  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:46.427  1015  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:46.457  7186  7251 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 466 ms] updated apps [took 465 ms] 
,09-09 16:05:46.457  1015  1472 I ActivityManager: Killing 6693:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-09 16:05:46.487  4787  5097 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-09 16:05:46.527  1015  5718 I ActivityManager: Killing 6834:com.android.mms/u0a41 (adj 15): empty #21
,09-09 16:05:46.527  1895  1895 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 16:05:46.587  1895  1895 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 16:05:46.597  1015  1498 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:05:46.617  1015  1027 D CountryDetector: No listener is left
,09-09 16:05:46.627  1895  1895 I SamsungIME: KeybaordView init() : load resources
,09-09 16:05:46.637  4787  5097 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-09 16:05:46.677  1895  1895 I SamsungIME: getCurrentKeyboard
,09-09 16:05:46.677  1895  1895 I SamsungIME: getTextKeyboard
,09-09 16:05:46.707  7023  7326 D jxcore_app_log: JniHelper::setJavaVM(0xb711d2b0), pthread_self() = -1217750720
,09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 16:05:46.717  7023  7326 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5373731 added. We now have 1 listener(s)
,09-09 16:05:46.727  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-09 16:05:46.727  7023  7326 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 16:05:46.727  7023  7326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:05:46.727  7023  7326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 16:05:46.737  7023  7326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16832984 added. We now have 1 listener(s)
,09-09 16:05:46.737  7023  7326 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:05:46.737  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:05:46.737  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 16:05:46.737  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 16:05:46.737  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 16:05:46.737  7023  7326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 16:05:46.747  7023  7326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:05:46.747  1895  1895 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 16:05:46.747  7023  7326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-09 16:05:46.757  7023  7326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:05:46.757  7023  7326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:05:46.757  7023  7326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 16:05:46.757  7023  7326 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:05:46.757  7023  7326 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 16:05:46.757  7023  7023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:05:46.757  7023  7023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:05:46.787  7023  7023 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 16:05:46.807  7334  7334 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 16:05:46.807  7334  7334 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:05:46.807  7334  7334 I GAv4    :   adb logcat -s GAv4
,09-09 16:05:46.817   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 16:05:46.817   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:05:46.827  7334  7370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 16:05:46.837   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 16:05:46.837   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:05:46.847  7334  7334 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:05:46.847  1015  1463 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:05:46.847  7334  7370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 16:05:46.877   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 16:05:46.877   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:05:46.877  7334  7372 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 16:05:46.877  7334  7334 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:05:46.887   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 16:05:46.887   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:05:46.897  7334  7372 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 16:05:46.897  7334  7373 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:05:47.137  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:05:47.147  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:47.147  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:47.147  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 16:05:47.157  7334  7334 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 16:05:47.167  7334  7334 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 1535-1538)
09-09 16:05:47.167  7334  7334 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:05:47.177  7334  7334 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4211f20}
,09-09 16:05:47.177  7334  7334 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 16:05:47.177  7334  7334 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:05:47.197  7334  7334 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 16:05:47.197  7334  7334 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:05:47.207  7334  7334 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:05:47.217  7334  7334 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 16:05:47.217  7334  7334 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 16:05:47.217  7334  7334 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 16:05:47.217  7334  7334 I Adreno-EGL: Local Branch: 
09-09 16:05:47.217  7334  7334 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 16:05:47.217  7334  7334 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 16:05:47.217  7334  7334 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 16:05:47.297  7334  7403 W cr.media: Requires BLUETOOTH permission
,09-09 16:05:47.327  7334  7334 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 16:05:47.337  7334  7334 I NSApplication: Starting up...
,09-09 16:05:47.337  1015  6615 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:05:47.347  1015  4362 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:05:47.347  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 16:05:47.347  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:47.347  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:47.347  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:47.347  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:47.367  7408  7408 E Zygote  : MountEmulatedStorage(),
09-09 16:05:47.367  7408  7408 I libpersona: KNOX_SDCARD checking this for 10121
09-09 16:05:47.367  7408  7408 E Zygote  : v2
09-09 16:05:47.367  7408  7408 I libpersona: KNOX_SDCARD not a persona,
09-09 16:05:47.367  7408  7408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 16:05:47.367  7408  7408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 16:05:47.367  1015  1472 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7408 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 16:05:47.367  7408  7408 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:47.367  1015  1472 I ActivityManager: Killing 7044:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-09 16:05:47.387  7408  7408 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:47.397  7408  7408 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:47.407  7408  7408 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:47.407  7408  7408 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:05:47.407  7408  7408 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 16:05:47.407  4787  5097 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-09 16:05:47.417  4787  5097 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-09 16:05:47.427  7408  7408 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,09-09 16:05:47.427  6730  6730 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-09 16:05:47.427  6730  6730 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REPLACED / mCurIndex :-10
09-09 16:05:47.427  6730  6730 I TapandpayWidget:Utils: Clear T&P info.
,09-09 16:05:47.427  6730  6730 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-09 16:05:47.427  1015  1462 I ActivityManager: Killing 7070:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-09 16:05:47.447  2475  2475 D daemonapp: [MSC_Daemon]>>> AWDCDS:28 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,09-09 16:05:47.447  1015  4362 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REPLACED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 16:05:47.447  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:47.447  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:05:47.447  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:47.457  4787  5097 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,09-09 16:05:47.567  4787  5097 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,09-09 16:05:47.577  1015  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:47.577  1015  1498 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:47.577  1015  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:47.577  1015  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:47.597   290   290 E SMD     : DCD OFF
,09-09 16:05:47.787  7023  7369 W jxcore-log: Initializing JXcore engine
09-09 16:05:47.787  7023  7369 W jxcore-log: JXcore engine is ready
,09-09 16:05:47.857  2017  2017 E audit   : type=1400 msg=audit(1473429947.857:205): avc:  denied  { ioctl } for  pid=7369 comm="Thread-1321" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 16:05:47.857  2017  2017 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:47.857  2017  2017 E audit   : type=1300 msg=audit(1473429947.857:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9db088f8 items=0 ppid=307 ppcomm=main pid=7369 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1321" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 16:05:47.857  2017  2017 E audit   : type=1320 msg=audit(1473429947.857:205): 
,09-09 16:05:47.877  7023  7369 W jxcore-log: Starting JXcore engine
,09-09 16:05:47.977  7023  7369 W jxcore-log: Platform android
09-09 16:05:47.977  7023  7369 W jxcore-log: 
09-09 16:05:47.977  7023  7369 W jxcore-log: Process ARCH arm
09-09 16:05:47.977  7023  7369 W jxcore-log: 
,09-09 16:05:48.237  7023  7369 I jxcore-log: JXcore Cordova bridge is ready!
09-09 16:05:48.237  7023  7369 I jxcore-log: 
,09-09 16:05:48.237  7023  7369 W jxcore-log: JXcore engine is started
,09-09 16:05:48.237  7023  7326 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 16:05:48.237  7023  7023 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 16:05:48.247  7023  7369 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-09 16:05:48.247  7023  7369 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-09 16:05:48.257  7023  7023 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,09-09 16:05:48.257  7023  7023 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-09 16:05:48.277  1015  1481 D FocusedStackFrame: Set to : 0
09-09 16:05:48.277  1015  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:05:48.277  1015  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 16:05:48.277  1015  1481 D InputDispatcher: Focused application set to: xxxx
09-09 16:05:48.277  1015  1481 D InputDispatcher: Focus left window: 7023
,09-09 16:05:48.287  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:05:48.287  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 16:05:48.287  1015  1481 I ActivityManager: Killing 7055:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-09 16:05:48.287  7023  7023 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 16:05:48.297  7023  7326 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
,09-09 16:05:48.297  7023  7023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,09-09 16:05:48.297  7023  7023 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:05:48.297  7023  7023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:05:48.297  7023  7023 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:05:48.297  7023  7023 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:05:48.297  7023  7023 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5373731 removed from the list
09-09 16:05:48.297  7023  7023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:05:48.297  7023  7023 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16832984 removed from the list
09-09 16:05:48.297  7023  7023 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:05:48.297  7023  7023 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-09 16:05:48.297  7023  7023 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 16:05:48.307   257  1865 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-09 16:05:48.307   257   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-09 16:05:48.317  1015  1330 W ActivityManager: mDVFSHelper.acquire()
,09-09 16:05:48.327  1015  1330 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-09 16:05:48.347  1483  1483 D Launcher: onRestart, Launcher: 887316446
,09-09 16:05:48.347  1483  1483 D Launcher: onStart, Launcher: 887316446
09-09 16:05:48.347  1483  1483 D Launcher.HomeView: onStart
,09-09 16:05:48.347  1483  1483 D Launcher: onResume, Launcher: 887316446
,09-09 16:05:48.357  1015  1479 D SettingsProvider: name = kids_home_mode
09-09 16:05:48.357  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:05:48.357  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 16:05:48.357  1015  1479 D SettingsProvider: selectionArgs: false
09-09 16:05:48.357  1015  1479 D SettingsProvider: selectionArgs: 10006
09-09 16:05:48.357  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:05:48.357  1015  1479 D SettingsProvider: ret = -1
,09-09 16:05:48.357  1483  1483 D Launcher.HomeView: onResume
,09-09 16:05:48.367  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 16:05:48.367  1483  1483 D MenuAppsGridFragment: onResume
,09-09 16:05:48.367  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:48.367  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.367  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,09-09 16:05:48.377  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-09 16:05:48.377  1015  1028 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,09-09 16:05:48.377  1015  1028 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,09-09 16:05:48.377  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-09 16:05:48.377  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:48.377  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:05:48.377  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,09-09 16:05:48.387  7259  7259 D GalleryCacheReady: Receive : home resume
,09-09 16:05:48.387  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:05:48.387  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:05:48.387  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-09 16:05:48.397  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.397  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.397  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
09-09 16:05:48.397  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,09-09 16:05:48.397  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 16:05:48.397  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.397  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.397  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:48.407  7427  7427 E Zygote  : MountEmulatedStorage()
09-09 16:05:48.407  7427  7427 E Zygote  : v2
09-09 16:05:48.407  7427  7427 I libpersona: KNOX_SDCARD checking this for 10089
09-09 16:05:48.407  7427  7427 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:48.407  7427  7427 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 16:05:48.417  1015  1040 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7427 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
09-09 16:05:48.417  7427  7427 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:48.417  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.417  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
09-09 16:05:48.417  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.417  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
09-09 16:05:48.417  7427  7427 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-09 16:05:48.417  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.417  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.417  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.417  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:48.427  7439  7439 E Zygote  : MountEmulatedStorage()
09-09 16:05:48.437  7439  7439 E Zygote  : v2
09-09 16:05:48.437  7439  7439 I libpersona: KNOX_SDCARD checking this for 10139
09-09 16:05:48.437  7439  7439 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:48.437  7439  7439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 16:05:48.437  7439  7439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:48.437  7439  7439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:48.437  1015  1040 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7439 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 16:05:48.447  7427  7427 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 16:05:48.447  7427  7427 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:48.447  1015  1134 D ActivityManager: handle home activity for 0
09-09 16:05:48.447  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 16:05:48.447  1015  1134 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-09 16:05:48.447  1015  1134 D KnoxTimeoutHandler: post home show event for user 0
09-09 16:05:48.447  1015  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 16:05:48.447  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-09 16:05:48.447  1015  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 16:05:48.447  1015  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 16:05:48.447  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-09 16:05:48.447  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 16:05:48.447  1483  1483 D Launcher.HomeView: onPause
09-09 16:05:48.447  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 16:05:48.457  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-09 16:05:48.457  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-09 16:05:48.457  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.457  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,09-09 16:05:48.457  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.457  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.457  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.457  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:48.467   307   307 I art     : Explicit concurrent mark sweep GC freed 8681(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 709us total 27.595ms
,09-09 16:05:48.467  7439  7439 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:48.467  7439  7439 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:48.477   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 562us total 16.940ms,
,09-09 16:05:48.497   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.124ms
,09-09 16:05:48.507  7457  7457 E Zygote  : MountEmulatedStorage()
09-09 16:05:48.507  7457  7457 I libpersona: KNOX_SDCARD checking this for 10041
09-09 16:05:48.507  7457  7457 E Zygote  : v2
09-09 16:05:48.507  7457  7457 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:48.507  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:48.507  1015  1028 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7457 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-09 16:05:48.507  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:48.517  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 16:05:48.527   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-09 16:05:48.537  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 16:05:48.537  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 16:05:48.537  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:48.537  7457  7457 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:48.547  1015  1134 D InputDispatcher: Focus entered window: 1483,
09-09 16:05:48.547  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 16:05:48.547  1483  1483 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-09 16:05:48.547  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 16:05:48.547  7427  7427 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:48.547  7427  7427 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-09 16:05:48.547  7424  7424 D AndroidRuntime: 
09-09 16:05:48.547  7424  7424 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 16:05:48.547  1015  3407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 16:05:48.557  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.557  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.557  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
09-09 16:05:48.557  1015  1027 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1483, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,09-09 16:05:48.557  7424  7424 D AndroidRuntime: CheckJNI is OFF
09-09 16:05:48.557  7424  7424 D AndroidRuntime: readGMSProperty: start
09-09 16:05:48.557  7424  7424 D AndroidRuntime: readGMSProperty: already setted!!
09-09 16:05:48.557  7424  7424 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 16:05:48.557  7424  7424 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 16:05:48.557  7424  7424 D AndroidRuntime: readGMSProperty: end
09-09 16:05:48.557  7424  7424 D AndroidRuntime: addProductProperty: start
,09-09 16:05:48.557  1483  1483 D Launcher.HomeView: onStop
09-09 16:05:48.557  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{226efe9f token=android.os.BinderProxy@220db64 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-09 16:05:48.557  1015  1462 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 16:05:48.557  1015  7473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 16:05:48.567  7023  7023 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 16:05:48.567  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.567  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.567  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,09-09 16:05:48.567  1895  1895 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 16:05:48.567  2573  2573 D Recents_RecreateReceiver: onReceive by home
,09-09 16:05:48.577  1173  1173 I StatusBar: Icon Only
09-09 16:05:48.577  1173  1173 D PanelView: There is/are notification(s) 
,09-09 16:05:48.577  7439  7439 V TaskCloserActivity: TaskCloserActivity enter()
,09-09 16:05:48.587  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.587  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.587  1015  1463 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
09-09 16:05:48.587  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,09-09 16:05:48.597  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.597  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.597  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.597  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:48.597  1483  1483 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@220db64 time:92962
,09-09 16:05:48.597  7439  7439 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,09-09 16:05:48.607  7481  7481 E Zygote  : MountEmulatedStorage(),
09-09 16:05:48.607  7481  7481 E Zygote  : v2
09-09 16:05:48.607  7481  7481 I libpersona: KNOX_SDCARD checking this for 10084
09-09 16:05:48.607  7481  7481 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:48.607  7481  7481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:48.617  7481  7481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 16:05:48.617  1015  1463 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7481 uid=10084 gids={50084, 9997} abi=armeabi-v7a
09-09 16:05:48.617  7481  7481 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 16:05:48.617  7457  7457 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
09-09 16:05:48.617  7457  7457 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:48.617  7457  7457 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:48.617  7457  7457 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 16:05:48.617  7457  7457 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:05:48.627  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.627  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.627  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,09-09 16:05:48.627  1015  1462 I ActivityManager: Killing 6656:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-09 16:05:48.627  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34b804c3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:92997
09-09 16:05:48.627  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-09 16:05:48.637  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:48.637  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
09-09 16:05:48.637  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:48.637  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,09-09 16:05:48.637  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.637  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.637  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:48.637  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:48.647  7481  7481 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:48.647  7481  7481 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:48.657  7498  7498 E Zygote  : MountEmulatedStorage()
09-09 16:05:48.657  7498  7498 E Zygote  : v2
09-09 16:05:48.657  1015  1462 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7498 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
09-09 16:05:48.657  7498  7498 I libpersona: KNOX_SDCARD checking this for 10135
09-09 16:05:48.657  7498  7498 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:48.657  1015  1462 I ActivityManager: Killing 6818:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
09-09 16:05:48.657  7498  7498 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:48.667  7498  7498 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:48.667  7457  7457 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-09 16:05:48.667  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-09 16:05:48.667  7498  7498 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:05:48.687  7481  7481 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:05:48.687  7498  7498 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:48.687  7498  7498 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:48.697  1015  1330 D PersonaManager: isKioskContainerExistOnDevice,
,09-09 16:05:48.707  1015  1134 I ActivityManager: Killing 6849:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-09 16:05:48.717  7424  7424 E AffinityControl: AffinityControl: registerfunction enter
,09-09 16:05:48.727  7498  7498 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-09 16:05:48.727  7498  7498 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:48.727  7498  7498 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 16:05:48.727  7498  7498 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
09-09 16:05:48.727  7498  7498 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:05:48.747  7424  7424 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 16:05:48.757  1015  1463 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-09 16:05:48.757  1015  1463 D PackageManager: START PACKAGE DELETE: observer{968911808}
09-09 16:05:48.757  1015  1463 D PackageManager: pkg{<packageName>}
09-09 16:05:48.757  1015  1463 D PackageManager: user{0}
09-09 16:05:48.757  1015  1463 D PackageManager: caller{2000}
09-09 16:05:48.757  1015  1463 D PackageManager: flags{2}
09-09 16:05:48.757  1015  1463 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 16:05:48.757  1015  1463 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 16:05:48.757  1015  1463 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 16:05:48.757  1015  1463 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-09 16:05:48.757  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 16:05:48.757  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 16:05:48.757  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 16:05:48.757  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 16:05:48.757  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 16:05:48.767  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-09 16:05:48.767  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-09 16:05:48.767  1015  1040 I ActivityManager: Killing 7023:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,09-09 16:05:48.817  7457  7457 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 102.169ms
,09-09 16:05:48.847  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 16:05:48.857  1015  1055 W PackageSettings: Skipping PackageSetting{2c3375f3 com.example.hello/10168} due to missing metadata
,09-09 16:05:48.877  7457  7516 D Mms/ArtClassLoader: init before art
09-09 16:05:48.877  7457  7457 D Mms/TelephonyPermission: start operation mode monitor
,09-09 16:05:48.877  1015  1047 I PowerManagerService: [PWL] Off : 30s ago
,09-09 16:05:48.887  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 16:05:48.887  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-09 16:05:48.887  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService' (uid=10011, pid=4787, ws=null) (elapsedTime=43486)
09-09 16:05:48.887  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=9)
,09-09 16:05:48.887  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-09 16:05:48.887  7457  7457 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 16:05:48.907  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 16:05:48.937  2706  2706 I art     : Explicit concurrent mark sweep GC freed 2499(121KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.051ms total 25.430ms
,09-09 16:05:48.947  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 16:05:48.967  1895  1895 E SamsungIME: mOCRHelper is null
,09-09 16:05:48.967  1993  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 16:05:48.977  4787  4787 I art     : Explicit concurrent mark sweep GC freed 39110(2MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 12MB/20MB, paused 1.260ms total 84.611ms
,09-09 16:05:48.977  1015  1015 D RCPManagerService: PackageReceiver onReceive()
09-09 16:05:48.977  1015  3379 D SSRM:n  : SIOP:: AP = 450
09-09 16:05:48.977  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 16:05:48.987  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 16:05:48.987  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 16:05:48.987  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-09 16:05:48.987  7457  7457 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-09 16:05:48.987  7457  7457 D Mms/TelephonyPermission: isDefault true
,09-09 16:05:48.987  7457  7457 D Mms/MmsApp: onCreate() com.android.mms
,09-09 16:05:48.997  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-09 16:05:49.017  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 16:05:49.027  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 16:05:49.037  7457  7457 D Mms/MmsApp: [start]    initCountryIso consume time = 371.900365
,09-09 16:05:49.047  1015  1134 D CountryDetector: The first listener is added
,09-09 16:05:49.047  1441  1441 D RegisteredServicesCache: empty dynamic service
,09-09 16:05:49.057  7457  7457 D Mms/MmsApp: [end]    initCountryIso consume time = 12.228385
,09-09 16:05:49.057  7457  7457 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.654271
,09-09 16:05:49.067  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
,09-09 16:05:49.067  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-09 16:05:49.067  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 16:05:49.067  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 16:05:49.077  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 16:05:49.077  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-09 16:05:49.087  7457  7457 D Mms/MmsConfig: before partial update
,09-09 16:05:49.097  1015  1121 V NetworkStats: performPollLocked() took 28ms
,09-09 16:05:49.107  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 16:05:49.107  1015  1028 D SecContentProvider2: mCursor = null
,09-09 16:05:49.117  7457  7457 D Mms/MmsConfig: Load Resize quality : 80
,09-09 16:05:49.117  7457  7457 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-09 16:05:49.117  7457  7457 D EasySignUpManager_1.0.1: isAuth is false
,09-09 16:05:49.117  7457  7457 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-09 16:05:49.137  1456  1480 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7457
,09-09 16:05:49.137  1456  1480 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.581 ms
,09-09 16:05:49.157  7457  7457 D EasySignUpManager_1.0.1: isAuth is false
09-09 16:05:49.157  7457  7457 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-09 16:05:49.157  7457  7457 E CscParser: mps_code.dat does not exist
09-09 16:05:49.157  7457  7457 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:05:49.157  7457  7457 E CscParser: fileName + /system/csc/customer.xml
,09-09 16:05:49.157  1015  1122 D NtpTrustedTime: forceRefresh() from cache miss
,09-09 16:05:49.157   280  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 16:05:49.157   280  1010 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,09-09 16:05:49.157  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-09 16:05:49.157  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-09 16:05:49.157  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-09 16:05:49.167  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 16:05:49.167  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicy: uID is 10171
,09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
,09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 16:05:49.167  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 16:05:49.167  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 16:05:49.177  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-09 16:05:49.177  7457  7457 E CscParser: mps_code.dat does not exist
09-09 16:05:49.177  7457  7457 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:05:49.177  7457  7457 E CscParser: fileName + /system/csc/customer.xml
,09-09 16:05:49.177  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 16:05:49.177  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-09 16:05:49.177  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-09 16:05:49.177  1015  3379 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-09 16:05:49.177  7457  7457 D CscParser: getInstance fileName =/system/csc/customer.xml,
09-09 16:05:49.177  7457  7457 D Mms/MmsConfig:  enable multiwindow = false
,09-09 16:05:49.197  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-09 16:05:49.197  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-09 16:05:49.197  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 16:05:49.197  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 16:05:49.207  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-09 16:05:49.207  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-09 16:05:49.207  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 16:05:49.207  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 16:05:49.207  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 16:05:49.207  7457  7457 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-09 16:05:49.207  7457  7457 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-09 16:05:49.207  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.217  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.217  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.217  1015  1122 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1473429949226 mCachedNtpElapsedRealtime : 93589 mCachedNtpCertainty : 6
09-09 16:05:49.217  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 16:05:49.217  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 16:05:49.247  7457  7457 D Mms/MmsConfig: [end]    init() consume time = 189.919323
,09-09 16:05:49.247  7457  7457 D Mms/Contact: [start]    init() consume time = 5.330208
,09-09 16:05:49.287  1456  2212 D TP/MmsSmsProvider: query,matched:13, calling pid = 7457
,09-09 16:05:49.287  1456  2212 D TP/MmsSmsProvider: match 13:Elapsed time : 1.558 ms
,09-09 16:05:49.307  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 16:05:49.317  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.317  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.317  1015  1055 I art     : Explicit concurrent mark sweep GC freed 49200(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 25MB/37MB, paused 3.040ms total 326.088ms
,09-09 16:05:49.327  1015  1025 I art     : WaitForGcToComplete blocked for 186.115ms for cause HeapTrim
,09-09 16:05:49.327  7457  7457 D Mms/Contact: [end]    init consume time = 76.484479
,09-09 16:05:49.337  7457  7524 D Mms/DraftCache: [start]    rebuildCache consume time = 7.749688
,09-09 16:05:49.337  7457  7516 D Mms/ArtClassLoader: init [DONE] art
,09-09 16:05:49.337  1456  1480 D TP/MmsSmsProvider: query,matched:12, calling pid = 7457
,09-09 16:05:49.337  1456  1480 D TP/MmsSmsProvider: match 12:Elapsed time : 1.092 ms
,09-09 16:05:49.337  7457  7457 D Mms/MethodReflector: getSubId is called
09-09 16:05:49.337  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-09 16:05:49.337  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
,09-09 16:05:49.337  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-09 16:05:49.337  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:05:49.337  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:49.337  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-09 16:05:49.347  7457  7457 D Mms/MethodReflector: getSubId is called
,09-09 16:05:49.347  7457  7457 D Mms/MethodReflector: getDefaultSmsSubId is called
09-09 16:05:49.347  7457  7457 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-09 16:05:49.347  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-09 16:05:49.347  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: auto download during roaming secondary -> false
09-09 16:05:49.347  7457  7457 D Mms/DownloadManager: mAutoDownload ------> true
,09-09 16:05:49.347  1015  1055 D PackageManager: delete codoeFile: 
,09-09 16:05:49.357  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-09 16:05:49.357  7457  7524 D Mms/DraftCache: [end]    rebuildCache consume time = 27.678177
09-09 16:05:49.357  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest,
09-09 16:05:49.357  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:05:49.367  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.357  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:05:49.357  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,09-09 16:05:49.377  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-09 16:05:49.377  1015  1055 D PackageManager: result of delete: 1{968911808}
,09-09 16:05:49.377  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.387  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.387  7457  7457 D ComposerPerformance: 1473429949397 ms / [DONE] Composer constructor
,09-09 16:05:49.387  7457  7457 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-09 16:05:49.387  7457  7457 I Mms/ReservationManager: ReservationManager()
,09-09 16:05:49.387  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:05:49.387  7457  7457 I Mms/ReservationManager: resetAfterConnected()
09-09 16:05:49.387  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 16:05:49.387  7424  7424 D AndroidRuntime: Shutting down VM
,09-09 16:05:49.387  7457  7525 D Mms/Conversation: [start]    init() consume time = 31.213489
09-09 16:05:49.387  1456  2212 D TP/MmsSmsProvider: query,matched:7, calling pid = 7457
,09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.397  1456  2212 D TP/MmsSmsProvider: match 7:Elapsed time : 1.791 ms
,09-09 16:05:49.397  1456  1857 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-09 16:05:49.397  1456  1857 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-09 16:05:49.397  1456  1857 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-09 16:05:49.397  1456  1857 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 16:05:49.397  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:05:49.407  7457  7457 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-09 16:05:49.407  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 16:05:49.407  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 16:05:49.407  1456  1857 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-09 16:05:49.407  1456  1857 D TP/MmsSmsProvider: need read changed broadcast:false
,09-09 16:05:49.407  7457  7457 D Mms/MmsApp: [end]    onCreate() consume time = 13.807448
,09-09 16:05:49.407  7457  7525 D Mms/Conversation: [end]    init consume time = 0.733959
09-09 16:05:49.407  7457  7457 D Mms/UIEventReceiver: ui event
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-09 16:05:49.407  1015  1027 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-09 16:05:49.407  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.407  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.407  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,09-09 16:05:49.407  7457  7457 D Mms/MethodReflector: getSubId is called
09-09 16:05:49.407  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-09 16:05:49.407  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-09 16:05:49.407  7457  7457 D Mms/DownloadManager: mAutoDownload ------> true
,09-09 16:05:49.417  7439  7439 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,09-09 16:05:49.417  1015  1462 I ActivityManager: Killing 6880:com.samsung.helphub/1000 (adj 15): empty #21
,09-09 16:05:49.417  7457  7525 D Mms/MessagingNotification: [start]    init() consume time = 11.361406
,09-09 16:05:49.417  7457  7525 D Mms/MessagingNotification: [end]    init consume time = 3.707135
,09-09 16:05:49.427  1015  1391 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 16:05:49.427  1015  1391 D AlarmManagerService: Setting time of day to sec=1473429949
,09-09 16:05:49.427  1015  1391 D AlarmManagerService: Trying to open a file
,09-09 16:05:49.427  1015  1391 D AlarmManagerService: File Open Success
09-09 16:05:49.427  1015  1391 D AlarmManagerService: File Close Success
09-09 16:05:49.427  1015  1391 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,09-09 16:05:49.429  1015  1093 V AlarmManager: waitForAlarm result :65536
09-09 16:05:49.429  1015  1391 W AlarmManagerService: Unable to set rtc to 1473429949: Invalid argument
09-09 16:05:49.429  2946  2946 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 16:05:49 GMT+02:00 2016
,09-09 16:05:49.429  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 16:05:49.429  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.429  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.429  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.429  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 16:05:49.429  1015  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 16:05:49.429  1015  1040 W ActivityManager: Failed to update preferences for: com.samsung.helphub
09-09 16:05:49.429  1015  1093 V AlarmManager: No more alarm at this time.nowELAPSED=93804 batch.start=104368
,09-09 16:05:49.429  2946  2946 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 16:05:49.429  1015  1015 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473429949440
,09-09 16:05:49.429  7457  7528 D Mms/Synchronizer: [start]    doSync consume time = 0.236458
,09-09 16:05:49.438  7457  7527 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 20.295417
,09-09 16:05:49.438  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
09-09 16:05:49.438  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
09-09 16:05:49.438  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 16:05:49.438  1015  1015 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,09-09 16:05:49.438  1015  1015 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,09-09 16:05:49.438  2946  2946 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 16:05:49.448  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 16:05:49.448  2946  2946 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 16:05:49.448  2946  2946 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 16:05:49.448  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 16:05:49.448  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 16:05:49.458  1015  1015 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 16:05:49.458  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 16:05:49.458  1015  1250 D SettingsProvider: name = lockscreen_zoom_panning_effect
09-09 16:05:49.458  1015  1250 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:05:49.458  1015  1250 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 16:05:49.458  1015  1250 D SettingsProvider: selectionArgs: false
09-09 16:05:49.458  1015  1250 D SettingsProvider: selectionArgs: 10049
09-09 16:05:49.458  1015  1250 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:05:49.458  1015  1250 D SettingsProvider: ret = -1
,09-09 16:05:49.458  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 16:05:49.458  1173  1173 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
09-09 16:05:49.458  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 16:05:49.458  1015  1463 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-09 16:05:49.458  1015  1463 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 16:05:49.468  1015  1463 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 16:05:49.468  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 16:05:49.468  1015  1015 I DrmEventService:  no response from SecureClock 
,09-09 16:05:49.468  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.468  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.468  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.468  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 16:05:49.468  1173  1173 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-09 16:05:49.468  1173  1173 I GeometricMosaic_Keyguard: update
,09-09 16:05:49.478  1173  1173 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,09-09 16:05:49.478  7530  7530 E Zygote  : MountEmulatedStorage()
09-09 16:05:49.478  7530  7530 E Zygote  : v2
09-09 16:05:49.478  7530  7530 I libpersona: KNOX_SDCARD checking this for 10090
09-09 16:05:49.478  7530  7530 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.488  7530  7530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:49.488  7530  7530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:49.488  7530  7530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 16:05:49.488  1015  1463 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7530 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-09 16:05:49.498  1015  1498 I TactileAssist: enable value -1
,09-09 16:05:49.498  1015  1498 I TactileAssist: internal enable value -1
09-09 16:05:49.498  1015  1498 I TactileAssist: intensity value -1
09-09 16:05:49.498  1015  1498 I TactileAssist: saveAppList value true
,09-09 16:05:49.508  1015  1498 I TactileAssist: List of disabled apps :
,09-09 16:05:49.508  7087  7087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
09-09 16:05:49.508  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-09 16:05:49.508  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.508  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.508  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.508  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.518  7530  7530 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:49.518  7530  7530 D ActivityThread: Added TimaKeyStore provider,
,09-09 16:05:49.528  7545  7545 E Zygote  : MountEmulatedStorage()
09-09 16:05:49.528  7545  7545 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:49.528  7545  7545 E Zygote  : v2
09-09 16:05:49.528  7545  7545 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.528  7545  7545 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:49.528  7545  7545 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 16:05:49.528  7545  7545 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:49.528  1015  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7545 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:05:49.528  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 16:05:49.538  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 16:05:49.538  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.538  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-09 16:05:49.538  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.538  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:05:49.538  1456  1469 D TP/MmsSmsProvider: update, matched:300, calling pid = 7457
09-09 16:05:49.538  1456  1469 V TP/MmsSmsProvider: syncDBData start
09-09 16:05:49.548  1456  1469 V TP/MmsSmsProvider: syncDBData sms end
,09-09 16:05:49.548  1456  1469 V TP/MmsSmsProvider: syncDBData mms end
09-09 16:05:49.548  1456  1469 V TP/MmsSmsProvider: syncDBData end
,09-09 16:05:49.558  1015  4362 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 16:05:49.558  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.558  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.558  1173  1173 I KeyguardEffectViewUtil: set current wallpaper info
09-09 16:05:49.558  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.558  1015  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.558  1015  1330 D SettingsProvider: name = keyguard_current_wallpaper_type
09-09 16:05:49.558  1015  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:05:49.558  1015  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 16:05:49.558  1015  1330 D SettingsProvider: selectionArgs: false
09-09 16:05:49.558  1015  1330 D SettingsProvider: selectionArgs: 10049
09-09 16:05:49.558  1015  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:05:49.558  1015  1330 D SettingsProvider: ret = -1
,09-09 16:05:49.558  2946  7529 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 16:05:49.558  1015  5718 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-09 16:05:49.558  1015  5718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:05:49.558  1015  5718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 16:05:49.558  1015  5718 D SettingsProvider: selectionArgs: false
09-09 16:05:49.558  1015  5718 D SettingsProvider: selectionArgs: 10049
09-09 16:05:49.558  1015  5718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:05:49.558  1015  5718 D SettingsProvider: ret = -1
09-09 16:05:49.558  1015  6615 D SettingsProvider: name = keyguard_current_wallpaper_res_id
09-09 16:05:49.558  1015  6615 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:05:49.558  1015  6615 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 16:05:49.558  1015  6615 D SettingsProvider: selectionArgs: false
09-09 16:05:49.558  1015  6615 D SettingsProvider: selectionArgs: 10049,
09-09 16:05:49.558  1015  6615 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:05:49.558  1015  6615 D SettingsProvider: ret = -1
,09-09 16:05:49.568  2946  7529 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 16:05:49.568  7545  7545 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.568  7545  7545 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:49.578  7561  7561 E Zygote  : MountEmulatedStorage()
,09-09 16:05:49.578  7561  7561 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:05:49.578  7561  7561 E Zygote  : v2
09-09 16:05:49.578  7561  7561 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:49.578  7561  7561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:49.578  7530  7530 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-09 16:05:49.578  1015  4362 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:05:49.578  7561  7561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:49.578  7530  7530 D elm:15121: ELMEngine.ELMEngine( context ).
09-09 16:05:49.578  7561  7561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:49.578  7530  7530 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-09 16:05:49.588  7144  7144 D Compatibility: onReceive() it will make start service
09-09 16:05:49.588  7424  7424 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 16:05:49.588  1015  1330 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 16:05:49.588  1015  1330 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.588  1015  1330 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.588  1015  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.588  1015  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-09 16:05:49.598  2946  2946 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-09 16:05:49.598  7530  7530 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 16:05:49.598  7530  7530 D elm:15121: ElmAgentService : onCreate()
,09-09 16:05:49.598  7530  7570 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 16:05:49.598  1015  5718 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-09 16:05:49.598  7457  7528 D Mms/Synchronizer: [end]    doSync consume time = 167.298854
09-09 16:05:49.598  1015  5718 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-09 16:05:49.598  7530  7570 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-09 16:05:49.598  7530  7570 D elm:15121: MDMBridge.getInstance()
09-09 16:05:49.598  7530  7570 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 16:05:49.608  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 16:05:49.608  1015  1055 D PackageManager: userId{-1}
09-09 16:05:49.608  1015  1055 D PackageManager: andCode{true}
09-09 16:05:49.608  1015  5718 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.608  1015  5718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.608  1015  5718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-09 16:05:49.608  1456  1857 D TP/MmsSmsProvider: query,matched:400, calling pid = 7457
,09-09 16:05:49.618  7561  7561 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.618  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.618  7144  7576 D Compatibility: onHandleIntent()
09-09 16:05:49.618  7561  7561 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:49.618  7144  7576 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-09 16:05:49.618  7530  7570 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 16:05:49.618  7124  7124 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:05:49.618  7124  7124 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:05:49.618  7124  7124 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 16:05:49.618  7124  7124 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
09-09 16:05:49.618  7144  7576 D Compatibility: found: 2
09-09 16:05:49.618  7144  7576 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-09 16:05:49.618  7144  7576 D Compatibility: skipping ResolveInfo{2293c51 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:05:49.618  7144  7576 D Compatibility: considering ResolveInfo{33958cb6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 16:05:49.618  7144  7576 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:05:49.628  7144  7576 D Compatibility: enabling receiver ResolveInfo{12508db7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:05:49.628  1456  2212 D TP/MmsSmsProvider: query,matched:0, calling pid = 7457
,09-09 16:05:49.628  1456  2212 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-09 16:05:49.638  1456  2212 D TP/MmsSmsProvider: match 0:Elapsed time : 2.255 ms
,09-09 16:05:49.638  1173  1598 D TEST    : run!!!
09-09 16:05:49.638  1173  1173 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-09 16:05:49.638  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:05:49.638  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.638  7144  7576 D Compatibility: enabling receiver ResolveInfo{2a044924 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:05:49.638  7561  7561 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:05:49.648  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.648  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:49.648  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:05:49.648  7545  7545 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-09 16:05:49.658  7457  7527 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 56.275365
09-09 16:05:49.658  7530  7530 D elm:15121: ElmAgentService : onDestroy().
,09-09 16:05:49.658  7144  7576 D Compatibility: enabling receiver ResolveInfo{27f44c8d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:05:49.658  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 16:05:49.668  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.668  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.668  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.668  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.668  7144  7576 D Compatibility: enabling receiver ResolveInfo{3465be42 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:05:49.678  7144  7576 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 16:05:49.688  7581  7581 E Zygote  : MountEmulatedStorage(),
09-09 16:05:49.688  7581  7581 E Zygote  : v2
,09-09 16:05:49.688  7581  7581 I libpersona: KNOX_SDCARD checking this for 10032
09-09 16:05:49.688  7581  7581 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.688  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,09-09 16:05:49.688  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 16:05:49.688  7581  7581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 16:05:49.688  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 16:05:49.698  1015  1472 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7581 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 16:05:49.698  7581  7581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:49.698  7581  7581 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 16:05:49.698  1173  1173 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,09-09 16:05:49.698  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:05:49.698  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-09 16:05:49.708  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.708  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:49.708  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-09 16:05:49.708  1015  1134 D SecContentProvider2: uri = -1 selection = getSealedState
09-09 16:05:49.708  1015  1134 D SecContentProvider2: mCursor = null
09-09 16:05:49.708  7545  7545 I PopupuiReceiver_KNOX: getSealedState : true
09-09 16:05:49.708  1015  1481 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-09 16:05:49.708  1015  1481 D SecContentProvider2: mCursor = null
,09-09 16:05:49.708  7545  7545 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-09 16:05:49.708  1015  4362 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-09 16:05:49.708  1015  4362 D SecContentProvider2: mCursor = null
,09-09 16:05:49.708  7545  7545 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-09 16:05:49.708  7545  7545 D PopupuiReceiver: Action package removed
,09-09 16:05:49.718  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 16:05:49.718  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.718  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.718  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.718  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.718  1173  1598 I GeometricMosaic_Renderer: setBackgroundBitmap
,09-09 16:05:49.728  7561  7561 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 16:05:49.728  7581  7581 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.728  7581  7581 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:49.738  1015  1134 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 16:05:49.738  1015  1134 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-09 16:05:49.748  7597  7597 E Zygote  : MountEmulatedStorage(),
09-09 16:05:49.748  7597  7597 E Zygote  : v2
,09-09 16:05:49.748  7597  7597 I libpersona: KNOX_SDCARD checking this for 10145,
09-09 16:05:49.748  7597  7597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:49.748  7597  7597 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.748  7597  7597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:05:49.748  1015  1462 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7597 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 16:05:49.748  7597  7597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:05:49.748  1015  1462 I ActivityManager: Killing 6928:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-09 16:05:49.758  1015  6615 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-09 16:05:49.758  7186  7588 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-09 16:05:49.758  1015  6615 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.758  1015  6615 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.758  1015  6615 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.758  1015  6615 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.778  7611  7611 E Zygote  : MountEmulatedStorage()
09-09 16:05:49.778  7611  7611 I libpersona: KNOX_SDCARD checking this for 10068
09-09 16:05:49.778  7611  7611 E Zygote  : v2
09-09 16:05:49.778  7611  7611 I libpersona: KNOX_SDCARD not a persona
09-09 16:05:49.778  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:49.778  1015  6615 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7611 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-09 16:05:49.788  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-09 16:05:49.788  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:49.788  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.788  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 16:05:49.788  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.788  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.788  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:05:49.808  7622  7622 E Zygote  : MountEmulatedStorage()
09-09 16:05:49.808  1015  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7622 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-09 16:05:49.808  7622  7622 E Zygote  : v2
09-09 16:05:49.808  7622  7622 I libpersona: KNOX_SDCARD checking this for 10055
09-09 16:05:49.808  7622  7622 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.808  7597  7597 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.808  7622  7622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:05:49.808  7597  7597 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:49.808  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast,
,09-09 16:05:49.808  7622  7622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:49.818  7622  7622 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-09 16:05:49.818  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.818  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.818  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.818  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:05:49.818  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.818  7611  7611 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:49.818  1173  1203 I art     : Background sticky concurrent mark sweep GC freed 51697(2MB) AllocSpace objects, 5(101KB) LOS objects, 0% free, 23MB/24MB, paused 987us total 179.884ms
,09-09 16:05:49.838  7622  7622 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:05:49.838  7622  7622 D ActivityThread: Added TimaKeyStore provider
,09-09 16:05:49.858  7643  7643 E Zygote  : MountEmulatedStorage(),
09-09 16:05:49.858  7643  7643 I libpersona: KNOX_SDCARD checking this for 10087
09-09 16:05:49.858  7643  7643 E Zygote  : v2
09-09 16:05:49.858  7643  7643 I libpersona: KNOX_SDCARD not a persona
,09-09 16:05:49.868  1015  1134 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7643 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,09-09 16:05:49.868  7643  7643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:05:49.868  1015  1134 I ActivityManager: Killing 7105:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-09 16:05:49.868  7643  7643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:05:49.868  1015  1028 I ActivityManager: Killing 7334:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,09-09 16:05:49.878  7643  7643 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:05:49.878  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 16:05:49.878  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.888  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.888  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.888  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-09 16:05:49.888   307   307 I art     : Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 29.908ms
,09-09 16:05:49.908  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:49.908  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-09 16:05:49.908  7643  7643 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:05:49.908  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.908  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:49.908  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:05:49.908  7643  7643 D ActivityThread: Added TimaKeyStore provider
09-09 16:05:49.908   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.896ms
,09-09 16:05:49.928   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 18.365ms
,09-09 16:05:49.938  7581  7652 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 16:05:49.938  7581  7652 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 16:05:49.938  1015  4362 I ActivityManager: Killing 6677:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 16:05:49.948  7186  7588 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 16:05:49.948  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:05:49.948  7186  7588 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-09 16:05:49.948  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.948  7622  7622 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 16:05:49.948  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.948  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:05:49.948  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:05:49.968  7611  7611 D BadgeProvider: onCreate
,09-09 16:05:49.968  7611  7611 D BadgeProvider: DatabaseHelper
,09-09 16:05:49.968  1015  1027 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-09 16:05:49.968  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-09 16:05:49.968  7611  7620 E SQLiteLog: (28) failed to open "/data/user/0/com.sec.android.provider.badge/databases/badge.db" with flag (131138) and mode_t (0) due to error (30)
09-09 16:05:49.978  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:05:49.978  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:05:49.978  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: Failed to open database '/data/user/0/com.sec.android.provider.badge/databases/badge.db'.
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at com.sec.android.provider.badge.BadgeProvider.query(BadgeProvider.java:145)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:993)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
09-09 16:05:49.978  7611  7620 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 16:05:49.978  7611  7620 E DatabaseUtils: Writing exception to parcel
09-09 16:05:49.978  7611  7620 E DatabaseUtils: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.query(BadgeProvider.java:145)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.content.ContentProvider.query(ContentProvider.java:993)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
09-09 16:05:49.978  7611  7620 E DatabaseUtils: ,	at android.os.Binder.execTransact(Binder.java:446)
09-09 16:05:49.978  7457  7525 D Mms/MessagingNotification: getBadgeCount has exception
09-09 16:05:49.978  7457  7525 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-09 16:05:49.978  7597  7597 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-09 16:05:49.978  7597  7597 D ThemeInfoUtil: isCurrentFestival = false,
,09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: Exception thrown from onTableChanged
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:355)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.h(InternalIcingCorporaProvider.java:2273)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.e.Jx(UpdateIcingCorporaService.java:408)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.g.bdp(UpdateIcingCorporaService.java:347)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:687)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a$1.Jx(AppDataSearchDbOpenHelperBase.java:256)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:237)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:353)
09-09 16:05:49.978  7186  7588 E AppDataSearchHelper: 	... 14 more
,09-09 16:05:49.978  7186  7588 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
09-09 16:05:49.978  7186  7588 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 223 ms] updated apps [took 223 ms] ,
09-09 16:05:49.978  7581  7581 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,09-09 16:05:49.988  1015  4362 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228),
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282),
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source),
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
,09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 16:05:49.978  7581  7581 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 16:05:49.978  7581  7581 E LNoti   : [b] open fail. SQLException occured
09-09 16:05:49.988  1456  1857 D TP/SmsProvider: query,matched:26, calling pid = 7457
09-09 16:05:49.988  1456  1857 D TP/SmsProvider: match 26:Elapsed time : 0.773 ms

```
