#### Test 82914073d0f9b46_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-06 19:15:57.877  6539  6539 D ComposerPerformance: 1473182157886 ms / [DONE] Composer constructor
09-06 19:15:57.877  6539  6539 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-06 19:15:57.877  6539  6539 I Mms/ReservationManager: ReservationManager()
09-06 19:15:57.877  6539  6539 I Mms/ReservationManager: resetAfterConnected()
09-06 19:15:57.877  1457  1475 D TP/MmsSmsProvider: query,matched:7, calling pid = 6539
09-06 19:15:57.877  6539  6742 D Mms/Conversation: [start]    init() consume time = 71.553541
09-06 19:15:57.877  1457  1475 D TP/MmsSmsProvider: match 7:Elapsed time : 1.327 ms
09-06 19:15:57.877  6539  6539 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-06 19:15:57.877  1457  4709 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-06 19:15:57.887  1457  4709 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-06 19:15:57.887  1457  4709 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-06 19:15:57.887  1457  4709 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-06 19:15:57.887  1457  4709 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-06 19:15:57.887  1457  4709 D TP/MmsSmsProvider: need read changed broadcast:false
09-06 19:15:57.887  6539  6539 D Mms/MmsApp: [end]    onCreate() consume time = 12.165
09-06 19:15:57.897  6539  6742 D Mms/Conversation: [end]    init consume time = 2.566146
09-06 19:15:57.897  6539  6742 D Mms/MessagingNotification: [start]    init() consume time = 2.529323
09-06 19:15:57.897  6539  6742 D Mms/MessagingNotification: [end]    init consume time = 1.709896
09-06 19:15:57.897  1457  1653 D TP/MmsSmsProvider: query,matched:0, calling pid = 6539
09-06 19:15:57.897  1457  1653 V TP/MmsSmsProvider: getSimpleConversations entered.
09-06 19:15:57.897  1457  1653 D TP/MmsSmsProvider: match 0:Elapsed time : 0.911 ms
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-06 19:15:57.907  6539  6539 D Mms/MethodReflector: getSubId is called
09-06 19:15:57.907  6539  6539 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-06 19:15:57.907  6539  6539 D Mms/MethodReflector: getTelephonyProperty is called
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: auto download without roaming -> true
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-06 19:15:57.907  6539  6539 D Mms/DownloadManager: mAutoDownload ------> true
09-06 19:15:57.907  6539  6744 D Mms/Synchronizer: [start]    doSync consume time = 11.015156
09-06 19:15:57.907  6539  6743 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.312604
--------- beginning of system
09-06 19:15:57.907  1017  1759 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-06 19:15:57.907  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.907  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.907  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.907  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.917  6747  6747 E Zygote  : MountEmulatedStorage()
09-06 19:15:57.917  6747  6747 E Zygote  : v2
09-06 19:15:57.917  6747  6747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:57.917  6747  6747 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:15:57.917  6747  6747 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:57.927  6747  6747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:57.927  6747  6747 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:15:57.927  1457  1653 D TP/MmsSmsProvider: update, matched:300, calling pid = 6539
09-06 19:15:57.927  1457  1653 V TP/MmsSmsProvider: syncDBData start
09-06 19:15:57.927  1457  1653 V TP/MmsSmsProvider: syncDBData sms end
09-06 19:15:57.927  1457  1653 V TP/MmsSmsProvider: syncDBData mms end
09-06 19:15:57.927  1457  1653 V TP/MmsSmsProvider: syncDBData end
09-06 19:15:57.927  1017  1759 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6747 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-06 19:15:57.937  6539  6539 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-06 19:15:57.937  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:57.937  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:57.937  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-06 19:15:57.937  6539  6744 D Mms/Synchronizer: [end]    doSync consume time = 31.569219
09-06 19:15:57.937  1017  1223 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-06 19:15:57.937  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-06 19:15:57.947  1457  1475 D TP/MmsSmsProvider: query,matched:400, calling pid = 6539
09-06 19:15:57.947  6539  6760 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-06 19:15:57.947  1017  1473 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-06 19:15:57.947  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.947  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.947  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.947  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:57.957  6539  6760 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-06 19:15:57.957  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:57.957  6747  6747 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:57.967  1017  1473 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6763 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-06 19:15:57.977  1017  1030 I ActivityManager: Killing 6408:com.android.defcontainer/u0a3 (adj 15): empty #21
09-06 19:15:57.977  1017  1030 I ActivityManager: Killing 6328:com.android.calendar/u0a131 (adj 15): empty #22
09-06 19:15:57.977  6763  6763 E Zygote  : MountEmulatedStorage()
09-06 19:15:57.977  6763  6763 E Zygote  : v2
09-06 19:15:57.977  6763  6763 I libpersona: KNOX_SDCARD checking this for 10042
09-06 19:15:57.977  6763  6763 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:57.987  6763  6763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:57.987  6763  6763 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:57.987  6539  6743 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 46.936823
09-06 19:15:57.997  6763  6763 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-06 19:15:58.047  6763  6763 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.047  6763  6763 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.067  6747  6747 D BadgeProvider: onCreate
09-06 19:15:58.067  6747  6747 D BadgeProvider: DatabaseHelper
09-06 19:15:58.067  6763  6763 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:15:58.067  6763  6763 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:15:58.067  6763  6763 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-06 19:15:58.107  2642  2652 I art     : Explicit concurrent mark sweep GC freed 14396(674KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.022ms total 60.539ms
09-06 19:15:58.107  1017  4206 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-06 19:15:58.117  6539  6742 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-06 19:15:58.127  1457  4709 D TP/SmsProvider: query,matched:26, calling pid = 6539
09-06 19:15:58.127  1457  4709 D TP/SmsProvider: match 26:Elapsed time : 1.242 ms
09-06 19:15:58.137  1457  1475 D TP/MmsSmsProvider: query,matched:6, calling pid = 6539
09-06 19:15:58.137  1457  1475 D TP/MmsSmsProvider: match 6:Elapsed time : 2.029 ms
09-06 19:15:58.187  6763  6763 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-06 19:15:58.187  1017  1344 I ActivityManager: Killing 6161:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-06 19:15:58.187  1017  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-06 19:15:58.187  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-06 19:15:58.197  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.197  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.197  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.197  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.207  1939  6586 I qtaguid : Untagging socket 101
09-06 19:15:58.207  1017  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6782 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:15:58.217  6782  6782 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.217  6782  6782 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:15:58.217  6782  6782 E Zygote  : v2
09-06 19:15:58.217  6782  6782 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.217  6782  6782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.217  6782  6782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.217  6782  6782 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:15:58.247  6773  6773 D AndroidRuntime: 
09-06 19:15:58.247  6773  6773 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:15:58.247  6773  6773 D AndroidRuntime: CheckJNI is OFF
09-06 19:15:58.247  6773  6773 D AndroidRuntime: readGMSProperty: start
09-06 19:15:58.247  6773  6773 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:15:58.247  6773  6773 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:15:58.247  6773  6773 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:15:58.247  6773  6773 D AndroidRuntime: readGMSProperty: end
09-06 19:15:58.247  6773  6773 D AndroidRuntime: addProductProperty: start
09-06 19:15:58.287  6782  6782 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.287  6782  6782 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.317  1939  6644 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 111.192ms
09-06 19:15:58.337  1939  1939 I ConfigFetchService: fetch service done; releasing wakelock
09-06 19:15:58.337  1939  1939 I ConfigFetchService: stopping self
09-06 19:15:58.337   283   283 E installd: system dir 0 : /system/app/
09-06 19:15:58.337   283   283 E installd: system dir 1 : /system/priv-app/
09-06 19:15:58.337   283   283 E installd: system dir 2 : /vendor/app/
09-06 19:15:58.337   283   283 E installd: system dir 3 : /oem/app/
09-06 19:15:58.347  1017  1223 I art     : Explicit concurrent mark sweep GC freed 139600(7MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 23MB/34MB, paused 2.899ms total 185.428ms
09-06 19:15:58.347  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-06 19:15:58.347  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.347  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.347  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.347  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.367  6805  6805 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.367  6805  6805 E Zygote  : v2
09-06 19:15:58.367  6805  6805 I libpersona: KNOX_SDCARD checking this for 10023
09-06 19:15:58.367  6805  6805 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.367  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.377  1017  1029 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6805 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-06 19:15:58.377  1017  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-06 19:15:58.387  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.387  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:15:58.397  6773  6773 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:15:58.407  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.407  6805  6805 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.417  6524  6578 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
09-06 19:15:58.417  1017  1488 I ActivityManager: Killing 6457:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-06 19:15:58.427  6773  6773 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:15:58.437  1939  1961 W art     : Suspending all threads took: 11.483ms
09-06 19:15:58.447  6524  6578 I AcmsKeyStoreHelper: Key Store exist
09-06 19:15:58.447  6524  6578 I AcmsKeyStoreHelper: Hence loading the keystore file
09-06 19:15:58.447  6589  6648 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-06 19:15:58.447  6589  6648 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:15:58.447  6589  6648 I GAv4    :   adb logcat -s GAv4
09-06 19:15:58.457  1017  1498 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:15:58.457  1017  1498 I PersonaManagerService: PersonaId don't exist
09-06 19:15:58.457  1017  1498 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:15:58.457  1017  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:15:58.477  1017  1498 W ActivityManager: mDVFSHelper.acquire()
09-06 19:15:58.477  1017  1498 D FocusedStackFrame: Set to : 0
09-06 19:15:58.487  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.487  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.487  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.487  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.487  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:15:58.487  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:15:58.497  6825  6825 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.497  1939  4201 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-06 19:15:58.497  6825  6825 E Zygote  : v2
09-06 19:15:58.497  6825  6825 I libpersona: KNOX_SDCARD checking this for 10170
09-06 19:15:58.497  6825  6825 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.507  6825  6825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.507  1017  1498 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6825 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:15:58.507  1017  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 19:15:58.507  1017  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:15:58.507  1017  1498 D InputDispatcher: Focused application set to: xxxx
09-06 19:15:58.507  1017  1498 D InputDispatcher: Focus left window: 1489
09-06 19:15:58.507  6825  6825 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.507  6773  6773 D AndroidRuntime: Shutting down VM
09-06 19:15:58.507  6825  6825 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:15:58.517  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:15:58.517  6524  6578 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-06 19:15:58.517  6524  6578 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-06 19:15:58.517  6524  6578 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-06 19:15:58.517  6524  6578 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-06 19:15:58.517  6524  6578 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-06 19:15:58.517  6524  6578 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
09-06 19:15:58.517  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:15:58.517  6524  6578 D AcmsCore: This is NOT a valid MirrorLink app
09-06 19:15:58.517  6524  6578 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-06 19:15:58.517   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-06 19:15:58.517  6524  6578 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-06 19:15:58.517  6524  6578 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-06 19:15:58.517  6524  6578 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
09-06 19:15:58.517  6524  6524 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-06 19:15:58.517  6524  6524 D AcmsService: Enter onDestroy
09-06 19:15:58.517  6524  6524 I AcmsService: cleanUp(): inside service clean up
09-06 19:15:58.517  6524  6524 D AcmsCore: AcmsCore: inside DeInit
09-06 19:15:58.517  6524  6524 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-06 19:15:58.517  6524  6524 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-06 19:15:58.517  6524  6524 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-06 19:15:58.517  6524  6524 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-06 19:15:58.517  6524  6524 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-06 19:15:58.517  6589  6648 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-06 19:15:58.517  6524  6524 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-06 19:15:58.517  1017  1487 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-06 19:15:58.517  6524  6524 D AcmsService: killing acms process
09-06 19:15:58.517  6524  6524 I Process : Sending signal. PID: 6524 SIG: 9
09-06 19:15:58.537  6805  6805 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-06 19:15:58.537  6825  6825 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.537  6825  6825 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.557  1017  1344 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 19:15:58.557  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:15:58.557  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:15:58.557  1017  1017 V ActivityManager: Display changed displayId=0
09-06 19:15:58.557  1017  1048 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-06 19:15:58.557  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:15:58.567  1017  1048 W DisplayManagerService: Failed to notify process 6524 that displays changed, assuming it died.
09-06 19:15:58.567  1017  1048 W DisplayManagerService: android.os.TransactionTooLargeException
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:15:58.567  1017  1048 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:15:58.577  6539  6742 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-06 19:15:58.577  6589  6648 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-06 19:15:58.597  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-06 19:15:58.597  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-06 19:15:58.597  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-06 19:15:58.607  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-06 19:15:58.607  1017  1344 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:15:58.607  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-06 19:15:58.607  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-06 19:15:58.607  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-06 19:15:58.617  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-06 19:15:58.617  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-06 19:15:58.617  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-06 19:15:58.617  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-06 19:15:58.617  1017  1498 I ActivityManager: Process ACMS.Process (pid 6524)(adj 0) has died(58,753)
09-06 19:15:58.627  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-06 19:15:58.627  6805  6805 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-06 19:15:58.627  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 19:15:58.637  6589  6648 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-06 19:15:58.637   257  1039 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
09-06 19:15:58.637   257   449 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
09-06 19:15:58.647  6589  6845 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-06 19:15:58.647  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{10aed85 token=android.os.BinderProxy@364a2a12 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 19:15:58.647  1489  1489 D Launcher: onTrimMemory. Level: 20
09-06 19:15:58.657  1939  4201 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-06 19:15:58.667  6589  6602 W art     : Suspending all threads took: 6.767ms
09-06 19:15:58.717  6773  6773 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:15:58.727  1939  4201 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-06 19:15:58.737  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-06 19:15:58.737  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:15:58.737  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:15:58.737  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:15:58.757  6825  6825 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:15:58.797  6825  6825 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4536-4538)
09-06 19:15:58.797  6825  6825 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:15:58.827  6825  6825 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fd5c2b3}
09-06 19:15:58.827  6825  6825 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:15:58.837  6825  6825 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:15:58.897  6825  6825 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-06 19:15:58.897  6825  6825 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:58.907  6825  6825 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:15:58.907  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-06 19:15:58.907  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.907  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.907  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.907  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.927  6855  6855 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.927  6855  6855 E Zygote  : v2
09-06 19:15:58.927  6855  6855 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:15:58.927  6855  6855 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.927  6855  6855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.927  6855  6855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.927  1017  1498 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:15:58.927  6855  6855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:15:58.927  1017  1498 I ActivityManager: Killing 6472:com.sec.spp.push/u0a32 (adj 15): empty #21
09-06 19:15:58.957  6855  6855 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.957  6855  6855 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.977  6825  6825 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:15:58.977  6825  6825 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:15:58.977  6825  6825 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:15:58.977  6825  6825 I Adreno-EGL: Local Branch: 
09-06 19:15:58.977  6825  6825 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:15:58.977  6825  6825 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:15:58.977  6825  6825 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-06 19:15:58.977  6855  6855 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-06 19:15:58.977  6855  6855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-06 19:15:58.977  1017  1498 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-06 19:15:58.977  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-06 19:15:58.987  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:58.987  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:58.987  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-06 19:15:58.987  1017  1344 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-06 19:15:58.987  6855  6855 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-06 19:15:59.007  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
09-06 19:15:59.007  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
09-06 19:15:59.007  6589  6853 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:15:59.007  6589  6853 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-06 19:15:59.007  1017  1393 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:15:59.007  1017  1393 D AlarmManagerService: Setting time of day to sec=1473182158
09-06 19:15:59.007  1017  1393 D AlarmManagerService: Trying to open a file
09-06 19:15:59.007  1017  1393 D AlarmManagerService: File Open Success
09-06 19:15:59.007  1017  1393 D AlarmManagerService: File Close Success
09-06 19:15:59.007  1017  1393 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
09-06 19:15:58.418  1017  1096 V AlarmManager: waitForAlarm result :65536
09-06 19:15:58.418  1017  1393 W AlarmManagerService: Unable to set rtc to 1473182158: Invalid argument
09-06 19:15:58.418  6855  6875 E FilterInstaller: installFilters
09-06 19:15:58.418  6855  6875 E FilterInstaller: There is no requred permission
09-06 19:15:58.418  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=94757 batch.start=96331
09-06 19:15:58.418  1017  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-06 19:15:58.437  1017  1017 I BackgroundCompactionService: onStart. jobID=801
09-06 19:15:58.437  1017  1043 W ActivityManager: Failed to update preferences for: com.sec.spp.push
09-06 19:15:58.437  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
09-06 19:15:58.437  1017  6876 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
09-06 19:15:58.437  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473182158446
09-06 19:15:58.437  1017  6876 I BackgroundCompactionService: compact_memory command done
09-06 19:15:58.447  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
09-06 19:15:58.447  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
09-06 19:15:58.447  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
09-06 19:15:58.447  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
09-06 19:15:58.447  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
09-06 19:15:58.447  6589  6853 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-06 19:15:58.447  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
09-06 19:15:58.457  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
09-06 19:15:58.477  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:15:58.477  1017  1759 D SettingsProvider: name = lockscreen_zoom_panning_effect
09-06 19:15:58.477  1017  1759 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:15:58.477  1017  1759 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:15:58.477  1017  1759 D SettingsProvider: selectionArgs: false
09-06 19:15:58.477  1017  1759 D SettingsProvider: selectionArgs: 10049
09-06 19:15:58.477  1017  1759 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:15:58.477  1017  1759 D SettingsProvider: ret = -1
09-06 19:15:58.477  1180  1180 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
09-06 19:15:58.487  1180  1180 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-06 19:15:58.487  1180  1180 I GeometricMosaic_Keyguard: update
09-06 19:15:58.487  1180  1180 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
09-06 19:15:58.497  1017  1344 I ActivityManager: Killing 5050:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-06 19:15:58.507  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{127cf234 u0 com.test.thalitest/.MainActivity t163}
09-06 19:15:58.517  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:15:58.527  1017  1017 I DrmEventService:  no response from SecureClock 
09-06 19:15:58.527  1017  1017 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
09-06 19:15:58.537  1017  1017 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
09-06 19:15:58.537  1017  1017 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
09-06 19:15:58.537  1017  1017 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
09-06 19:15:58.547  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-06 19:15:58.547  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.547  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.547  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.547  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.557  1017  1017 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6885 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:15:58.567  6885  6885 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.567  6885  6885 E Zygote  : v2
09-06 19:15:58.567  6885  6885 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:15:58.567  6885  6885 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.567  6885  6885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.567   290   290 E SMD     : DCD OFF
09-06 19:15:58.577  6885  6885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.577  6885  6885 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:15:58.577  6589  6853 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-06 19:15:58.577  6589  6853 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18871bc1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-06 19:15:58.587  6589  6853 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-06 19:15:58.587  1180  1180 I KeyguardEffectViewUtil: set current wallpaper info
09-06 19:15:58.587  1017  1498 D SettingsProvider: name = keyguard_current_wallpaper_type
09-06 19:15:58.587  1017  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:15:58.587  1017  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:15:58.587  1017  1498 D SettingsProvider: selectionArgs: false
09-06 19:15:58.587  1017  1498 D SettingsProvider: selectionArgs: 10049
09-06 19:15:58.587  1017  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:15:58.587  1017  1498 D SettingsProvider: ret = -1
09-06 19:15:58.587  1017  1759 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-06 19:15:58.587  1017  1759 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:15:58.587  1017  1759 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:15:58.587  1017  1759 D SettingsProvider: selectionArgs: false
09-06 19:15:58.587  1017  1759 D SettingsProvider: selectionArgs: 10049
09-06 19:15:58.587  1017  1759 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:15:58.587  1017  1759 D SettingsProvider: ret = -1
09-06 19:15:58.587  1017  1487 D SettingsProvider: name = keyguard_current_wallpaper_res_id
09-06 19:15:58.587  1017  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:15:58.587  1017  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:15:58.587  1017  1487 D SettingsProvider: selectionArgs: false
09-06 19:15:58.587  1017  1487 D SettingsProvider: selectionArgs: 10049
09-06 19:15:58.587  1017  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:15:58.587  1017  1487 D SettingsProvider: ret = -1
09-06 19:15:58.607  6885  6885 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.607  6885  6885 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.617  6825  6825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:15:58.627  6825  6825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:15:58.627  6825  6825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:15:58.637  6825  6825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:15:58.637  6825  6825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:15:58.667  1180  1651 D TEST    : run!!!
09-06 19:15:58.667  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:15:58.667  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:15:58.667  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:15:58.687  1180  1180 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
09-06 19:15:58.687  1180  1651 I GeometricMosaic_Renderer: setBackgroundBitmap
09-06 19:15:58.687  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
09-06 19:15:58.717  1017  1759 I ActivityManager: Killing 6502:com.samsung.helphub/1000 (adj 15): empty #21
09-06 19:15:58.727  6885  6885 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
09-06 19:15:58.737  1017  1223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:15:58.737  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
09-06 19:15:58.737  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:58.737  1017  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:15:58.737  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:15:58.757  6825  6825 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:58.767  1017  1223 I ActivityManager: Killing 6487:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-06 19:15:58.777  6825  6825 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:15:58.787  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:15:58.787  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
09-06 19:15:58.787  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:58.787  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:15:58.787  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:15:58.787  6825  6825 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:15:58.787  6825  6825 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-06 19:15:58.797  6825  6825 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 19:15:58.797  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Sep 06 19:15:58 GMT+02:00 2016
09-06 19:15:58.797  1017  1487 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:15:58.797  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-06 19:15:58.797  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:58.797  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:58.797  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-06 19:15:58.797  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-06 19:15:58.807  6825  6825 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:58.807  6825  6825 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:58.807  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
09-06 19:15:58.807  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.807  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.807  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.807  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:58.807  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-06 19:15:58.807  2819  2819 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-06 19:15:58.807  2819  2819 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-06 19:15:58.817  2819  6909 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
09-06 19:15:58.817  2819  6909 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
09-06 19:15:58.817  6911  6911 E Zygote  : MountEmulatedStorage()
09-06 19:15:58.817  6911  6911 E Zygote  : v2
09-06 19:15:58.817  6911  6911 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:15:58.817  6911  6911 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:58.817  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:58.817  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.827  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:15:58.827  1017  1488 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6911 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:15:58.827  2819  6909 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Sep 06 19:15:58 GMT+02:00 2016
09-06 19:15:58.847   315   315 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 20.980ms
09-06 19:15:58.847  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:58.847  6911  6911 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:58.857  2819  6909 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
09-06 19:15:58.857   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.758ms
09-06 19:15:58.857  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-06 19:15:58.877   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 17.577ms
09-06 19:15:58.887  6911  6911 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3027a73b
09-06 19:15:58.907  6911  6911 I SA      : [SSP] onCreated
09-06 19:15:58.917  6911  6911 I SA      : [TPM] There is no property file
09-06 19:15:58.917  6911  6911 I SA      : [SCU] isHaveSA() - false
09-06 19:15:58.917  6825  6931 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:15:58.927  6911  6911 I SA      : [TPM] getModelProperty : null
09-06 19:15:58.927  6911  6911 I SA      : [TPM] getCSCProperty : null
09-06 19:15:58.927  6911  6911 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-06 19:15:58.927  6911  6911 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 19:15:58.927  6911  6911 I SA      : [DM] TFT FEATURE: false
09-06 19:15:58.927  1017  1367 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:15:58.927  1017  1367 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:15:58.927  1017  1367 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:15:58.927  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:15:58.927  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:15:58.937  6911  6911 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
09-06 19:15:58.937  6825  6825 V ActivityThread: updateVisibility : ActivityRecord{1c30ff82 token=android.os.BinderProxy@3948d864 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:15:58.937  6911  6911 I SA      : [DM] init START
,09-06 19:15:58.937  6825  6882 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-06 19:15:58.937  6911  6911 I SA      : [DM] This device is not a Vodafone
,09-06 19:15:58.937  6825  6825 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-06 19:15:58.937  6825  6825 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-06 19:15:58.947  6911  6911 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-06 19:15:58.957   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:15:58.957  6911  6911 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75),
09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-06 19:15:58.967  6911  6911 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-06 19:15:58.977  6911  6911 I SA      : [SCU] isHaveSA() - false
09-06 19:15:58.977  6911  6911 I SA      : support phone number id : false
09-06 19:15:58.977  6911  6911 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:15:58.977  6911  6911 I SA      : [DM] init END
,09-06 19:15:58.977  1017  4205 D InputDispatcher: Focus entered window: 6825
,09-06 19:15:58.987  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:15:58.987  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:15:58.987  6825  6825 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:15:58.987  6825  6931 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 19:15:58.987  6825  6931 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-06 19:15:58.987  6825  6931 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:15:59.017  1017  1498 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:15:59.017  1017  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:15:59.017  1180  1180 D PanelView: There is/are notification(s) 
,09-06 19:15:59.027  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,09-06 19:15:59.037  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.037  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.037  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.037  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.037  6825  6825 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 19:15:59.047  6825  6825 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3948d864 time:95380
,09-06 19:15:59.047  6940  6940 E Zygote  : MountEmulatedStorage(),
09-06 19:15:59.047  6940  6940 E Zygote  : v2
09-06 19:15:59.047  6940  6940 I libpersona: KNOX_SDCARD checking this for 10058
09-06 19:15:59.047  6940  6940 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.047  1017  1505 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6940 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:15:59.047  6940  6940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:59.047  1017  1048 I ActivityManager: Displayed Component not be shown by security: +1s42ms (total +1s166ms)
09-06 19:15:59.047  1017  1048 W ActivityManager: mDVFSHelper.release()
09-06 19:15:59.047  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{127cf234 u0 com.test.thalitest/.MainActivity t163} time:95389
,09-06 19:15:59.057  6940  6940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:15:59.057  1017  1505 I ActivityManager: Killing 6182:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-06 19:15:59.057  6940  6940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:15:59.057   257   449 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-06 19:15:59.057   257   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-06 19:15:59.057  1874  1874 I SamsungIME: getCurrentCandidateView
,09-06 19:15:59.087  6940  6940 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.087  6940  6940 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.137  6940  6940 I ExternalOEMControlProvider: onCreate
,09-06 19:15:59.157  6940  6957 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,09-06 19:15:59.157  1017  1505 I ActivityManager: Killing 5991:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-06 19:15:59.157  1734  1734 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,09-06 19:15:59.167  1734  1734 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:15:59.167  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,09-06 19:15:59.167  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.167  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.167  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.167  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.177  6958  6958 E Zygote  : MountEmulatedStorage(),
,09-06 19:15:59.177  6958  6958 E Zygote  : v2
,09-06 19:15:59.187  6958  6958 I libpersona: KNOX_SDCARD checking this for 10081
,09-06 19:15:59.187  6958  6958 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.187  6958  6958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:15:59.187  6958  6958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:15:59.187  6958  6958 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:15:59.197  6825  6825 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6825
09-06 19:15:59.197  1017  1136 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6958 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:15:59.207  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.207  6958  6958 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.207  1874  1874 D SamsungIME: Dismiss ExpandCandiate
,09-06 19:15:59.237  6958  6958 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 19:15:59.237  6958  6958 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:15:59.237  6958  6958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:15:59.237  6958  6958 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:15:59.237  6958  6958 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-06 19:15:59.287  1017  1136 D SettingsProvider: name = next_alarm_formatted
,09-06 19:15:59.287  1017  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:15:59.287  1017  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:15:59.287  1017  1136 D SettingsProvider: selectionArgs: false
09-06 19:15:59.287  1017  1136 D SettingsProvider: selectionArgs: 10081
,09-06 19:15:59.287  1017  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:15:59.287  1017  1136 D SettingsProvider: ret = -1
,09-06 19:15:59.287  6539  6539 I Mms/MmsApp:  start initViewCache mms
,09-06 19:15:59.287  6539  6539 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1901.649009
09-06 19:15:59.287  6539  6539 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-06 19:15:59.387  6825  6825 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:15:59.417  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:15:59.427  6539  6539 D AbsListView: Get MotionRecognitionManager
,09-06 19:15:59.437  6958  6958 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 137.141ms
09-06 19:15:59.437  1017  1223 D MotionRecognitionService:  ssp status : false
,09-06 19:15:59.437  6539  6539 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 149.700208
,09-06 19:15:59.487  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:15:59.517  1874  1874 I SamsungIME: KeybaordView init() : load resources
,09-06 19:15:59.517  6825  6939 D jxcore_app_log: JniHelper::setJavaVM(0xb72d32b0), pthread_self() = -1215950800
,09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:15:59.527  6825  6939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33db0601 added. We now have 1 listener(s)
,09-06 19:15:59.527  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-06 19:15:59.537  6825  6939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:15:59.537  6825  6939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:15:59.537  6825  6939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:15:59.537  6539  6539 D Mms/BubbleViewCache: fillCache bubble = 1
,09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:15:59.547  6825  6939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c52294 added. We now have 1 listener(s)
09-06 19:15:59.547  6825  6939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:15:59.547  1017  4206 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:15:59.547  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.547  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.547  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.547  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.557  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:15:59.557  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:15:59.557  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:15:59.557  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:15:59.557  6825  6939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:15:59.557  1874  1874 I SamsungIME: getCurrentKeyboard
09-06 19:15:59.557  1874  1874 I SamsungIME: getTextKeyboard
,09-06 19:15:59.557  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:15:59.557  1017  1029 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4178, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:15:59.557  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:15:59.557  1017  1029 D BatteryService: stay LED for charging
09-06 19:15:59.557  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:15:59.567  6978  6978 E Zygote  : MountEmulatedStorage()
,09-06 19:15:59.567  6978  6978 E Zygote  : v2
09-06 19:15:59.567  6978  6978 I libpersona: KNOX_SDCARD checking this for 10090
09-06 19:15:59.567  6978  6978 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.567  1017  4206 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6978 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-06 19:15:59.567  1017  4206 I ActivityManager: Killing 6093:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-06 19:15:59.567  6825  6939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-06 19:15:59.567  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:15:59.577  1017  1017 I MotionRecognitionService: Plugged
09-06 19:15:59.577  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:15:59.577  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:59.577  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:15:59.577  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:15:59.577  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:15:59.577  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
09-06 19:15:59.577  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:15:59.577  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:15:59.587  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:15:59.587  3221  3359 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:15:59.587  6825  6939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-06 19:15:59.597  6825  6939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:15:59.597  6825  6939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:15:59.597  6825  6939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:15:59.597  6825  6939 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:15:59.597  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-06 19:15:59.597  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:15:59.597  1874  1874 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-06 19:15:59.597  6825  6939 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:15:59.607  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:15:59.607  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:15:59.607  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:59.607  6978  6978 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.637  6825  6825 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:15:59.637  6978  6978 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,09-06 19:15:59.647  6978  6978 D elm:15121: ELMEngine.ELMEngine( context ).
,09-06 19:15:59.647  6978  6978 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-06 19:15:59.647  1017  1759 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-06 19:15:59.647  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-06 19:15:59.647  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:15:59.647  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:59.647  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-06 19:15:59.657  6978  6978 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,09-06 19:15:59.657  1017  1367 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-06 19:15:59.657  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.657  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.657  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.657  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.657  6978  6978 D elm:15121: ElmAgentService : onCreate()
,09-06 19:15:59.657  6978  6994 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,09-06 19:15:59.667  6978  6994 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
09-06 19:15:59.667  6978  6978 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
09-06 19:15:59.667  6978  6978 D elm:15121: ModuleBase.ModifySetAlarm()
09-06 19:15:59.667  6978  6978 D elm:15121: MDMBridge.getInstance()
09-06 19:15:59.667  6978  6978 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:15:59.677  6996  6996 E Zygote  : MountEmulatedStorage()
,09-06 19:15:59.677  6996  6996 E Zygote  : v2
09-06 19:15:59.677  6996  6996 I libpersona: KNOX_SDCARD checking this for 10130
09-06 19:15:59.677  6996  6996 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.677  6996  6996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:15:59.677  1017  1367 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6996 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-06 19:15:59.687  6996  6996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:15:59.687  6996  6996 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-06 19:15:59.687  6978  6978 D elm:15121: ElmAgentService : onDestroy().
09-06 19:15:59.687  1017  1488 I ActivityManager: Killing 6557:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-06 19:15:59.707  6996  6996 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.707  6996  6996 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.747  6996  6996 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:15:59.747  6996  6996 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-06 19:15:59.767  1017  1223 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-06 19:15:59.767  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.767  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.767  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.767  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.777  7011  7011 E Zygote  : MountEmulatedStorage()
09-06 19:15:59.777  7011  7011 I libpersona: KNOX_SDCARD checking this for 10131
,09-06 19:15:59.777  7011  7011 E Zygote  : v2
09-06 19:15:59.777  7011  7011 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:59.777  1017  1223 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7011 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-06 19:15:59.777  1017  1223 I ActivityManager: Killing 6589:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-06 19:15:59.787  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:15:59.787  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:59.787  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:15:59.807  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.807  7011  7011 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.827  7011  7011 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:15:59.827  7011  7011 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:15:59.827  7011  7011 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:15:59.847  2494  5160 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:15:59.857  1017  1344 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-06 19:15:59.867  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-06 19:15:59.867  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:15:59.867  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:59.867  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:15:59.877  1017  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,09-06 19:15:59.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.897  7031  7031 E Zygote  : MountEmulatedStorage()
09-06 19:15:59.897  7031  7031 E Zygote  : v2
09-06 19:15:59.897  7031  7031 I libpersona: KNOX_SDCARD checking this for 10037
09-06 19:15:59.897  7031  7031 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.897  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:59.897  1017  1030 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7031 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:15:59.897  1017  1488 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-06 19:15:59.897  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-06 19:15:59.897  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:15:59.907  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:15:59.907  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:15:59.907  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:15:59.907  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
09-06 19:15:59.907  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-06 19:15:59.917  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.917  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.917  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:59.917  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:15:59.927  7044  7044 E Zygote  : MountEmulatedStorage()
09-06 19:15:59.927  7044  7044 E Zygote  : v2
09-06 19:15:59.927  7044  7044 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:15:59.927  7044  7044 I libpersona: KNOX_SDCARD not a persona
,09-06 19:15:59.927  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:15:59.927  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:15:59.937  1017  1136 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-06 19:15:59.937  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:15:59.947  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.947  7031  7031 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.967  7031  7031 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-06 19:15:59.967  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:15:59.977  7044  7044 D ActivityThread: Added TimaKeyStore provider
,09-06 19:15:59.997  1017  1096 V AlarmManager: waitForAlarm result :8
,09-06 19:16:00.007  7031  7031 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-06 19:16:00.007  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:00.007  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:16:00.007  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:00.017  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,09-06 19:16:00.017  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.017  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.017  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.017  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:00.027  7063  7063 E Zygote  : MountEmulatedStorage()
,09-06 19:16:00.037  7063  7063 E Zygote  : v2
09-06 19:16:00.037  7063  7063 I libpersona: KNOX_SDCARD checking this for 10153
09-06 19:16:00.037  7063  7063 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:00.037  7063  7063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:00.037  7063  7063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:00.037  1017  1488 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7063 uid=10153 gids={50153, 9997} abi=armeabi-v7a
09-06 19:16:00.037  7063  7063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:00.037  1017  1488 I ActivityManager: Killing 6606:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-06 19:16:00.077  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:00.077  7063  7063 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:00.097  7063  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:00.107  1017  4205 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,09-06 19:16:00.117  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.117  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.117  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:00.117  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:00.127  7082  7082 E Zygote  : MountEmulatedStorage(),
09-06 19:16:00.127  7082  7082 E Zygote  : v2
09-06 19:16:00.127  7082  7082 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:00.127  7082  7082 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:00.127  7082  7082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:00.127  7082  7082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:00.127  1017  4205 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:00.127  7082  7082 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:00.127  1017  4205 I ActivityManager: Killing 6628:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-06 19:16:00.157  1017  4206 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-06 19:16:00.157  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-06 19:16:00.157  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:00.157  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:00.157  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-06 19:16:00.157  7082  7082 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:00.157  7082  7082 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:00.187  7082  7082 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473182160195
09-06 19:16:00.187  7082  7082 D         : TimeServiceNative: User Time to be set is 1473182160195
09-06 19:16:00.187  7082  7082 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-06 19:16:00.187  7082  7082 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-06 19:16:00.187  7082  7082 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473182160195
,09-06 19:16:00.187   327   557 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-06 19:16:00.197  7082  7082 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473182160195
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473182160195, operation = 0
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/4/71 10:58:43
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:Value read from RTC seconds = 36932323000
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:new time 1473182160195 
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon: delta 1436249837195 genoff 1436249837195 
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249837195 to memory
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-06 19:16:00.197   327  7100 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-06 19:16:00.207  1017  1473 I ActivityManager: Killing 6649:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-06 19:16:00.217   327  7100 D QC-time-services: Updating the TOD offset
09-06 19:16:00.217   327  7100 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249837195 to memory
09-06 19:16:00.217   327  7100 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-06 19:16:00.217   327  7100 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-06 19:16:00.217   327  7100 E QC-time-services: Daemon:Update to modem bit set
09-06 19:16:00.217   327  7100 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-06 19:16:00.217   327  7100 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285037195
,09-06 19:16:00.217  7082  7082 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-06 19:16:00.217  1017  4205 I ActivityManager: Killing 6661:com.google.android.partnersetup/u0a14 (adj 15): empty #21
09-06 19:16:00.217   327   555 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-06 19:16:00.217   327   557 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-06 19:16:00.227  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-06 19:16:00.227  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,09-06 19:16:00.227  2494  2494 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:16:00.237  2494  2494 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:16:00.237  2494  2494 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-06 19:16:00.237  2494  2494 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,09-06 19:16:00.247  2494  2494 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-06 19:16:00.247  2494  2494 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,09-06 19:16:00.247  2494  2494 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-06 19:16:00.247  2494  2494 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,09-06 19:16:00.247  2494  2494 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,09-06 19:16:00.257  2494  2494 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-06 19:16:00.257  2494  2494 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,09-06 19:16:00.267  6825  6992 W jxcore-log: Initializing JXcore engine
09-06 19:16:00.267  6825  6992 W jxcore-log: JXcore engine is ready
,09-06 19:16:00.267  2494  2494 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
09-06 19:16:00.267  2494  2494 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,09-06 19:16:00.317  2018  2018 E audit   : type=1400 msg=audit(1473182160.317:205): avc:  denied  { ioctl } for  pid=6992 comm="Thread-1280" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 19:16:00.317  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:00.317  2018  2018 E audit   : type=1300 msg=audit(1473182160.317:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dfb38f8 items=0 ppid=315 ppcomm=main pid=6992 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1280" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:16:00.317  2018  2018 E audit   : type=1320 msg=audit(1473182160.317:205): 
,09-06 19:16:00.337  6825  6992 W jxcore-log: Starting JXcore engine
,09-06 19:16:00.437  6825  6992 W jxcore-log: Platform android
09-06 19:16:00.437  6825  6992 W jxcore-log: 
09-06 19:16:00.437  6825  6992 W jxcore-log: Process ARCH arm
09-06 19:16:00.437  6825  6992 W jxcore-log: 
,09-06 19:16:00.657  6825  6992 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:16:00.657  6825  6992 I jxcore-log: 
,09-06 19:16:00.657  6825  6992 W jxcore-log: JXcore engine is started
,09-06 19:16:00.667  6825  6939 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:16:00.667  6825  6825 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:16:01.157  7031  7031 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-06 19:16:01.157  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:01.157  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.157  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-06 19:16:01.167  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-06 19:16:01.167  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:01.167  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.167  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-06 19:16:01.167  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:01.167  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.167  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:16:01.177  1017  1367 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-06 19:16:01.177  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-06 19:16:01.177  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:01.177  1017  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.177  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:16:01.187  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:01.187  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.187  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:16:01.197  1017  1759 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-06 19:16:01.197  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-06 19:16:01.197  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:01.197  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:01.197  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:16:01.207  1017  1223 I ActivityManager: Killing 6700:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:16:01.207   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb82557c8
09-06 19:16:01.207   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-06 19:16:01.207   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:16:01.207   272   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1205512904)
,09-06 19:16:01.257   272   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
09-06 19:16:01.257   272   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:16:01.257   272   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1205512904) wakelock released: 1, error no: 0
09-06 19:16:01.257   272   343 I rmt_storage: 
,09-06 19:16:01.267   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb82557c8,
,09-06 19:16:01.577   290   290 E SMD     : DCD OFF,
,09-06 19:16:01.637  1017  3381 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 19:16:02.737  2642  2642 I ConfigService: onDestroy
,09-06 19:16:04.577   290   290 E SMD     : DCD OFF
,09-06 19:16:06.637  1017  3381 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:16:06.797  1017  3360 D SSRM:n  : SIOP:: AP = 400
,09-06 19:16:07.577   290   290 E SMD     : DCD OFF,
,09-06 19:16:07.827  1017  1058 D PackageManager: [MSG] MCS_UNBIND
,09-06 19:16:07.827  1017  1030 I ActivityManager: Killing 6718:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-06 19:16:07.887  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-06 19:16:09.607  1017  1136 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:09.607  1017  1136 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:16:09.607  1017  1136 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-06 19:16:09.607  1017  1136 D BatteryService: stay LED for charging
09-06 19:16:09.607  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:09.607  1017  1017 I MotionRecognitionService: Plugged
,09-06 19:16:09.607  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:16:09.607  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:16:09.607  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:16:09.617  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-06 19:16:09.617  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-06 19:16:09.627  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:16:09.627  3221  3359 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:16:09.637  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:09.637  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:09.637  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:10.577   290   290 E SMD     : DCD OFF,
,09-06 19:16:11.547  1017  1306 E Watchdog: !@Sync 3
,09-06 19:16:12.647   325   325 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 19:16:12.647   325   325 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 19:16:12.677  1017  1096 V AlarmManager: waitForAlarm result :4,
,09-06 19:16:12.677  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-06 19:16:12.677  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-06 19:16:12.687  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
09-06 19:16:12.687  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-06 19:16:12.697  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-06 19:16:12.697  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 19:16:12.707  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-06 19:16:12.707  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,09-06 19:16:12.717  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:12.717  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-06 19:16:12.717  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,09-06 19:16:12.727  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:12.757  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:12.757  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:12.767  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:12.857  1017  1030 I art     : Explicit concurrent mark sweep GC freed 24277(1432KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 2.387ms total 163.244ms
,09-06 19:16:12.957  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:16:12.957  6825  6992 I jxcore-log: 
,09-06 19:16:12.957  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:16:12.957  6825  6992 I jxcore-log: 
,09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:12.967  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:12.967  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:12.967  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:16:12.967  6825  6992 I jxcore-log: 
,09-06 19:16:12.967  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:16:12.967  6825  6992 I jxcore-log: 
,09-06 19:16:13.087  6041  6152 D Finsky  : [1104] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-06 19:16:13.087  6041  6041 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-06 19:16:13.577   290   290 E SMD     : DCD OFF
,09-06 19:16:13.647  6825  6992 D executeNativeTests: Running unit tests
,09-06 19:16:13.737  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:13.737  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 added. We now have 2 listener(s)
,09-06 19:16:13.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:13.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:13.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:13.737  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:13.737  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 added. We now have 2 listener(s)
09-06 19:16:13.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:13.737  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:13.737  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.737  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.747  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.747  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:13.747  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:16:13.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:13.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:13.747  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.747  6825  6992 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:16:13.747  6825  6992 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:13.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:13.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:13.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:16:13.757  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.757  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.757  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.757  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:13.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 removed from the list
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 removed from the list
09-06 19:16:13.757  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.757  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.757  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:13.757  6825  6992 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:16:13.757  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.757  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.757  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.757  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.757  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.757  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:13.757  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.757  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.757  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.757  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:13.767  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.767  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.767  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.767  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.767  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.767  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.767  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:13.767  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.767  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:13.767  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.767  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.767  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.767  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:13.767  6825  6992 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:16:13.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.777  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.777  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.777  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:13.777  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:13.777  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:13.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:13.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:13.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:13.777  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.777  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:13.777  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.787  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:13.787  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:13.797  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 19:16:13.797  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:16:13.797  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:16:13.797  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:13.797  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:13.797  3221  3380 D BtGatt.GattService: registerClient() - UUID=de34dcde-5414-4e65-b954-7fccdcdf3fd9
,09-06 19:16:13.847  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=de34dcde-5414-4e65-b954-7fccdcdf3fd9, clientIf=6
,09-06 19:16:13.847  6825  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:13.847  3221  3247 D BtGatt.GattService: start scan with filters
,09-06 19:16:13.857  3221  3357 D BtGatt.ScanManager: handling starting scan,
09-06 19:16:13.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:13.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,09-06 19:16:13.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:13.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:16:13.857  3221  3357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:13.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.867  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.867  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:13.867  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.867  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:13.867  3221  3357 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:13.867  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:16:13.867  3221  3357 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:16:13.867  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:13.877  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:13.877  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.877  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:16:13.877  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:13.877  6825  6992 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:16:13.887  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:13.887  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.887  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:13.887  6825  6992 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:16:13.887  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.887  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:16:13.887  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:16:13.887  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:13.887  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:16:13.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:16:13.897  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:16:13.897  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:13.897  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:16:13.897  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:13.897  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.897  3221  3247 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:13.897  3221  3357 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:13.897  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:16:13.907  3221  5334 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:13.907  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:13.907  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:13.907  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:13.907  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.907  3221  3357 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:16:13.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:16:13.917  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:13.917  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:13.917  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:13.917  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.917  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:13.917  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.917  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:13.917  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:13.917  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:13.917  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.917  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:13.917  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:13.917  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:13.917  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.917  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.917  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:13.917  6825  6992 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:16:13.927  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.927  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:16:13.927  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.927  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.927  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.937  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:13.937  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.937  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.937  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:16:13.937  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:13.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:13.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:13.947  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:13.947  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:13.947  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:13.947  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:13.947  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:13.947  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:13.957  3221  3380 D BtGatt.GattService: registerClient() - UUID=a9f27963-e901-4cb9-9265-acee33ebf6f3
,09-06 19:16:13.997  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=a9f27963-e901-4cb9-9265-acee33ebf6f3, clientIf=6
,09-06 19:16:13.997  6825  6839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:13.997  3221  3247 D BtGatt.GattService: start scan with filters
,09-06 19:16:13.997  3221  3357 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:13.997  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:16:13.997  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:16:14.007  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:14.007  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:14.007  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:14.007  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.007  3221  3357 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:14.007  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:16:14.007  3221  3357 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:16:14.007  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:14.007  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:14.017  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:14.017  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:14.017  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.017  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:14.017  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:14.017  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:14.027  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:14.027  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.027  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:16:14.027  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.037  6825  6992 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:16:14.037  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:14.037  6825  6992 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:14.037  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.037  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:14.037  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:14.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:14.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:14.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:14.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:14.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:14.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:14.037  3221  3247 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:14.037  3221  3357 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:14.037  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:16:14.047  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:14.047  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:14.047  3221  3357 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:14.047  3221  3297 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:14.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:14.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:14.047  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:14.047  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:14.047  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:14.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:14.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:14.047  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:14.047  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.057  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:14.057  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:14.057  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:14.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.057  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:14.057  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:14.057  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:14.057  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.057  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.057  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.057  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:14.057  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:14.057  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.057  6825  6992 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:16:14.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:14.067  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:14.067  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:14.067  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:14.077  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:14.077  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:14.077  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:14.077  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:14.077  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:14.077  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.077  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.077  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:14.087  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:14.087  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:14.087  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:14.087  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:14.087  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:14.087  3221  3247 D BtGatt.GattService: registerClient() - UUID=87c7938d-7919-41f4-9455-1993126005ae
,09-06 19:16:14.137  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=87c7938d-7919-41f4-9455-1993126005ae, clientIf=6
,09-06 19:16:14.137  6825  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:14.137  3221  3297 D BtGatt.GattService: start scan with filters
,09-06 19:16:14.137  3221  3357 D BtGatt.ScanManager: handling starting scan
09-06 19:16:14.137  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:14.137  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:14.137  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:14.137  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:14.137  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:14.137  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:16:14.137  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:14.137  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:16:14.137  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:14.137  3221  3357 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:14.137  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:14.137  3221  3357 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:16:14.137  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:14.147  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:14.147  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.147  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:14.147  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:14.147  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:14.147  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.157  6825  6992 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:16:14.157  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.157  6825  6992 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:14.157  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.157  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:14.157  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.157  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:14.157  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:14.157  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:14.157  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:14.157  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:14.157  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:14.157  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:14.157  3221  3235 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:14.157  3221  3380 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:14.157  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:16:14.157  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.157  3221  3357 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:14.167  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:14.167  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:16:14.167  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:16:14.167  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:16:14.167  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:14.167  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.167  3221  3357 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:14.167  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:14.177  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:14.177  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:14.177  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:14.177  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:14.177  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:14.177  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.177  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:16:14.177  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:14.177  6825  6992 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:16:14.177  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:14.187  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.187  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.187  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.187  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:14.187  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.187  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.187  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.187  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.187  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:14.187  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.187  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:14.187  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.187  6825  6992 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-06 19:16:14.187  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:14.187  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.187  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:14.187  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:14.197  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.197  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.197  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.197  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.197  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.197  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:14.197  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.197  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.197  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:14.197  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.197  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.197  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.197  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.197  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.197  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-06 19:16:14.197  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:14.197  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.197  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:14.197  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.197  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.197  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.197  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:14.207  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.207  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.207  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.207  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.207  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.207  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.207  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.207  6825  6992 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:16:14.207  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.207  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:14.207  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.207  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.207  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.207  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.207  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.207  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.207  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.207  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.207  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.207  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.207  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.207  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.217  6825  6992 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:16:14.217  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.217  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.217  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.217  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:16:14.217  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:14.217  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:14.217  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:14.217  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.217  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.217  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.217  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.217  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.217  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.217  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.217  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
,09-06 19:16:14.217  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:16:14.217  6825  6992 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:14.217  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-06 19:16:14.227  6825  6992 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:16:14.227  6825  6992 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:14.227  6825  6992 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:14.227  6825  6992 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:14.227  6825  6992 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:16:14.227  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.227  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.227  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.227  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.227  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.227  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:16:14.227  6825  7111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1344)
09-06 19:16:14.227  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.227  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.227  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.227  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.227  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.227  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.227  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.227  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.237  6825  7112 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1344
09-06 19:16:14.237  6825  7111 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 19:16:14.237  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.237  6825  7111 D BluetoothSocket: connect(): myUserId = 0
09-06 19:16:14.237  6825  7111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:14.237  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.237  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.237  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.237  6825  6992 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  3221  3380 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  7111 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:16:14.247  6825  6992 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:14.247  6825  6992 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:14.247  6825  6992 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:14.247  6825  6992 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:16:14.247  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.247  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.247  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.247  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.247  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.247  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.247  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.257  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.257  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.257  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.257  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.257  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:14.257  6825  6825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:16:14.257  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
,09-06 19:16:14.257  6825  6825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.257  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:14.257  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.257  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.267  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.267  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:14.267  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.267  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.267  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.267  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  7113 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.267  6825  6992 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:16:14.267  6825  6992 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:14.267  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:14.267  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.267  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.267  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.267  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.267  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.267  6825  7113 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:16:14.267  6825  6825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.267  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.267  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.277  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.277  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.277  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.277  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.277  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:14.277  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:14.277  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6da91 not in the list
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.277  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:14.277  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:14.277  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:14.277  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd96df6 not in the list
09-06 19:16:14.287  6825  6992 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:14.287  6825  6992 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:14.287  6825  6992 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:16:14.287  6825  6992 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:14.287  6825  6992 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:14.287  6825  6992 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:16:14.287  6825  6992 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection, with peer with ID outgoing
09-06 19:16:14.287  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:14.287  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a1003e8 added. We now have 2 listener(s)
09-06 19:16:14.287  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:14.297  6825  6992 D BluetoothAdapter: enable()
09-06 19:16:14.297  6825  6992 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:16:14.297  1017  1473 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:16:14.297  1017  1473 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:14.297  1017  1473 D SecContentProvider2: mCursor = null
09-06 19:16:14.297  1017  1473 D WifiService: setWifiEnabled: true pid=6825, uid=10170
09-06 19:16:14.297  1017  1473 W ActivityManager: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:14.307  1017  1473 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:16:14.307  1017  1473 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:14.307  1017  1473 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:14.307  1017  1473 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:14.307  1017  1473 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:14.307  1017  1473 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:14.307  1017  1473 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:14.307  1017  1473 D SettingsProvider: name = wifi_on
,09-06 19:16:14.307  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:14.307  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7728a01 added. We now have 3 listener(s)
09-06 19:16:14.307  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:14.307  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:14.307  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9740a6 added. We now have 4 listener(s)
09-06 19:16:14.307  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:14.317  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:14.317  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f7d4ae7 added. We now have 5 listener(s)
09-06 19:16:14.317  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:14.317  1017  1487 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:14.317  1017  1487 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:14.317  1017  1487 D SecContentProvider2: mCursor = null
,09-06 19:16:14.317  1017  1487 D WifiService: setWifiEnabled: false pid=6825, uid=10170
,09-06 19:16:14.317  1017  1487 D SettingsProvider: name = wifi_on
,09-06 19:16:14.327  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:16:14.327  1373  1373 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:14.327  1373  1373 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
09-06 19:16:14.327  1373  1373 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:14.327  1373  1373 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-06 19:16:14.327  6825  6992 D BluetoothAdapter: disable()
,09-06 19:16:14.337  1017  1029 D SettingsProvider: name = bluetooth_on
,09-06 19:16:14.337  3221  3293 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:16:14.337  3221  3293 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:14.337  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:14.337  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:14.337  3221  3293 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:16:14.337  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:14.337  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.347  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.347  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.347  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.347  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:16:14.347  3221  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:14.347  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:16:14.347  3221  3293 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:16:14.347  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.347  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:14.347  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.347  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.347  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.347  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c2e66e2, channel: 19, state: LISTENING
09-06 19:16:14.347  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c2e66e2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@303c508a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27e6da73mSocket: android.net.LocalSocket@3bcc3d30 impl:android.net.LocalSocketImpl@33badda9 fd:FileDescriptor[80]
09-06 19:16:14.347  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bcc3d30 impl:android.net.LocalSocketImpl@33badda9 fd:FileDescriptor[80]
,09-06 19:16:14.347  3221  3293 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:16:14.347  3221  3293 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:16:14.347  1017  1473 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:16:14.357  3221  3293 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:16:14.357  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.357  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:16:14.367  1180  1180 D BluetoothTile:  onBluetoothStateChange:,
,09-06 19:16:14.367  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:14.367  1373  1373 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
09-06 19:16:14.367  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.367  1017  1126 E WifiNative-wlan0: do suspend true
,09-06 19:16:14.367  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null,
,09-06 19:16:14.367  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:14.367  1180  1180 D BluetoothTile:  getBluetoothState : 13
09-06 19:16:14.367  1017  1125 D WifiP2pService: InactiveState{ what=147461 }
,09-06 19:16:14.367  1017  1125 D WifiP2pService: P2pEnabledState{ what=147461 },
09-06 19:16:14.367  1017  1125 D WifiP2pService: DefaultState{ what=147461 }
,09-06 19:16:14.367  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
,09-06 19:16:14.377  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:14.377  1017  1367 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:14.377  1017  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:14.377  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:14.377  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:14.387  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:14.387  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.387  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:14.387  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:14.387  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:14.387  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:14.387  3221  3296 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:16:14.397  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:16:14.397  3221  3293 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:16:14.397  3221  3293 E bt-btif : cmd socket is not created
09-06 19:16:14.397  6825  7111 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@117cc53d, channel: -1, state: INIT
,09-06 19:16:14.397  3221  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-06 19:16:14.397  3221  5280 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:14.397  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.397  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:14.397  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:14.397  3221  3293 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:16:14.397  6825  7111 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@117cc53d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@66c132, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1949ae83mSocket: android.net.LocalSocket@33dd6800 impl:android.net.LocalSocketImpl@3af57839 fd:FileDescriptor[106]
09-06 19:16:14.397  6825  7111 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33dd6800 impl:android.net.LocalSocketImpl@3af57839 fd:FileDescriptor[106]
,09-06 19:16:14.397  6825  7111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1344)
,09-06 19:16:14.397  1017  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:16:14.397  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.397  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:14.397  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:16:14.397  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:14.397  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.407  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.407  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.407  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.407  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:14.407  3221  3298 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-06 19:16:14.407  3221  3298 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-06 19:16:14.407  3221  3298 W bt-btif : invalid rfc slot id: 4
,09-06 19:16:14.407  4808  4808 D BluetoothPbap: Proxy object disconnected
,09-06 19:16:14.407  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@fd00f2e, channel: 5, state: LISTENING
09-06 19:16:14.407  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@fd00f2e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ef486fb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@bcaaacfmSocket: android.net.LocalSocket@306ffc5c impl:android.net.LocalSocketImpl@9baab65 fd:FileDescriptor[82]
09-06 19:16:14.407  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@306ffc5c impl:android.net.LocalSocketImpl@9baab65 fd:FileDescriptor[82]
09-06 19:16:14.407  4808  4808 D PbapServerProfile: Bluetooth service disconnected
09-06 19:16:14.407  3221  3221 I BtOppRfcommListener: stopping Accept Thread
09-06 19:16:14.407  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39d1f03a, channel: 12, state: LISTENING
09-06 19:16:14.407  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@39d1f03a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3889b3ad, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c7124ebmSocket: android.net.LocalSocket@e2e8248 impl:android.net.LocalSocketImpl@12f98e1 fd:FileDescriptor[85]
09-06 19:16:14.407  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e2e8248 impl:android.net.LocalSocketImpl@12f98e1 fd:FileDescriptor[85]
,09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:14.417  3221  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:14.417  3221  5280 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:16:14.417  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:14.417  4808  4808 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:14.417  3221  3221 V BluetoothOppManager: cleanUp...
,09-06 19:16:14.427  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:14.427  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.427  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:16:14.427  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:16:14.427  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:14.427  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:16:14.427  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:14.427  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.427  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:14.427  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:14.447  7118  7118 E Zygote  : MountEmulatedStorage()
09-06 19:16:14.447  1017  1136 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7118 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-06 19:16:14.447  7118  7118 E Zygote  : v2
09-06 19:16:14.447  7118  7118 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:16:14.447  7118  7118 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:14.447   277   983 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:14.447  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:14.447  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:14.457  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:14.457  2642  2679 V NativeCrypto: Read error: ssl=0xb77e0438: I/O error during system call, Connection timed out
,09-06 19:16:14.457  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.457  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:14.457  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:16:14.457  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
09-06 19:16:14.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.457  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.457  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.467  2642  2679 V NativeCrypto: SSL shutdown failed: ssl=0xb77e0438: I/O error during system call, Broken pipe
,09-06 19:16:14.467  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-06 19:16:14.467  1017  1367 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-06 19:16:14.467  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.467  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:14.467  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:16:14.467  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.467  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-06 19:16:14.467  1017  1726 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.467  1017  1726 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,09-06 19:16:14.477  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:16:14.477  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:16:14.477  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 19:16:14.477  1017  1726 I qtaguid : Untagging socket 353,
09-06 19:16:14.477  1017  1726 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.477  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:16:14.477  1017  1017 D RttService: SCAN_AVAILABLE : 1
,09-06 19:16:14.477  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.477  1017  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:14.487  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.487  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:14.487  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.497  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:14.497  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:14.497  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:16:14.497  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:16:14.497  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:16:14.497  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:16:14.497  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:16:14.497  1017  1048 D WifiDisplayController: disconnect
,09-06 19:16:14.497  1017  1048 D WifiDisplayController: updateConnection
09-06 19:16:14.497  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:14.497  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-06 19:16:14.507  1017  1125 D WifiP2pService: P2pDisablingState
09-06 19:16:14.507  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:16:14.507  1017  1125 D WifiP2pService: p2p socket connection lost
09-06 19:16:14.507  1017  1125 D WifiP2pService: P2pDisabledState
,09-06 19:16:14.507  1017  1126 E WifiNative-wlan0: do suspend true,
,09-06 19:16:14.507  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:16:14.507  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:16:14.507  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:14.507  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-06 19:16:14.507  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:14.507  1017  1473 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:14.507  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:16:14.517  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:14.517  7118  7118 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:14.537  7118  7118 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:16:14.537  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 19:16:14.547  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:16:14.547  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-06 19:16:14.547  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.547  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:16:14.567  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:14.567  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.567  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:14.567  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.567  7118  7118 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:16:14.577   277   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:14.577  7118  7118 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
09-06 19:16:14.577   277   979 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-06 19:16:14.577  7118  7118 D UserAnalysis: Create SecureDbHelper
,09-06 19:16:14.577   277   983 D CommandListener: Clearing all IP addresses on wlan0,
,09-06 19:16:14.577  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:16:14.577  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.577  1017  1128 V NetworkStats: updateIfacesLocked()
09-06 19:16:14.577  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.577  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:14.577  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:14.577  1017  1128 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:14.577  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:16:14.577  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 19:16:14.577  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.577  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:14.577  1373  1373 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:14.587  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.587  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-06 19:16:14.597  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.597  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.597  7118  7118 D IntelligenceServiceApplication: onCreate()
,09-06 19:16:14.597  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:16:14.597  1180  1755 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:16:14.597  1017  1726 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.597  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:14.597  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:16:14.597  1457  1457 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:14.607  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:16:14.607  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:14.607  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:14.607  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:16:14.607  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-06 19:16:14.607  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:16:14.607  7118  7118 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:16:14.607  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:14.607  1017  1487 I ActivityManager: Killing 6747:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.617  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.617  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:16:14.617  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:16:14.617  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:14.617  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.617  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:14.617  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:16:14.617  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.617  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.617  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:14.617  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.617  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:14.617  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:16:14.617  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 19:16:14.617  3221  3293 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:14.617  3221  3293 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:16:14.617  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-06 19:16:14.617  3221  3293 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-06 19:16:14.617  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.617  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.617  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:14.617  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:14.617  1180  1180 D HotspotTile: onReceive : 0, 0
09-06 19:16:14.617  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.617  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:14.617  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:14.617  1017  1123 V NetworkStats: updateIfacesLocked()
09-06 19:16:14.617  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.617  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:14.627  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:16:14.627  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.627  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:14.627  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:16:14.627  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.627  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.627  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:16:14.627  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:16:14.627  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:16:14.627  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-06 19:16:14.627  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-06 19:16:14.627  1017  1123 V NetworkStats: performPollLocked() took 8ms
09-06 19:16:14.627  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.627  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.627  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.627  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.627  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:16:14.627  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:14.627  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:14.627  3221  3221 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:16:14.637  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.637  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:14.637  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:16:14.637  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-06 19:16:14.637  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-06 19:16:14.637  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.637  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:16:14.637  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.637  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.637  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.637  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:14.637  1017  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.637  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.637  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.637  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.637  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.637  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:14.647  7140  7140 E Zygote  : MountEmulatedStorage()
,09-06 19:16:14.647  7140  7140 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:16:14.647  7140  7140 E Zygote  : v2
09-06 19:16:14.647  7140  7140 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:14.657  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:14.657  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:14.657  1017  1223 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7140 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
09-06 19:16:14.657  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:14.657  1017  4206 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.657  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.657  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.667  1017  4205 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.657  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.667  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:16:14.657  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.667  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:14.667  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-06 19:16:14.667  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:14.667  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 19:16:14.667  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:16:14.667  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.667  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.667  4808  4808 D HeadsetProfile: Bluetooth service disconnected
09-06 19:16:14.667  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.667  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.667  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.667  3221  3221 D A2dpService: Received stop request...Stopping profile...
09-06 19:16:14.667  3221  3362 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:16:14.677  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:16:14.677  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:14.677  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:16:14.677  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.677  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.677  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:14.677  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.677  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.677  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.677   315   315 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 22.419ms
,09-06 19:16:14.677  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-06 19:16:14.677  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:14.677  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:16:14.677  1017  1017 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:14.677  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 19:16:14.687  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.687  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.687  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:14.687  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.687  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.687  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.687  7140  7140 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:14.687  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.687  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.687  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.697  4808  4808 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:14.697  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.697  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.697  4808  4808 D A2dpProfile: Bluetooth service disconnected
09-06 19:16:14.697  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.697  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.697  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.697  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:16:14.697  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.697  3221  3293 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.697   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 21.269ms
,09-06 19:16:14.697  1017  4206 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.707  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.707  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.707  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.707  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:14.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:14.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:16:14.707  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:14.707  3221  3293 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:16:14.707  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:16:14.707  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:14.707  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:16:14.717  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:14.717  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:16:14.717  3221  3221 D HidService: Received stop request...Stopping profile...
09-06 19:16:14.717  3221  3221 D HidService: Stopping Bluetooth HidService
09-06 19:16:14.717  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:14.717  3221  3221 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:16:14.717  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:14.717  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:14.717  4808  4808 D BluetoothInputDevice: Proxy object disconnected
09-06 19:16:14.717  4808  4808 D HidProfile: Bluetooth service disconnected
09-06 19:16:14.717  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:16:14.717  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:14.717  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:16:14.717   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.564ms
,09-06 19:16:14.717  3221  3221 D HealthService: Received stop request...Stopping profile...
09-06 19:16:14.717  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:14.717  3221  3221 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:14.717  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:16:14.717  3221  3363 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:16:14.717  3221  3221 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:14.717  3221  3221 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-06 19:16:14.717  3221  3221 D PanService: Received stop request...Stopping profile...
09-06 19:16:14.717  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:14.727  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected,
09-06 19:16:14.727  4808  4808 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:16:14.727  4808  4808 D PanProfile: Bluetooth service disconnected
09-06 19:16:14.727  3221  3221 D BluetoothMapService: Received stop request...Stopping profile...,
,09-06 19:16:14.727  1373  1373 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822,
09-06 19:16:14.727  4808  4808 D BluetoothMap: Proxy object disconnected
09-06 19:16:14.727  4808  4808 D MapProfile: Bluetooth service disconnected
09-06 19:16:14.727  3221  3221 D SapService: Received stop request...Stopping profile...
09-06 19:16:14.727  3221  3221 D SapService: Stopping Bluetooth SapService
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:14.727  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:14.727  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:14.727  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:14.727  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:14.727  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:14.727  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.727  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:14.727  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:16:14.737  4808  4808 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:16:14.737  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:16:14.737  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:14.737  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:14.737  3221  3221 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.737  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 19:16:14.737  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:14.737  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:16:14.737  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 19:16:14.737  4808  4808 D SapProfile: Bluetooth service disconnected
,09-06 19:16:14.737  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:16:14.737  3221  3293 D BluetoothAdapterProperties: Setting state to 10
09-06 19:16:14.737  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:14.737  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:14.737  3221  3293 D BluetoothAdapterService: updateAdapterState state is 10
09-06 19:16:14.737  3221  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:14.737  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:16:14.737  3221  3293 I BluetoothAdapterState: Entering OffState
09-06 19:16:14.737  4808  4816 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:14.747  1457  4709 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.747  1457  4709 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.747  6825  6839 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.747  6825  6839 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:16:14.747  6825  6839 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:16:14.747  6825  6839 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:16:14.747  6825  6839 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:16:14.747  6825  6839 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:16:14.747  1442  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.747  1442  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.747  3221  3247 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.747  3221  3247 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
09-06 19:16:14.747  4808  4817 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:16:14.757  4808  4816 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:16:14.757  1431  1441 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 19:16:14.757  1431  1441 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.757  4808  4817 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:16:14.757  4808  4817 D Bluetoothsap: Unbinding service...
,09-06 19:16:14.767  6825  6825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:16:14.767  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:16:14.767  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.767  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.767  4808  4816 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.767  4808  4816 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.767  4808  4817 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:16:14.767  2642  4317 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.767  2642  4317 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:16:14.767  3221  5334 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:14.767  1373  1373 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-06 19:16:14.777  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:14.777  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:14.777  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:14.777  1760  2651 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.777  1760  2651 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.777  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
09-06 19:16:14.777  1180  5834 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.777  1180  5834 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.787  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:16:14.787  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.787  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.787  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.787  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:16:14.787  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:14.787  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.797  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.797  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.797  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.797  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:14.797  1180  1180 D BluetoothTile:  getBluetoothState : 10
,09-06 19:16:14.797  1373  1373 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:16:14.797  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:16:14.797  1373  1373 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:16:14.797  1373  1373 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:16:14.797  1373  1373 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:14.797  1373  1373 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:14.797  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.797  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.797  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:14.797  1017  1131 D Tethering: InitialState.processMessage what=4
,09-06 19:16:14.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-06 19:16:14.797  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.797  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:16:14.797  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.807  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:14.807  1017  1131 E Tethering: No numeric data
09-06 19:16:14.807  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:14.807  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:14.807  1017  1131 D Tethering: clearTetheredNotification()
,09-06 19:16:14.807  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:14.807  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.807  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:14.807  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.807  1017  1367 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:14.807  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.817  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.817  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:14.817  1017  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:14.817  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:16:14.817  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:14.817  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.817  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:14.817  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:16:14.817  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.817  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.817  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:14.817  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.817  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.817  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.817  1017  1123 V NetworkStats: performPollLocked() took 3ms
,09-06 19:16:14.817  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.817  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.817  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.817  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.827  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.827  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.827  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.827  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.827  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.827  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.827  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.827  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,09-06 19:16:14.827  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:16:14.847   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:14.847   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:14.847  7140  7173 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:14.857   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:14.857   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:14.857  7140  7173 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  1017  1759 I ActivityManager: Killing 6763:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  7140  7140 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:15.017  7140  7140 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:15.017  1017  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:15.017  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:15.027  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.027  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.027  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:15.027  1634  1634 I Hs20UtilService: Starting #8
09-06 19:16:15.027  1634  1661 I Hs20UtilService: Message received 5007
09-06 19:16:15.027  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:15.047  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:15.047  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:15.047  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:15.047  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:15.047  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:15.047  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:15.057  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:16:15.057  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:15.057  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:15.057  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:15.057  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:15.057  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:15.067  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:16:15.067  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-06 19:16:15.067  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.067  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.067  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.067  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.077  1373  1373 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:16:15.077  7184  7184 E Zygote  : MountEmulatedStorage()
09-06 19:16:15.077  7184  7184 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:16:15.077  7184  7184 E Zygote  : v2
09-06 19:16:15.077  7184  7184 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.077  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:15.087  1017  1505 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7184 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:15.087  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.087  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.097  7140  7174 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:16:15.107  1373  1373 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 19:16:15.107  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:15.107  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:15.107  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:15.117  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:15.117  7184  7184 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:15.117  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:15.127  1017  1017 I ApplicationPolicy: updateDataUsageMap
,09-06 19:16:15.127  7184  7184 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:16:15.137  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:15.137  1017  1759 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:15.137  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:15.137  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.147  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.147  1017  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:15.147  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:15.157  7184  7184 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:15.167  7184  7184 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:16:15.187  7184  7184 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:15.187  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:16:15.187  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.187  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.187  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.187  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.207  7204  7204 E Zygote  : MountEmulatedStorage()
,09-06 19:16:15.207  7204  7204 E Zygote  : v2
09-06 19:16:15.207  7204  7204 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:16:15.207  7204  7204 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.207  7204  7204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:16:15.207  1017  1505 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7204 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:15.207  7204  7204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.207  1017  1505 I ActivityManager: Killing 6805:com.wsomacp/u0a23 (adj 15): empty #21
09-06 19:16:15.207  7204  7204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.217  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:16:15.217  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:15.217  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.217  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.217  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:15.217  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:15.217  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:16:15.217  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:15.227  1180  1180 D HotspotTile: onReceive : 1, 0
,09-06 19:16:15.227  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:15.227  1760  2202 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:15.227  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.227  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.237  7204  7204 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.237  7204  7204 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.267  7204  7204 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:15.267  1017  1505 I ActivityManager: Killing 6855:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-06 19:16:15.277  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.277  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:15.277  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-06 19:16:15.277  1017  1367 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 19:16:15.277  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.277  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.277  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.277  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.287  7219  7219 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:15.287  7219  7219 E Zygote  : v2
09-06 19:16:15.287  7219  7219 I libpersona: KNOX_SDCARD checking this for 10102
09-06 19:16:15.287  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:15.287  7219  7219 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.287  1017  1367 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7219 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:16:15.287  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:15.297  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.307  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:16:15.307  7219  7219 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.327  7219  7219 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:16:15.517  7219  7239 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 19:16:15.517  7219  7239 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:16:15.517  7219  7239 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-06 19:16:15.517  7219  7239 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:16:15.537  7219  7239 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-06 19:16:15.547  7219  7239 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:16:15.547  7219  7239 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:16:15.547  7219  7239 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:16:15.557  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-06 19:16:15.557  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 19:16:15.557  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.567  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:15.567  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:15.577  7219  7219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:15.587  7219  7219 I Babel_Crash: startup - clean
,09-06 19:16:15.607  1017  1344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:15.607  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:15.617  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.617  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.617  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:15.617  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:15.617  1634  1634 I Hs20UtilService: Starting #9
,09-06 19:16:15.617  1634  1661 I Hs20UtilService: Message received 5007
09-06 19:16:15.617  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:15.617  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:15.617  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:15.617  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:15.617  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:15.627  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:15.627  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:15.627  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:15.637  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.637  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:15.637  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:15.637  7219  7219 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.637  1634  1634 I Hs20UtilService: Starting #10
,09-06 19:16:15.637  1634  1661 I Hs20UtilService: Message received 5011
09-06 19:16:15.637  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:15.637  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:15.637  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:15.637  7219  7219 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:16:15.637  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:15.647  7219  7219 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:16:15.647  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.647  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.647  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.657  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.657  7219  7219 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:16:15.657  7219  7219 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 19:16:15.657  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.657  7219  7219 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 19:16:15.657  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:15.657  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.657  7219  7219 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:16:15.667  7219  7219 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:16:15.667  7219  7219 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:16:15.667  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.667  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.667  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.667  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.667  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.667  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-06 19:16:15.677  7219  7219 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:16:15.677  7219  7219 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:16:15.677  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.677  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.677  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.677  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.677  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.677  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.687  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.687  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-06 19:16:15.687  7219  7219 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:16:15.687  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.687  7219  7219 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:16:15.687  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.687  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.687  7219  7219 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:16:15.697  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.697  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.697  7219  7219 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.697  7219  7219 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:16:15.697  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.697  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.697  7219  7219 W VideoCapabilities: Unsupported mime video/mp43
,09-06 19:16:15.707  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:15.707  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:15.707  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:15.707  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.707  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.707  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:15.707  7219  7219 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:16:15.717  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:15.717  7219  7219 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:16:15.717  4808  4808 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:15.717  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:15.727  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:15.727  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:16:15.737  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:16:15.737  7219  7219 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:16:15.737  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.737  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.737  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.737  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.747  7244  7244 E Zygote  : MountEmulatedStorage()
09-06 19:16:15.747  7244  7244 E Zygote  : v2
09-06 19:16:15.747  7244  7244 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:15.747  7244  7244 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.747  7244  7244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.757  7244  7244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:15.757  7244  7244 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:15.757  1017  1136 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7244 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:15.777  7244  7244 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.777  7244  7244 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.787  7219  7219 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.787  7219  7219 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.797  1017  1045 D Tethering: interfaceRemoved wlan0
09-06 19:16:15.797  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:16:15.797  7219  7219 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.797  7219  7219 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.807  1017  4206 I ActivityManager: Killing 6885:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:16:15.807  7244  7244 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:16:15.807  7244  7244 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:16:15.807  7219  7219 I vclib   : onServiceConnected
09-06 19:16:15.807  7244  7244 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:16:15.817  7244  7244 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 19:16:15.817  7244  7244 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:16:15.817  7244  7244 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:16:15.817  7244  7244 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:15.817  1017  1488 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-06 19:16:15.817  1017  1488 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-06 19:16:15.817  1017  1488 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-06 19:16:15.817  1017  1488 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-06 19:16:15.827  1017  1488 I ActivityManager: Killing 1939:com.google.android.gms/u0a11 (adj 15): empty #21
,09-06 19:16:15.827  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:16:15.827  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.837  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.837  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.837  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.837  7244  7260 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 19:16:15.847  7262  7262 E Zygote  : MountEmulatedStorage()
,09-06 19:16:15.847  7262  7262 E Zygote  : v2
09-06 19:16:15.847  7262  7262 I libpersona: KNOX_SDCARD checking this for 10001
09-06 19:16:15.847  7262  7262 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.847  7262  7262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:15.847  7262  7262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:15.857  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7262 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:15.857  7262  7262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.867  7262  7262 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:15.867  7262  7262 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.947  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:16:15.947  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.947  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.947  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.947  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.957  1017  1505 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7279 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:15.957  7279  7279 E Zygote  : MountEmulatedStorage()
09-06 19:16:15.957  1017  1505 I ActivityManager: Killing 6911:com.osp.app.signin/u0a36 (adj 15): empty #21
09-06 19:16:15.957  7279  7279 E Zygote  : v2
09-06 19:16:15.957  7279  7279 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:15.957  7279  7279 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.957  7279  7279 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.967  1017  1045 D Tethering: interfaceRemoved p2p0,
09-06 19:16:15.967  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:16:15.967  7279  7279 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:15.967  7279  7279 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.977  7279  7279 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.987  7279  7279 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.017  7279  7279 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:16:16.147  7279  7279 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-06 19:16:16.167  7279  7279 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 19:16:16.167  7279  7279 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:16.167  7279  7279 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:16:16.167  7279  7279 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 19:16:16.167  7279  7279 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 19:16:16.177  1017  1367 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 19:16:16.177  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.177  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.177  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.177  1017  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.197  7294  7294 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:16.197  7294  7294 E Zygote  : v2
09-06 19:16:16.197  7294  7294 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:16:16.197  7294  7294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:16.197  7294  7294 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:16.197  1017  1367 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7294 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:16.197  1017  1367 I ActivityManager: Killing 6539:com.android.mms/u0a41 (adj 15): empty #21
,09-06 19:16:16.207  7294  7294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:16.207  7294  7294 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.237  7294  7294 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.237  7294  7294 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.307  1017  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,09-06 19:16:16.317  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.317  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.317  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.317  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.327  1017  1223 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7309 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
09-06 19:16:16.327  1017  1223 I ActivityManager: Killing 6940:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-06 19:16:16.327  7309  7309 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.327  7309  7309 I libpersona: KNOX_SDCARD checking this for 10011
09-06 19:16:16.327  7309  7309 E Zygote  : v2
09-06 19:16:16.327  7309  7309 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:16.337  7309  7309 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.337  7309  7309 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.337  7309  7309 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.347  1017  1136 D CountryDetector: No listener is left
,09-06 19:16:16.367  7309  7309 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.367  7309  7309 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.397  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:16:16.397  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:16:16.427  7309  7309 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-06 19:16:16.427  7309  7309 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-06 19:16:16.437  7309  7309 I MultiDex: VM with version 2.1.0 has multidex support
,09-06 19:16:16.437  7309  7309 I MultiDex: install
09-06 19:16:16.437  7309  7309 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:16:16.547  7309  7309 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-06 19:16:16.577   290   290 E SMD     : DCD OFF,
,09-06 19:16:16.627  7309  7309 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:16:16.627  7309  7309 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@511e5bf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:16:16.627  7309  7309 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:16:16.647  1017  1759 I ActivityManager: Killing 6208:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 19:16:16.647  1017  1473 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-06 19:16:16.647  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.657  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:16.657  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:16.657  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:16.677  7309  7327 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,09-06 19:16:16.707  7309  7322 W art     : Suspending all threads took: 7.507ms
,09-06 19:16:16.717  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:16:16.727  7309  7331 I iu.SyncManager: SYNC; picasa accounts
,09-06 19:16:16.737  7309  7309 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-06 19:16:16.757  1017  4206 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:16.757  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.757  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:16.757  1017  4206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:16.757  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:16.777  7309  7309 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:16:16.807  7309  7309 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-06 19:16:16.807  1017  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-06 19:16:16.807  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-06 19:16:16.807  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-06 19:16:16.807  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=2198)
,09-06 19:16:16.817  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:16:16 GMT+02:00 2016
,09-06 19:16:16.817  1017  3360 D SSRM:n  : SIOP:: AP = 390
,09-06 19:16:16.817  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-06 19:16:16.817  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.817  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:16.817  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:16.817  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:16:16.827  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:16:16.827  1017  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 19:16:16.837  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.837  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.837  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.837  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.847  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:16:16.847  7336  7336 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:16.847  7336  7336 E Zygote  : v2
09-06 19:16:16.847  7336  7336 I libpersona: KNOX_SDCARD checking this for 10031,
,09-06 19:16:16.847  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:16.847  7336  7336 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:16.847  2819  2819 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-06 19:16:16.847  1017  1487 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7336 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:16.857  2819  2819 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-06 19:16:16.857  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:16.857  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:16.857  2819  7335 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:16:16.867  2819  7335 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:16.867  2819  7335 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 19:16:16.877  2819  7335 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 19:16:16.877  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.877  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:16:16.877  7336  7336 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.907  7336  7336 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 19:16:16.917  1017  4205 I ActivityManager: Killing 6958:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 19:16:16.927  1017  1096 V AlarmManager: waitForAlarm result :4
,09-06 19:16:16.937  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:16:16.937  2759  7351 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-06 19:16:16.937  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.937  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.937  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.937  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.937  2759  7351 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:16:16.937  2759  7351 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:16:16.937  2759  7351 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 19:16:16.947  2759  7351 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:16:16.947  7352  7352 E Zygote  : MountEmulatedStorage(),
09-06 19:16:16.947  7352  7352 E Zygote  : v2
09-06 19:16:16.947  7352  7352 I libpersona: KNOX_SDCARD checking this for 10032,
09-06 19:16:16.947  7352  7352 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:16.947  1017  1029 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7352 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:16.957  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.957  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.957  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.987  7352  7352 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.987  7352  7352 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:17.037  7352  7367 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:16:17.037  7352  7367 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:16:17.037  7352  7352 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-06 19:16:17.047  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 19:16:17.047  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.047  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.047  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.047  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.047  7352  7367 D SPPClientService: PushLog.txt file is not deleted.
,09-06 19:16:17.047  7352  7367 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:16:17.047  7352  7367 D SPPClientService: ============PushLog. stop!
,09-06 19:16:17.067  7369  7369 E Zygote  : MountEmulatedStorage(),
09-06 19:16:17.067  7369  7369 E Zygote  : v2
09-06 19:16:17.067  7369  7369 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:16:17.067  7369  7369 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:17.067  7369  7369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:17.067  1017  1136 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7369 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:17.067  1017  1136 I ActivityManager: Killing 6978:com.sec.esdk.elm/u0a90 (adj 15): empty #21,
,09-06 19:16:17.067  1017  1759 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-06 19:16:17.067  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
09-06 19:16:17.067  1017  1759 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:16:17.067  1017  1759 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:16:17.067  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-06 19:16:17.067  7369  7369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:17.077  7369  7369 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-06 19:16:17.097  7352  7377 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
09-06 19:16:17.097  7369  7369 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:17.097  7369  7369 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:17.107   315   315 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 768us total 36.721ms
,09-06 19:16:17.127   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 681us total 20.079ms
,09-06 19:16:17.147  7369  7369 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3027a73b
,09-06 19:16:17.147   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 687us total 20.343ms,
,09-06 19:16:17.157  7369  7369 I SA      : [SSP] onCreated
,09-06 19:16:17.177  7369  7369 I SA      : [TPM] There is no property file
,09-06 19:16:17.177  7369  7369 I SA      : [SCU] isHaveSA() - false
,09-06 19:16:17.177  7369  7369 I SA      : [TPM] getModelProperty : null,
,09-06 19:16:17.177  7369  7369 I SA      : [TPM] getCSCProperty : null
,09-06 19:16:17.177  7369  7369 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-06 19:16:17.187  7369  7369 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-06 19:16:17.187  7369  7369 I SA      : [DM] TFT FEATURE: false
,09-06 19:16:17.187  7369  7369 I SA      : [DM] init START
,09-06 19:16:17.187  7369  7369 I SA      : [DM] This device is not a Vodafone
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-06 19:16:17.197  7369  7369 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-06 19:16:17.207  7369  7369 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-06 19:16:17.217  7369  7369 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-06 19:16:17.217  7369  7369 I SA      : [SCU] isHaveSA() - false
09-06 19:16:17.217  7369  7369 I SA      : support phone number id : false
09-06 19:16:17.217  7369  7369 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:16:17.217  7369  7369 I SA      : [DM] init END
09-06 19:16:17.217  7369  7369 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 19:16:17.227  7369  7369 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 19:16:17.227  7369  7369 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:16:17.227  7369  7369 I SA      : [SLFUCHKMGR] constructor called
,09-06 19:16:17.237  7369  7369 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:16:17.237  7369  7369 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:16:17.237  7369  7369 I SA      : [SCU] == networkStateCheck == false
09-06 19:16:17.237  7369  7369 I SA      : [OR] onReceive END
,09-06 19:16:17.237  1017  1344 I ActivityManager: Killing 7063:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-06 19:16:17.247  1234  1234 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:17.247  1734  1734 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:17.257  2494  2503 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-06 19:16:17.257  1734  1734 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-06 19:16:17.257  1734  1734 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-06 19:16:17.257  1734  1734 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-06 19:16:17.257  1734  1734 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:17.267  1734  1734 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:17.267  1734  1734 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:16:17.267  1017  4206 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 19:16:17.267  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.267  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.267  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.267  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.277  7391  7391 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:17.277  7391  7391 E Zygote  : v2
09-06 19:16:17.277  7391  7391 I libpersona: KNOX_SDCARD checking this for 10077,
09-06 19:16:17.277  7391  7391 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:17.277  1017  4206 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7391 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 19:16:17.287  7391  7391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:17.287  7391  7391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:17.287  7391  7391 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-06 19:16:17.297  7391  7391 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:17.307  7391  7391 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:17.397  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:17.397  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:16:17.407  1017  1030 D SecContentProvider2: mCursor = null
,09-06 19:16:17.407  1017  1030 D WifiService: setWifiEnabled: true pid=6825, uid=10170
,09-06 19:16:17.407  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:17.407  1017  1030 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:16:17.407  1017  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:17.407  1017  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:17.407  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:17.407  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:17.407  1017  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:17.407  1017  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:17.407  1017  1030 D SettingsProvider: name = wifi_on
,09-06 19:16:17.407  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:16:17.537  1017  1367 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 19:16:17.547  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-06 19:16:17.547  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:17.547  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:17.547  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:17.547  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 19:16:17.547  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.547  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.547  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.547  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.557  7410  7410 E Zygote  : MountEmulatedStorage()
09-06 19:16:17.557  1017  1488 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7410 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:17.557  7410  7410 E Zygote  : v2
09-06 19:16:17.567  7410  7410 I libpersona: KNOX_SDCARD checking this for 10110
09-06 19:16:17.567  7410  7410 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:17.567  7410  7410 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:17.567  1017  1473 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 19:16:17.567  7410  7410 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:17.567  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:16:17.567  7410  7410 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:17.567  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:17.567  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:17.567  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:17.577  7219  7409 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 19:16:17.577  1017  1505 I ActivityManager: Killing 7031:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-06 19:16:17.587  7410  7410 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:17.587  7410  7410 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:17.647   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:17.707  1017  1505 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:17.807   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:17.807   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:17.807  7410  7434 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:16:17.817   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:17.817   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:17.817  7410  7434 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:17.827   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:17.827   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:17.827  7410  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:16:17.827   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:17.827   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:17.827  7410  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:17.837  1017  1045 D Tethering: interfaceAdded wlan0
,09-06 19:16:17.837  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:17.837  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:17.837  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:17.837  1017  1131 E Tethering: No numeric data
09-06 19:16:17.837  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:17.837  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:17.837  1017  1131 D Tethering: clearTetheredNotification()
09-06 19:16:17.837  1017  1131 D Tethering: InitialState.processMessage what=4
09-06 19:16:17.837  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:17.837  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:17.847  1017  1131 E Tethering: No numeric data
,09-06 19:16:17.847  1017  1045 D Tethering: interfaceAdded p2p0
,09-06 19:16:17.847  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:16:17.847   277   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 19:16:17.847   277   983 D SoftapController: Softap fwReload - Ok
,09-06 19:16:17.847  7410  7410 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:16:17.847  7410  7410 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:16:17.847  7410  7410 I GAv4    :   adb logcat -s GAv4
09-06 19:16:17.847  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:17.847  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:17.847  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:17.847  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:17.847  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:16:17.847  1017  1131 D Tethering: clearTetheredNotification()
09-06 19:16:17.847  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:17.847  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:17.857  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:17.857  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:16:17.857   277   983 D CommandListener: Setting iface cfg
09-06 19:16:17.857   277   983 D CommandListener: Trying to bring down wlan0
,09-06 19:16:17.857   277   983 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:17.857  1017  1123 V NetworkStats: performPollLocked() took 5ms
09-06 19:16:17.857  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:17.857  1017  1123 V NetworkStats: performPollLocked(flags=0x1),
09-06 19:16:17.857  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:17.857  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:17.857  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:17.857  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:17.857  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:17.857  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:16:17.857  1017  1123 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:17.857  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:17.867  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:17.867  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:17.887  7410  7410 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:16:17.887  1017  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:17.907  7410  7410 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,09-06 19:16:17.917  7410  7439 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:16:17.927  7437  7437 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 19:16:17.927  7437  7437 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:16:17.927  7437  7437 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-06 19:16:17.957  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-06 19:16:17.977  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:17.977  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:17.977  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:16:17.977  1180  1180 D HotspotTile: onReceive : 2, 0
09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:17.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:17.977  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:16:17.977  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:16:17.987  7437  7437 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:16:17.987  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:17.987  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:17.987   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7437
09-06 19:16:17.987   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-06 19:16:17.987  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:17.987  7437  7437 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:16:17.987  7437  7437 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:17.987  7437  7437 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:16:17.987  7437  7437 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:16:17.987   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7437
09-06 19:16:17.987   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-06 19:16:18.177   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-06 19:16:18.187  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-06 19:16:18.207  1017  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:18.207  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:18.207  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:18.207  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:16:18.217  7410  7410 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:16:18.237  7410  7410 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4567-4570)
,09-06 19:16:18.237  7410  7410 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:16:18.237  7437  7437 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:16:18.237  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:16:18.247  7410  7410 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c2e66e2},
09-06 19:16:18.247  7410  7410 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:16:18.247  7410  7410 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:16:18.257  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 19:16:18.257   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7437
09-06 19:16:18.257   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:18.257  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:16:18.257  7437  7437 I wpa_supplicant: ssSupport state is = 1
,09-06 19:16:18.257  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,09-06 19:16:18.257  7437  7437 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-06 19:16:18.257  7437  7437 E wpa_supplicant: SIM READ ERROR
,09-06 19:16:18.257  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:18.257  7437  7437 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:18.257  7437  7437 E wpa_supplicant: SIM READ ERROR,
09-06 19:16:18.257  7437  7437 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:18.257  7437  7437 I wpa_supplicant: wpa_default_ap_write_once,
09-06 19:16:18.257  7437  7437 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-06 19:16:18.257  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:16:18.257  7437  7437 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:16:18.257  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:16:18.257  7437  7437 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:16:18.267  7410  7410 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-06 19:16:18.267  7437  7437 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:18.267  7410  7410 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:18.267  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:16:18.267  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:18.267  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
09-06 19:16:18.267  7410  7410 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:16:18.287  7410  7410 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:16:18.287  7410  7410 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:16:18.287  7410  7410 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:16:18.287  7410  7410 I Adreno-EGL: Local Branch: 
09-06 19:16:18.287  7410  7410 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:16:18.287  7410  7410 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:16:18.287  7410  7410 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:16:18.337  7437  7437 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 19:16:18.337  7410  7469 W cr.media: Requires BLUETOOTH permission
,09-06 19:16:18.347  7410  7410 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:16:18.357  7410  7410 I NSApplication: Starting up...
,09-06 19:16:18.357  1017  4205 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:18.367  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:18.367  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:16:18.367  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:18.367  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:18.367  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:18.367  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:18.377  7474  7474 E Zygote  : MountEmulatedStorage()
,09-06 19:16:18.387  7474  7474 E Zygote  : v2
,09-06 19:16:18.387  7474  7474 I libpersona: KNOX_SDCARD checking this for 10117
09-06 19:16:18.387  7474  7474 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:18.387  7474  7474 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:18.387  1017  1505 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7474 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,09-06 19:16:18.387  7474  7474 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:18.387  7474  7474 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:16:18.387  1017  1505 I ActivityManager: Killing 7082:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-06 19:16:18.407  7474  7474 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:18.407  7474  7474 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:18.427  7474  7474 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:18.477  7437  7437 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 19:16:18.477  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:16:18.487  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,09-06 19:16:18.487   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7437
09-06 19:16:18.487   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:18.487  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:16:18.487  7437  7437 I wpa_supplicant: ssSupport state is = 1
,09-06 19:16:18.487  7437  7437 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:16:18.487  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:16:18.497  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,09-06 19:16:18.497   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7437
09-06 19:16:18.497   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:18.497  7437  7437 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:16:18.497  7437  7437 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:18.497  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:18.497  7437  7437 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:18.497  7437  7437 E wpa_supplicant: SIM READ ERROR
09-06 19:16:18.497  7437  7437 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:18.497  7437  7437 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:18.497  7437  7437 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:18.507  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.507  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.507  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:18.507  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.507  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.507  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:18.617  7437  7437 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:16:18.617  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:16:18.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:18.737  7437  7437 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 19:16:18.737  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-06 19:16:18.737  7437  7437 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:18.747  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-06 19:16:18.747  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:18.747  7437  7437 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:16:18.747  7437  7437 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:18.747  7437  7437 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-06 19:16:18.747  7437  7437 E wpa_supplicant: SIM READ ERROR
09-06 19:16:18.747  7437  7437 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:18.787  7437  7437 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:16:18.787  1017  1759 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:16:18.787  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:18.787  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:18.787  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:16:18.787  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:18.797  7437  7437 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:18.797  7499  7499 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:18.807  7499  7499 E Zygote  : v2
09-06 19:16:18.807  7499  7499 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:16:18.807  7499  7499 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:18.807  7499  7499 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:18.807  7499  7499 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:18.807  1017  1759 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7499 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-06 19:16:18.807  1017  1759 I ActivityManager: Killing 6996:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-06 19:16:18.807  7499  7499 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:18.817  1017  1126 D WifiConfigStore: Loading config and enabling all networks ,
,09-06 19:16:18.827  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:18.827  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:18.827  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:18.827  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.827  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:18.827  1180  1180 D HotspotTile: onReceive : 3, 0
09-06 19:16:18.827  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-06 19:16:18.827  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:18.827  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:18.827  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:18.827  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:18.837  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.837  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:18.837  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:18.837  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:18.837  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:18.837  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:18.837  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:18.837  1017  1126 E WifiConfigStore: Not a HS20
,09-06 19:16:18.837  7499  7499 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:18.837  7499  7499 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:18.847  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:16:18.847  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-06 19:16:18.847  7437  7437 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:16:18.847  7437  7437 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:18.847  7437  7437 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:18.847  7437  7437 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:18.847  7437  7437 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:16:18.847  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:16:18.847  7437  7437 I wpa_supplicant: First Scan Start
,09-06 19:16:18.847  7437  7437 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:16:18.857  7219  7219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:18.857  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:16:18.857  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:18.857  1017  1126 I WifiNative-HAL: startHal
09-06 19:16:18.857  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f59488c
09-06 19:16:18.857  1017  1126 I WifiNative-HAL: Could not start hal
,09-06 19:16:18.857  7499  7499 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:18.857  7499  7499 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:16:18.857  7499  7499 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:18.857  1017  1126 E WifiNative-wlan0: do suspend true
,09-06 19:16:18.857  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-06 19:16:18.857  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:16:18.857  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:16:18.857  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:18.857  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:18.857  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:18.857  1017  1126 E WifiNative-wlan0: invaild command id : 215
09-06 19:16:18.857  1017  1151 I WifiNative-HAL: startHal
09-06 19:16:18.857  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e4569bc
09-06 19:16:18.857  1017  1151 I WifiNative-HAL: Could not start hal
09-06 19:16:18.857  1017  1151 E WifiScanningService: could not start HAL
09-06 19:16:18.857  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-06 19:16:18.867  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:18.867   277   983 D CommandListener: Setting iface cfg
09-06 19:16:18.867   277   983 D CommandListener: Trying to bring up p2p0
,09-06 19:16:18.867  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:16:18.867  7437  7437 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:16:18.867  1017  1125 D WifiP2pService: P2pEnablingState
,09-06 19:16:18.867  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 19:16:18.867  7437  7437 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:18.867  1017  1125 D WifiP2pService: P2p socket connection successful
,09-06 19:16:18.867  7437  7437 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:16:18.867  1017  1125 D WifiP2pService: P2pEnabledState
,09-06 19:16:18.867  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:16:18.867  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:18.867  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:18.867  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:18.867  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:18.867  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:16:18.867  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:16:18.867  7499  7499 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:18.867  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:16:18.877  1017  1048 D WifiDisplayController: disconnect
09-06 19:16:18.877  1017  1048 D WifiDisplayController: updateConnection
09-06 19:16:18.877  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:18.877  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:18.877  1017  1126 D SecContentProvider2: mCursor = null
09-06 19:16:18.877  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,09-06 19:16:18.877  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:18.877  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:18.877  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:18.877  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:18.877  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:16:18.877  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-06 19:16:18.877  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:16:18.877  1017  1488 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:18.877  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,09-06 19:16:18.877  7499  7499 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-06 19:16:18.877  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:18.887  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  secondary type: null
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  wps: 0
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  grpcapab: 0
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  devcapab: 0
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  status: 3
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  wfdInfo: null
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  groupownerAddress: null
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  GOdeviceName: null
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  interfaceAddress: 
09-06 19:16:18.887  1017  1048 D WifiDisplayController:  SConnectInfo : null
,09-06 19:16:18.887  7499  7499 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:16:18.887  1017  1223 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-06 19:16:18.887  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:18.887  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:18.887  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:18.887  1017  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-06 19:16:18.907  7518  7518 E Zygote  : MountEmulatedStorage()
,09-06 19:16:18.907  7518  7518 E Zygote  : v2
09-06 19:16:18.907  7518  7518 I libpersona: KNOX_SDCARD checking this for 10141
09-06 19:16:18.907  7518  7518 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:18.907  7518  7518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:18.907  7518  7518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:18.907  1017  1223 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7518 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-06 19:16:18.907  7518  7518 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:18.907  1017  1223 I ActivityManager: Killing 7011:com.android.calendar/u0a131 (adj 15): empty #21
,09-06 19:16:18.917  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:16:18.917  1017  1125 D WifiP2pService: InactiveState
09-06 19:16:18.917  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:16:18.917  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:18.917  7437  7437 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-06 19:16:18.917  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:16:18.917  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:18.927  7518  7518 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:18.927  7518  7518 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:18.947  7518  7518 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:16:18.947  7518  7518 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:18.947  7518  7518 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:16:18.947  7518  7518 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:16:18.987  1017  1223 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.007  1017  1759 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.057  1017  1136 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.057  1017  1344 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.097  1017  1344 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-06 19:16:19.097  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.097  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.097  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.097  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.107  1017  1223 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.117  7541  7541 E Zygote  : MountEmulatedStorage(),
09-06 19:16:19.117  7541  7541 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:16:19.117  7541  7541 E Zygote  : v2
,09-06 19:16:19.117  7541  7541 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:19.117  1017  1367 D RCPManagerService: exchangeData() failure , invalid userId
09-06 19:16:19.117  1017  1344 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7541 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-06 19:16:19.117  7541  7541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:19.127  7541  7541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:19.127  7541  7541 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:16:19.157  1017  1367 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:19.157  1017  4205 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-06 19:16:19.157  7541  7541 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:19.157  7541  7541 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:19.157  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:16:19.157  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.157  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.157  1017  4205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.187  1017  4205 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7556 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-06 19:16:19.187  7556  7556 E Zygote  : MountEmulatedStorage()
,09-06 19:16:19.187  7556  7556 E Zygote  : v2
09-06 19:16:19.187  7556  7556 I libpersona: KNOX_SDCARD checking this for 10009,
,09-06 19:16:19.187  7556  7556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:19.187  7556  7556 I libpersona: KNOX_SDCARD not a persona,
09-06 19:16:19.187  1017  4205 I ActivityManager: Killing 6782:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-06 19:16:19.197  1017  1487 I ActivityManager: Killing 6041:com.android.vending/u0a26 (adj 15): empty #21
,09-06 19:16:19.197  7556  7556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:19.197  7556  7556 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,09-06 19:16:19.227  7556  7556 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:19.227  7556  7556 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:19.357  1017  1505 I art     : Explicit concurrent mark sweep GC freed 65881(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 23MB/34MB, paused 2.374ms total 153.607ms
,09-06 19:16:19.377  7541  7541 D BadgeProvider: onCreate
,09-06 19:16:19.377  7541  7541 D BadgeProvider: DatabaseHelper
,09-06 19:16:19.397  7541  7551 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 19:16:19.407  7541  7551 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-06 19:16:19.407  7541  7551 D BadgeProvider: sendNotify, [notify] : null
09-06 19:16:19.407  7541  7551 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:16:19.407  7541  7551 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:16:19.407  7541  7551 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:16:19.417  1489  1489 D Launcher.Model: reloadBadges entered.
,09-06 19:16:19.427  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-06 19:16:19.427  1017  1344 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 19:16:19.427  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.437  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.457  1017  1136 I ActivityManager: Killing 7184:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-06 19:16:19.467  1017  1367 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:19.467  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:19.467  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.467  1017  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:19.467  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:19.467  1634  1634 I Hs20UtilService: Starting #11
,09-06 19:16:19.467  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:19.477  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:19.477  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:19.477  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:19.477  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:19.477  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.477  1017  4206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.477  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.487  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-06 19:16:19.487  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.487  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.487  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.487  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.487  1017  1498 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,09-06 19:16:19.487  1017  1498 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-06 19:16:19.487  1017  1498 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,09-06 19:16:19.487  1017  1498 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-06 19:16:19.487  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.487  1017  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.487  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.497  2642  5119 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-06 19:16:19.507  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.507  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.507  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.507  2642  2642 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 19:16:19.517  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.517  1017  4205 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.517  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.517  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-06 19:16:19.517  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.517  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.517  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.517  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.527  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.527  1017  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.527  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.527  2642  2642 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:16:19.527  2642  2642 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:16:19.537  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.537  1017  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.537  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.537  7309  7309 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-06 19:16:19.547  1017  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:19.547  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.547  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.547  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:19.547  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.547  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.547  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:19.547  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.557  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.557  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.557  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.557  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.567  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.567  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.567  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.567  1017  4206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.567  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.567  1017  1344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:19.577  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.577  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.577  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.577  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.577  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.577  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.577  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:16:19.577   290   290 E SMD     : DCD OFF
,09-06 19:16:19.587  7574  7574 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:19.587  7574  7574 E Zygote  : v2
09-06 19:16:19.587  7574  7574 I libpersona: KNOX_SDCARD checking this for 10011
09-06 19:16:19.587  7574  7574 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:19.587  7574  7574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:19.587  1017  1344 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7574 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-06 19:16:19.597  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.597  1017  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.597  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.597  7574  7574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:19.597  7574  7574 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:19.627  7574  7574 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:19.627  7574  7574 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:19.637  7574  7574 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:16:19.637  7574  7574 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:16:19.647  1017  4205 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:19.657  1017  4205 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4176, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:16:19.657  1017  4205 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:16:19.657  1017  4205 D BatteryService: stay LED for charging
09-06 19:16:19.657  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:19.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:19.657  1017  1017 I MotionRecognitionService: Plugged
09-06 19:16:19.657  1457  1475 D TP/SmsProvider: query,matched:0, calling pid = 7309
09-06 19:16:19.657  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
09-06 19:16:19.657  1457  1475 D TP/SmsProvider: match 0:Elapsed time : 1.289 ms
,09-06 19:16:19.657  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:16:19.657  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:16:19.667  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:16:19.667  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-06 19:16:19.667  7574  7574 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-06 19:16:19.667  7574  7574 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-06 19:16:19.677  7574  7574 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:16:19.677  7574  7574 I MultiDex: install
09-06 19:16:19.677  7574  7574 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:16:19.687  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.687  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.687  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.687  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.687  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:19.687  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.697  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:19.697  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-06 19:16:19.697  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:19.697  1017  1223 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:19.697  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.697  1017  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.697  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.697  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.697  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.697  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.707  1457  1471 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7309
,09-06 19:16:19.717  7574  7574 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-06 19:16:19.717   277   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:19.717   277   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-06 19:16:19.727  1017  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:19.727  1457  1475 D TP/SmsProvider: query,matched:0, calling pid = 7309
09-06 19:16:19.727  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:19.727  1457  1475 D TP/SmsProvider: match 0:Elapsed time : 0.935 ms
,09-06 19:16:19.727  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.727  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:19.727  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:19.727  1017  1344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:19.727  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-06 19:16:19.727  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.727  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.727  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.727  7309  7593 D LocationInitializer: Restart initialization of location
,09-06 19:16:19.737  1634  1634 I Hs20UtilService: Starting #12
,09-06 19:16:19.737  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:19.737  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:19.737  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:19.737  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:19.737  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:19.747  1457  1471 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7309
,09-06 19:16:19.747  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:19.747  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.747  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.747  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.747  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.757  1017  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:19.757  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:19.757  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.757  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:19.757  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:19.767  1634  1634 I Hs20UtilService: Starting #13
,09-06 19:16:19.767  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:19.767  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-06 19:16:19.767  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:19.767  1017  1126 E WifiNative-wlan0: invaild command id : 215
09-06 19:16:19.767  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:19.767  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.767  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.777  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:19.777  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:19.777  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:19.777  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:19.777  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.787  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:16:19.797  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:19.797  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:19.797  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:19.797  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:19.797  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:19.797  7574  7574 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:16:19.797  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:19.797  7574  7574 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24610bdf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-06 19:16:19.797  7574  7574 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:16:19.797  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-06 19:16:19.807  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.807  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.807  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:19.807  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:19.817  7597  7597 E Zygote  : MountEmulatedStorage(),
09-06 19:16:19.817  7597  7597 E Zygote  : v2
09-06 19:16:19.817  7597  7597 I libpersona: KNOX_SDCARD checking this for 10064,
09-06 19:16:19.817  7597  7597 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:19.817  7597  7597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:19.827  7597  7597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:19.827  7597  7597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:19.827  1017  1030 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7597 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:19.847  7597  7597 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:19.847  7597  7597 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:19.847  7574  7574 D WearableService: callingUid 10011, callindPid: 7574
,09-06 19:16:19.877  7574  7606 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0,
,09-06 19:16:19.897  1760  5049 E MDM     : [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-06 19:16:19.897  7597  7597 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:16:19.907  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:19.907  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:16:19.937  7597  7597 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:19.937  7204  7204 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:19.947  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.947  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.947  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-06 19:16:19.947  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.947  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.947  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.957  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-06 19:16:19.957  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.957  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.957  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.957  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.957  1017  1473 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,09-06 19:16:19.957  1017  1473 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-06 19:16:19.957  1017  1473 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,09-06 19:16:19.957  1017  1473 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-06 19:16:19.957  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.957  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.957  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.967  2642  2669 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-06 19:16:19.967  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.967  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.967  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.967  2642  2642 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 19:16:19.967  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.967  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.967  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.977  1017  1344 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms,
09-06 19:16:19.977  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.977  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
09-06 19:16:19.977  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.977  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.977  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.977  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.977  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.987  2642  2642 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-06 19:16:19.987  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.987  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.987  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.987  7309  7309 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-06 19:16:19.987  1017  1223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:19.987  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-06 19:16:19.987  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.987  1017  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.987  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.997  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.997  1017  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.997  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:19.997  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.997  1017  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:19.997  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.007  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.007  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.007  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.007  1760  5121 E MDM     : [193] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
,09-06 19:16:20.007  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.007  1017  4206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
09-06 19:16:20.007  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.017  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.017  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.017  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.027  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.027  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.027  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.027  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.027  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.027  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.027  1017  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:20.027  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.027  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.027  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.037  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:20.037  1017  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.037  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-06 19:16:20.037  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:20.037  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-06 19:16:20.047  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.047  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:20.047  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:16:20.047  7309  7619 D LocationInitializer: Restart initialization of location
,09-06 19:16:20.047  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.047  1017  1759 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:20.047  1017  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:20.047  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
09-06 19:16:20.047  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:20.047  7437  7437 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
09-06 19:16:20.047  7437  7437 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:20.047  7437  7437 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:16:20.047  7437  7437 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:16:20.047  7437  7437 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-06 19:16:20.047  1017  7497 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-06 19:16:20.047  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 19:16:20.067  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:16:20.067  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.197  7437  7437 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:16:20.197  7437  7437 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:20.197  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.197  7437  7437 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-06 19:16:20.197  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.197  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:20.197  7437  7437 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:16:20.197  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:16:20.197  7437  7437 I wpa_supplicant: Associated with F4.99.3E
09-06 19:16:20.197  7437  7437 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:20.197  7437  7437 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-06 19:16:20.197  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:20.197  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.197  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.197  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:20.197  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:20.197  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:20.197  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:20.207  1017  1131 E Tethering: No numeric data
09-06 19:16:20.207  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:20.207  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:20.207  1017  1131 D Tethering: clearTetheredNotification()
09-06 19:16:20.207  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.207  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:20.207  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:20.207  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:20.207  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:16:20.207  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:20.207  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.217  1017  1123 V NetworkStats: performPollLocked() took 8ms
09-06 19:16:20.217  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.217  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.217  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.217  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:20.217  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.217  7437  7437 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:20.217  7437  7437 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 19:16:20.227  7437  7437 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 19:16:20.227  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:20.227  7437  7437 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:20.227  7437  7437 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:16:20.227  7437  7437 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-06 19:16:20.227  7437  7437 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:16:20.227  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:20.227  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:20.227  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:16:20.227  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:20.227  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:16:20.237  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:16:20.237  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-06 19:16:20.237  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:16:20.237  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:20.237  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.247  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.247  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:20.247  1017  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:20.247  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:20.247  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.247  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:20.247  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:20.257  1634  1634 I Hs20UtilService: Starting #14
09-06 19:16:20.257  1634  1661 I Hs20UtilService: Message received 5007
,09-06 19:16:20.257  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:20.257  7204  7215 W art     : Suspending all threads took: 6.784ms
09-06 19:16:20.257  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:20.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:20.267  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:20.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:20.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:20.267  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:20.267  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:20.277   277   983 D CommandListener: Setting iface cfg
,09-06 19:16:20.287  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:16:20.287  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:16:20.287  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:20.307  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.317  1017  1126 E WifiNative-wlan0: do suspend false
,09-06 19:16:20.317  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:16:20.317  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:20.317  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:16:20.317  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.417  1017  4206 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:20.417  1017  4206 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:20.417  1017  4206 D SecContentProvider2: mCursor = null
,09-06 19:16:20.417  1017  4206 D WifiService: setWifiEnabled: false pid=6825, uid=10170
,09-06 19:16:20.417  1017  4206 D SettingsProvider: name = wifi_on
,09-06 19:16:20.427  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:20.437  1017  1126 E WifiNative-wlan0: do suspend true
,09-06 19:16:20.457  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:16:20.457  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:20.467   277   983 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:20.467  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:20.467  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:20.467  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:20.467  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-06 19:16:20.467  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:20.467  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.467  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:16:20.467  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.477  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:16:20.467  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:20.477   277   983 E Netd    : no such netId 503
,09-06 19:16:20.477  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,09-06 19:16:20.477  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:16:20.477  1017  1128 V NetworkStats: updateIfacesLocked()
09-06 19:16:20.477  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.477  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:20.477  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:20.477  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:20.487  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:16:20.487  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:20.487  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-06 19:16:20.487  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:20.487  1017  1128 V NetworkStats: performPollLocked() took 11ms
09-06 19:16:20.487  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.497  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-06 19:16:20.497  1017  7621 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:20.497  1017  7621 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-06 19:16:20.497  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:16:20.497  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:16:20.497  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:16:20.497  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:20.497  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.497  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.497  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.497  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.497  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:16:20.497  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.497  1017  1344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:20.497  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.497  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:20.497  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.497  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.497  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:20.497  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:20.507  1634  1634 I Hs20UtilService: Starting #15
,09-06 19:16:20.507  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:20.507  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:20.507  1634  1661 I Hs20UtilService: Message received 5007
,09-06 19:16:20.507  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:16:20.507  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-06 19:16:20.507  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:16:20.507  1017  1048 D WifiDisplayController: disconnect
,09-06 19:16:20.507  1017  1048 D WifiDisplayController: updateConnection
09-06 19:16:20.507  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:20.507  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:20.517  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:20.517  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:20.517  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:20.517  1017  1125 D WifiP2pService: P2pDisablingState
,09-06 19:16:20.517  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:20.517  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:16:20.517  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:20.517  1017  1125 D WifiP2pService: p2p socket connection lost
09-06 19:16:20.517  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:20.517  1017  1125 D WifiP2pService: P2pDisabledState
,09-06 19:16:20.517  1017  1126 E WifiNative-wlan0: do suspend true
09-06 19:16:20.517  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:20.517  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:16:20.517  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:20.517  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:20.517  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:20.527  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:16:20.527  1017  1498 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:20.527  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:20.537  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-06 19:16:20.537  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:20.537  7624  7624 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-06 19:16:20.537  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:20.547  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:20.547  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:20.547  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:20.547  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:20.547  7624  7624 I dhcpcd  : version 5.5.6 starting
,09-06 19:16:20.547  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:20.547  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:20.547  7597  7597 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:20.557  7204  7204 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:20.567  7624  7624 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 19:16:20.567  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 19:16:20.567  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:16:20.567   277   983 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:20.567  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:20.567  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.567  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.567  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.577  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.577  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.577  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.577  7437  7437 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 19:16:20.577  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:16:20.587  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:20.587  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.597  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:20.597  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:20.597  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.597  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:20.597  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:16:20.607  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:20.607  1180  1180 D HotspotTile: onReceive : 0, 0
,09-06 19:16:20.607  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:20.607  1017  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:20.607  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:20.617  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.617  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:20.617  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-06 19:16:20.617  1634  1634 I Hs20UtilService: Starting #16
,09-06 19:16:20.617  1634  1661 I Hs20UtilService: Message received 5007
09-06 19:16:20.617  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:20.617  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:20.627  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:20.627  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:20.627  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:20.627  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:20.627  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:20.627  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:20.627  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:20.637  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:20.637  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:20.637  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:20.637  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:16:20.637  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:20.637  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:20.637  1017  4205 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:20.637  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:20.647  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.647  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:20.647  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:20.647  1634  1634 I Hs20UtilService: Starting #17
09-06 19:16:20.647  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:20.647  7624  7624 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 19:16:20.647  7624  7624 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
09-06 19:16:20.647  7624  7624 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-06 19:16:20.647  7624  7624 I dhcpcd  : bssid match
09-06 19:16:20.647  7624  7624 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-06 19:16:20.657  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
,09-06 19:16:20.657  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:20.657  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:20.657  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,09-06 19:16:20.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:20.727  7624  7624 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-06 19:16:20.807  7624  7624 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-06 19:16:20.817  7437  7437 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:20.907  7437  7437 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:16:20.907  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:20.907  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:20.907  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:20.937  7437  7437 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-06 19:16:20.937  7437  7437 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,09-06 19:16:20.937  7437  7437 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-06 19:16:20.937  7437  7437 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:20.937  7437  7437 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:20.937  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.937  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.937  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:20.937  1017  1131 D Tethering: InitialState.processMessage what=4
,09-06 19:16:20.937  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.947  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.947  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:20.947  1017  1131 E Tethering: No numeric data,
,09-06 19:16:20.947  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:20.947  1017  1131 D Tethering: clearTetheredNotification()
09-06 19:16:20.947  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:20.947  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.947  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:20.947  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:20.947  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:20.947  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:16:20.947  1017  1123 V NetworkStats: performPollLocked() took 4ms,
09-06 19:16:20.947  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.947  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:20.947  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.947  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-06 19:16:20.947  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.947  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:21.187  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:21.187  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:16:21.187  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:21.257  7437  7437 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:21.417  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:16:21.417  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:21.417  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:21.417  7437  7437 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-06 19:16:21.527  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:16:21.527  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:21.527  7219  7219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:21.537  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:21.537  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:21.537  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:16:21.537  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:21.547  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:21.547  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:21.547  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:21.547  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:21.547  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:21.547  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 19:16:21.547  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:21.547  1180  1180 D HotspotTile: onReceive : 1, 0
,09-06 19:16:21.547  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-06 19:16:21.547  1760  2202 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:21.557  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:21.557  1017  4205 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:21.557  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:21.557  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:21.557  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:21.557  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:21.557  1634  1634 I Hs20UtilService: Starting #18
,09-06 19:16:21.557  1634  1661 I Hs20UtilService: Message received 5011
09-06 19:16:21.557  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:21.567  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:21.567  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:16:21.567  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:21.567  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:21.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:21.727  5918  5918 D FactoryTest: Not factory mode
,09-06 19:16:21.727  5918  5918 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:16:21.737  5918  5918 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 19:16:21.737  5918  5918 D MTPRx   : still no open session command from host, so toast
,09-06 19:16:21.737  5918  5918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-06 19:16:21.737  5918  5918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 19:16:21.737  5918  5918 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118079
,09-06 19:16:21.747  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!,
09-06 19:16:21.747  1017  1030 I PersonaManagerService: PersonaId don't exist
,09-06 19:16:21.747  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:16:21.747  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-06 19:16:21.747  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
,09-06 19:16:21.747  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-06 19:16:21.747  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 19:16:21.757  1017  1030 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:16:21.777  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:21.797  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:16:21.797  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:16:21.797  1017  1030 D InputDispatcher: Focused application set to: xxxx
,09-06 19:16:21.797  1017  1030 D InputDispatcher: Focus left window: 6825
,09-06 19:16:21.797  5918  5918 E MTPRx   : started activity for popup
,09-06 19:16:21.797  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:16:21.797  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:21.827  5918  5918 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:21.847  5918  5918 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:16:21.857  1017  1223 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:16:21.857  1017  1223 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:16:21.857  1017  1223 D InputDispatcher: Focused application set to: xxxx
,09-06 19:16:21.857  1017  1223 D InputDispatcher: Focus entered window: 6825
,09-06 19:16:21.857  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:16:21.857  1017  1498 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:16:21.857  1017  1498 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3d411240 attribute=null, token = android.os.BinderProxy@1d280971
,09-06 19:16:21.857  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:21.897  5918  5918 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:16:21.897  5918  5918 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-06 19:16:21.897  5918  5918 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:16:21.917  6825  6825 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:16:21.917  6825  6825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-06 19:16:21.927  6825  6825 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:16:21.927  6825  6825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:16:21.927  1017  4205 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 19:16:21.927  1017  4205 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:16:21.927  1017  4205 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:16:21.927  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:16:21.927  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:16:21.937  6825  6825 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:16:21.937  6825  6825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:16:21.937  6825  6825 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3948d864 time:118279
,09-06 19:16:21.947  6825  6825 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@343d05a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1a3bbe7e, 16908290=android.view.AbsSavedState$1@1a3bbe7e}, android:focusedViewId=100}]}]
09-06 19:16:21.947  6825  6825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:16:21.947  6825  6825 V ActivityThread: updateVisibility : ActivityRecord{1c30ff82 token=android.os.BinderProxy@3948d864 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:16:21.947  6825  6825 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:16:21.947  6825  6825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:16:21.957  1017  4206 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:22.177   277   977 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-06 19:16:22.177  1017  1045 D Tethering: interfaceRemoved wlan0
,09-06 19:16:22.177  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:16:22.357  1017  1045 D Tethering: interfaceRemoved p2p0
,09-06 19:16:22.357  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:16:22.587   290   290 E SMD     : DCD OFF,
,09-06 19:16:22.657   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-06 19:16:23.077  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:16:23.427  6825  6992 D BluetoothAdapter: enable(),
,09-06 19:16:23.427  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:23.437  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:16:23.437  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:23.437  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:23.437  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:23.437  1017  1029 D SettingsProvider: name = bluetooth_on
,09-06 19:16:23.447  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:16:23.447  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:23.447  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:16:23.447  3221  3293 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:16:23.447  3221  3293 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:16:23.447  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 19:16:23.447  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:23.447  3221  3293 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:16:23.447  3221  3293 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:23.447  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-06 19:16:23.447  3221  3293 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:23.447  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:16:23.447  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:23.457  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:23.457  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:23.457  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.457  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:16:23.467  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:23.467  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.467  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-06 19:16:23.467  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:23.467  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:23.467  1017  1473 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:23.477  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
09-06 19:16:23.477  1017  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:23.477  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:23.477  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.477  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.477  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.477  1017  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:23.477  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.487  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.487  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.487  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.487  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:23.487  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:23.487  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:23.487  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.487  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.487  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.487  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.487  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.487  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-06 19:16:23.497  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:23.497  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:23.497  1017  4206 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:23.497  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.497  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.497  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.497  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.497  3221  3221 D HeadsetService: Received start request. Starting profile...
,09-06 19:16:23.497  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:16:23.497  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:23.497  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:16:23.497  3221  3221 D HeadsetService: start()
09-06 19:16:23.497  3221  3221 D HeadsetStateMachine: make
,09-06 19:16:23.497  1017  1759 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.497  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.497  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.497  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.497  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:23.497  3221  3221 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:16:23.507  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-06 19:16:23.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:16:23.507  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:16:23.507  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.507  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.507  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.517  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.517  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.517  1017  4205 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 19:16:23.517  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.517  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:16:23.517  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:23.517  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:23.517  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.517  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.517  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:16:23.527  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:23.527  1017  1223 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-06 19:16:23.527  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.527  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.527  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.527  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:16:23.527  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.527  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.527  3221  3221 I bluedroid: get_profile_interface handsfree
,09-06 19:16:23.527  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.527  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.527  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.527  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:16:23.527  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:23.537  3221  3293 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:23.537  1017  4206 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:23.537  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.537  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:23.537  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.537  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.537  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:23.547  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:23.547  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:23.547  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:23.547  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:23.547  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:23.547  3221  3293 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:16:23.547  3221  3221 E DualScoManager: Dual Sco Manager already instantiated
,09-06 19:16:23.557  3221  3221 I DualScoManager: Set HeadsetServiceHelper
09-06 19:16:23.557  3221  3221 D BluetoothAtMessage: createCMTIContentObservers
09-06 19:16:23.557  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.557  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:16:23.557  1017  4205 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 19:16:23.557  1017  4205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:23.557  1017  4205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:23.557  1017  4205 D SettingsProvider: selectionArgs: false
09-06 19:16:23.557  1017  4205 D SettingsProvider: selectionArgs: 1002
09-06 19:16:23.557  1017  4205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:23.557  1017  4205 D SettingsProvider: ret = -1
,09-06 19:16:23.557  3221  7655 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:16:23.557  3221  3221 D HeadsetService: mStartError = false
,09-06 19:16:23.557  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.557  3221  3221 D A2dpService: Received start request. Starting profile...
,09-06 19:16:23.557  3221  3221 D A2dpService: start()
09-06 19:16:23.557  3221  3221 I bluedroid: get_profile_interface avrcp
,09-06 19:16:23.557  3221  7655 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:16:23.557  3221  7655 D HeadsetStateMachine: map size, before remove : 0
09-06 19:16:23.557  3221  7655 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:16:23.567  3221  3221 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:16:23.567  3221  3221 D Avrcp   : Initialize Media Controller
09-06 19:16:23.567  3221  3221 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:16:23.567  3221  3221 E Avrcp   : getActiveSessions
,09-06 19:16:23.567  3221  3221 D Avrcp   : pick active media Controller
09-06 19:16:23.567  3221  3221 D Avrcp   : Get the active Media Controller 
,09-06 19:16:23.567  3221  3221 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:16:23.577  3221  7656 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:16:23.577  3221  3221 D A2dpStateMachine: make
,09-06 19:16:23.577  3221  3221 I bluedroid: get_profile_interface a2dp
,09-06 19:16:23.577  3221  7658 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:16:23.577  3221  3221 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:16:23.577  3221  3221 D A2dpService: mStartError = false
09-06 19:16:23.577  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.577  3221  7657 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:16:23.577  3221  3221 D HidService: Received start request. Starting profile...
09-06 19:16:23.577  3221  3221 D HidService: start()
09-06 19:16:23.577  3221  3221 I bluedroid: get_profile_interface hidhost
09-06 19:16:23.577  3221  3221 D HidService: setHidService(): set to: null
09-06 19:16:23.577  3221  3221 D HidService: mStartError = false
09-06 19:16:23.577  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.577  3221  3221 D HealthService: Received start request. Starting profile...
09-06 19:16:23.577  3221  3221 D HealthService: start()
,09-06 19:16:23.587  3221  3221 I bluedroid: get_profile_interface health
,09-06 19:16:23.587  3221  3221 D HealthService: mStartError = false
09-06 19:16:23.587  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.587  3221  3221 D PanService: Received start request. Starting profile...
09-06 19:16:23.587  3221  3221 D PanService: start()
09-06 19:16:23.587  3221  3221 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:16:23.587  3221  3221 I bluedroid: get_profile_interface pan
09-06 19:16:23.587  3221  3221 D PanService: mStartError = false
09-06 19:16:23.587  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.587  3221  3221 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:16:23.587  1431  3358 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:16:23.587  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:16:23.587  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:23.587  1431  3358 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:16:23.587  3221  3221 D HeadsetStateMachine: Proxy object connected
,09-06 19:16:23.597  3221  3221 D BluetoothMapService: Received start request. Starting profile...
09-06 19:16:23.597  3221  3221 D BluetoothMapService: start()
,09-06 19:16:23.597  3221  3221 D BluetoothMapService: mStartError = false
09-06 19:16:23.597  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:23.597  3221  3221 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:16:23.597  3221  3221 D SapService: Received start request. Starting profile...
09-06 19:16:23.597  3221  7655 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:23.597  3221  3221 D SapService: start()
09-06 19:16:23.597  3221  3221 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:16:23.597  3221  3221 I bluedroid: get_profile_interface sap
09-06 19:16:23.597  3221  3221 D SapService: mStartError = false
09-06 19:16:23.597  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:23.597  3221  3221 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:16:23.597  3221  3221 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-06 19:16:23.597  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:16:23.597  3221  7655 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:16:23.597  3221  7655 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:16:23.597  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:16:23.597  3221  7655 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:16:23.597  3221  7655 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:23.597  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:16:23.597  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:16:23.597  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:16:23.597  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:16:23.597  3221  7656 D BluetoothMediaBrowser: no now playing list
09-06 19:16:23.597  3221  7656 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:16:23.607  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-06 19:16:23.607  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:16:23.617  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:16:23.617  3221  3293 I bluedroid: enable
,09-06 19:16:23.617  3221  3296 E bt-btif : Calling BTA_HhEnable
09-06 19:16:23.617  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:16:23.617  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:16:23.617  3221  3296 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-06 19:16:23.617  3221  3296 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-06 19:16:23.617  3221  3296 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:16:23.617  3221  3296 I bluedroid: getModelRssiValues
09-06 19:16:23.617  3221  3296 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:16:23.617  3221  3296 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:23.627  1017  1017 D SettingsProvider: name = bluetooth_name
09-06 19:16:23.627  3221  3296 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-06 19:16:23.627  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.627  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.627  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:16:23.627  3221  3296 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:16:23.627  3221  3296 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:23.627  3221  3296 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-06 19:16:23.637  3221  3296 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,09-06 19:16:23.637  3221  3296 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-06 19:16:23.637  3221  3296 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 19:16:23.637  3221  3296 E bt-btif : JVenable fails
,09-06 19:16:23.637  3221  3296 D bte_conf: Device ID record 1 : primary
,09-06 19:16:23.637  3221  3296 D bte_conf:   vendorId            = 0075
09-06 19:16:23.637  3221  3296 D bte_conf:   vendorIdSource      = 0001
,09-06 19:16:23.637  3221  3296 D bte_conf:   product             = 0100
,09-06 19:16:23.637  3221  3296 D bte_conf:   version             = 0200
09-06 19:16:23.637  3221  3296 D bte_conf:   clientExecutableURL = 
,09-06 19:16:23.637  3221  3296 D bte_conf:   serviceDescription  = 
,09-06 19:16:23.637  3221  3296 D bte_conf:   documentationURL    = 
,09-06 19:16:23.637  3221  3296 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:16:23.637  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:16:23.637  3221  3296 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:16:23.637  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:16:23.647  3221  3293 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:23.647  3221  3293 D BluetoothAdapterProperties: State =  11
,09-06 19:16:23.647  1017  1367 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:16:23.647  3221  3293 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:23.647  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:16:23.647  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:23.647  3221  3296 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:23.647  3221  3296 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:23.647  1017  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:16:23.647  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:16:23.647  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:23.647  1017  1030 D SettingsProvider: selectionArgs: false
09-06 19:16:23.647  1017  1030 D SettingsProvider: selectionArgs: 1002
,09-06 19:16:23.647  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:16:23.647  1017  1030 D SettingsProvider: ret = -1
,09-06 19:16:23.647  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 19:16:23.647  3221  3293 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:16:23.657  1017  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.657  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.657  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.657  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.657  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.657  3221  3293 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:23.657  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-06 19:16:23.657  3221  3293 D BluetoothAdapterService: starting service from this receiver
,09-06 19:16:23.657  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.657  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.657  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.657  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.657  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:23.667  7140  7151 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.667  7140  7151 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.667  3221  3293 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:16:23.667  1431  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.667  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.667  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:23.667  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:16:23.667  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.667  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.667  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.667  1431  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:23.667  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:23.667  4808  4817 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:23.677  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:23.677  3221  3221 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:16:23.677  4808  4817 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.677  1017  1487 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:23.677  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:23.677  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.677  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.677  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.677  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.677  3221  7664 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:23.687  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:23.687  4808  4808 D BluetoothA2dp: Proxy object connected
,09-06 19:16:23.687  4808  4808 D A2dpProfile: Bluetooth service connected
,09-06 19:16:23.687  4808  4817 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.687  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:23.687  3221  7664 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:23.687  3221  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:23.687  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.687  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:23.687  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.687  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.687  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.697  3221  7664 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-06 19:16:23.697  3221  7664 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:23.697  3221  7664 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:23.697  3221  7664 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15752f9f
09-06 19:16:23.697  4808  4817 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.697  3221  7664 D BluetoothSocket: channel: 19
09-06 19:16:23.697  4808  7665 D BluetoothPan: Binding service...
,09-06 19:16:23.697  3221  7664 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 19:16:23.697  4808  4808 D HeadsetProfile: Bluetooth service connected
,09-06 19:16:23.697  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:16:23.697  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.697  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.697  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.697  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.697  1457  4709 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.697  1457  4709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.697  4808  4808 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:23.697  4808  4808 D PanProfile: Bluetooth service connected
09-06 19:16:23.697  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:23.697  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.697  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:23.697  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.707  1457  1653 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.707  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
09-06 19:16:23.707  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.707  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:23.707  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.707  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.707  1457  1653 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.707  6825  6839 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.707  6825  6839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.707  1442  1864 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.707  1442  1864 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.707  3221  3380 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.707  3221  3380 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.707  4808  7665 D BluetoothMap: onBluetoothStateChange: up=true,
,09-06 19:16:23.707  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-06 19:16:23.707  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.717  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.717  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.717  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.717  4808  4816 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:16:23.717  4808  4808 D BluetoothMap: Proxy object connected
,09-06 19:16:23.717  4808  4808 D MapProfile: Bluetooth service connected
,09-06 19:16:23.717  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:16:23.717  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.717  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:16:23.717  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.717  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.717  4808  4808 D BluetoothMap: getConnectedDevices()
,09-06 19:16:23.717  1431  3358 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.717  1431  3358 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.717  4808  7665 D Bluetoothsap: onBluetoothStateChange: up=true
,09-06 19:16:23.717  4808  7665 D Bluetoothsap: Binding service...
,09-06 19:16:23.727  4808  4808 D BluetoothInputDevice: Proxy object connected
,09-06 19:16:23.727  4808  4808 D HidProfile: Bluetooth service connected
,09-06 19:16:23.727  4808  7665 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:16:23.727  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 19:16:23.727  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.727  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.727  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.727  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.727  4808  7665 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:16:23.727  1431  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.727  4808  4808 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:16:23.727  4808  4808 D SapProfile: Bluetooth service connected
09-06 19:16:23.727  4808  4808 D Bluetoothsap: getConnectedDevices()
,09-06 19:16:23.727  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.727  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:23.727  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.727  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.727  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.727  1431  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.727  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:16:23.727  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:23.727  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:23.727  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.727  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.727  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:23.727  4808  7665 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.727  4808  7665 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:23.727  1017  1017 D BluetoothA2dp: Proxy object connected
,09-06 19:16:23.727  4808  4817 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:16:23.737  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:16:23.737  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.737  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.737  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.737  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.737  4808  4808 D BluetoothPbap: Proxy object connected
09-06 19:16:23.737  4808  4808 D PbapServerProfile: Bluetooth service connected
,09-06 19:16:23.737  1431  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.737  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:23.737  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:23.737  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.737  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.737  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.737  1431  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.737  2642  2687 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.737  2642  2687 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.737  3221  3235 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:23.737  3221  3235 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.747  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:23.747  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.747  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.747  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.747  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:23.747  3221  3221 D BluetoothA2dp: Proxy object connected
09-06 19:16:23.747  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:16:23.747  1760  1768 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.747  1760  1768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.747  1017  1047 D BluetoothPan: Binding service...
,09-06 19:16:23.747  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:16:23.747  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.747  1180  5834 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:23.747  1180  5834 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.747  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:16:23.747  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:16:23.747  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:16:23.747  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.747  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:16:23.747  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:23.757  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@33db0601, true
,09-06 19:16:23.757  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:16:23.757  1431  1431 D BluetoothHeadset: registerMessageListener
,09-06 19:16:23.757  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.757  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:23.757  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-06 19:16:23.757  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:23.757  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-06 19:16:23.757  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:23.757  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.767  3221  3380 D HeadsetService: registerMessageListener
,09-06 19:16:23.767  3221  3380 D HeadsetService: registerMessageListener
,09-06 19:16:23.767  3221  7655 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:16:23.767  3221  7655 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b61e8ec
,09-06 19:16:23.767  1017  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:23.767  1017  1473 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:16:23.767  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.767  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:16:23.767  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:23.767  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:23.777  3221  7666 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-06 19:16:23.777  4808  4808 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:16:23.777  4808  4808 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:16:23.777  4808  4808 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:16:23.777  4808  4808 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:16:23.777  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.777  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:23.777  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
09-06 19:16:23.777  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 19:16:23.777  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:16:23.777  3221  7655 D HeadsetStateMachine: Disconnected process message: 9
09-06 19:16:23.777  3221  7655 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:16:23.777  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:23.777  3221  7666 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:23.777  1017  1344 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:23.777  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.787  3221  7666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:23.787   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-06 19:16:23.787   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:16:23.787   282   282 V voice   : voice_set_parameters: exit with code(-2)
,09-06 19:16:23.787   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:16:23.787   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-06 19:16:23.787   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:16:23.787   282   282 V audio_hw_primary: adev_set_parameters: exit
,09-06 19:16:23.787  3221  7655 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:16:23.787  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.787  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.787  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:23.797  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:23.797  3221  7666 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-06 19:16:23.797  3221  7666 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:23.797  3221  7666 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:23.797  3221  7666 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3044b5
,09-06 19:16:23.797  3221  7666 D BluetoothSocket: channel: 5
,09-06 19:16:23.797  4808  4808 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:23.807  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:23.807  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.807  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:16:23.817  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:23.817  3221  3221 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:16:23.817  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:23.817  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.817  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.817  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.817  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.827  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:23.837  3221  7671 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:16:23.837  3221  7671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:23.837  3221  7671 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-06 19:16:23.837  3221  7671 D BluetoothSocket: bindListen(), new LocalSocket ,
09-06 19:16:23.837  3221  7671 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:23.837  3221  7671 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ded7731
,09-06 19:16:23.837  3221  7671 D BluetoothSocket: channel: 12
09-06 19:16:23.837  3221  7671 I BtOppRfcommListener: Accept thread started.
,09-06 19:16:24.757  1017  1043 W ActivityManager: mDVFSHelper.release()
,09-06 19:16:25.017  1017  1505 I ActivityManager: Killing 7244:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:16:25.077  1017  1473 I ActivityManager: Killing 7262:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-06 19:16:25.587   290   290 E SMD     : DCD OFF
,09-06 19:16:26.447  6825  6992 D BluetoothAdapter: disable()
09-06 19:16:26.447  1017  1487 D SettingsProvider: name = bluetooth_on
,09-06 19:16:26.457  3221  3293 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-06 19:16:26.457  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.457  3221  3293 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:26.457  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.457  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:26.457  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:26.457  3221  3293 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:16:26.457  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.457  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.457  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.467  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-06 19:16:26.467  3221  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:26.467  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:16:26.467  3221  3293 D BluetoothAdapterService: terminating service from this receiver
09-06 19:16:26.467  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@952de16, channel: 19, state: LISTENING,
09-06 19:16:26.467  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@952de16, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15752f9f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12f77397mSocket: android.net.LocalSocket@365e6984 impl:android.net.LocalSocketImpl@a71556d fd:FileDescriptor[80]
09-06 19:16:26.467  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@365e6984 impl:android.net.LocalSocketImpl@a71556d fd:FileDescriptor[80]
,09-06 19:16:26.467  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.467  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.467  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:26.467  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:26.467  4808  4808 D BluetoothPbap: Proxy object disconnected
09-06 19:16:26.467  4808  4808 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:16:26.467  3221  3293 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:16:26.467  3221  3293 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:16:26.467  1017  1488 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:16:26.467  3221  3293 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:16:26.487  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:26.487  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:26.487  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:26.487  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:26.497  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:26.497  3221  3296 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:16:26.497  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:26.497  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:26.497  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
09-06 19:16:26.497  3221  3293 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:16:26.497  3221  3293 E bt-btif : cmd socket is not created
,09-06 19:16:26.497  3221  3293 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:16:26.497  3221  7671 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:16:26.497  3221  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-06 19:16:26.497  6825  6825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:26.497  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:26.507  3221  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:16:26.517  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.517  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:16:26.517  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:16:26.517  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:26.527  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:26.527  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:26.527  1180  1180 D BluetoothTile:  getBluetoothState : 13
,09-06 19:16:26.527  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:26.527  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:26.527  1017  1498 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:26.527  1017  1759 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:26.537  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:26.537  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:26.537  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.537  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32b5b233, channel: 5, state: LISTENING
,09-06 19:16:26.537  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32b5b233, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3044b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a1a99f0mSocket: android.net.LocalSocket@17dadb69 impl:android.net.LocalSocketImpl@333f99ee fd:FileDescriptor[82]
09-06 19:16:26.537  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17dadb69 impl:android.net.LocalSocketImpl@333f99ee fd:FileDescriptor[82]
,09-06 19:16:26.547  3221  3221 I BtOppRfcommListener: stopping Accept Thread
09-06 19:16:26.547  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f0f3e8f, channel: 12, state: LISTENING
09-06 19:16:26.547  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f0f3e8f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ded7731, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2027651cmSocket: android.net.LocalSocket@13cc525 impl:android.net.LocalSocketImpl@2a8f66fa fd:FileDescriptor[85]
09-06 19:16:26.547  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@13cc525 impl:android.net.LocalSocketImpl@2a8f66fa fd:FileDescriptor[85]
,09-06 19:16:26.547  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.547  3221  7671 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:16:26.547  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.547  3221  3221 V BluetoothOppManager: cleanUp...
,09-06 19:16:26.557  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:26.557  1017  1344 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:26.557  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.557  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.557  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.557  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:26.567  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:26.567  4808  4808 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:26.577  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:26.577  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.577  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:16:26.637  1017  3381 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:16:26.697  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 19:16:26.697  3221  3293 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:26.697  3221  3293 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-06 19:16:26.697  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-06 19:16:26.697  3221  3293 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-06 19:16:26.697  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.697  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:26.697  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:16:26.697  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:26.697  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:16:26.707  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.707  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.707  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-06 19:16:26.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:16:26.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:26.707  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-06 19:16:26.707  1017  4205 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.707  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.707  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.707  3221  3221 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:16:26.707  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.707  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.707  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.707  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-06 19:16:26.707  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:26.707  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:26.717  1017  4206 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.717  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:16:26.717  4808  4808 D HeadsetProfile: Bluetooth service disconnected
09-06 19:16:26.717  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.717  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.717  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.717  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.717  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:16:26.717  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:16:26.717  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:16:26.717  1017  1759 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.717  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.727  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.727  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.727  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.727  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-06 19:16:26.727  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:26.727  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:16:26.727  1017  1367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.727  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.727  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.727  1017  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.727  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.727  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.727  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.727  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.737  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.737  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.737  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.737  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.737  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.737  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.737  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.737  3221  3293 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.737  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.737  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.737  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.737  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.737  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:26.747  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:26.747  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:26.747  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-06 19:16:26.747  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:16:26.747  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:26.747  3221  3293 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:16:26.747  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:16:26.747  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:26.747  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:16:26.747  3221  3221 D A2dpService: Received stop request...Stopping profile...
,09-06 19:16:26.747  3221  7657 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:16:26.757  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.757  1017  1017 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:26.757  4808  4808 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:26.757  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 19:16:26.757  4808  4808 D A2dpProfile: Bluetooth service disconnected
,09-06 19:16:26.757  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:26.757  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:16:26.757  3221  3221 D HidService: Received stop request...Stopping profile...
,09-06 19:16:26.757  3221  3221 D HidService: Stopping Bluetooth HidService
,09-06 19:16:26.757  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:26.757  3221  3221 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:16:26.757  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:26.757  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.757  3221  3221 D HealthService: Received stop request...Stopping profile...
09-06 19:16:26.757  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:26.757  4808  4808 D BluetoothInputDevice: Proxy object disconnected
09-06 19:16:26.757  4808  4808 D HidProfile: Bluetooth service disconnected
,09-06 19:16:26.767  3221  3221 D PanService: Received stop request...Stopping profile...
,09-06 19:16:26.767  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.767  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:16:26.767  3221  3221 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:16:26.767  4808  4808 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:16:26.767  4808  4808 D PanProfile: Bluetooth service disconnected
,09-06 19:16:26.767  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.777  3221  3221 D SapService: Received stop request...Stopping profile...
09-06 19:16:26.777  3221  3221 D SapService: Stopping Bluetooth SapService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:16:26.777  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:16:26.777  3221  7658 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:16:26.777  4808  4808 D BluetoothMap: Proxy object disconnected
09-06 19:16:26.777  3221  3221 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:26.777  3221  3221 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:16:26.777  4808  4808 D MapProfile: Bluetooth service disconnected
09-06 19:16:26.777  3221  3221 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:26.777  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.777  4808  4808 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:16:26.777  4808  4808 D SapProfile: Bluetooth service disconnected
,09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:26.777  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.777  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:26.777  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:16:26.777  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.777  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:26.777  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:16:26.777  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.777  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:16:26.777  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:16:26.787  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:16:26.787  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:16:26.787  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:16:26.787  3221  3293 D BluetoothAdapterProperties: Setting state to 10
09-06 19:16:26.787  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:26.787  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:26.787  3221  3293 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:16:26.787  3221  3293 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:26.787  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,09-06 19:16:26.787  3221  3293 I BluetoothAdapterState: Entering OffState
,09-06 19:16:26.787  7140  7148 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.787  7140  7148 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.787  4808  7665 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.787  1457  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.787  1457  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.797  6825  6839 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.797  6825  6839 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:16:26.797  6825  6839 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 19:16:26.797  6825  6839 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:16:26.797  6825  6839 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:16:26.797  6825  6839 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:16:26.797  1442  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.797  1442  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.797  3221  3380 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.797  3221  3380 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.797  4808  7665 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:16:26.797  4808  4817 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:16:26.797  1431  3358 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.797  1431  3358 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.797  4808  4816 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 19:16:26.797  4808  4816 D Bluetoothsap: Unbinding service...
,09-06 19:16:26.797  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.797  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.797  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.807  4808  7665 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.807  4808  7665 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.807  4808  4817 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:16:26.807  2642  2652 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.807  2642  2652 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.807  3221  3235 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.807  1760  1775 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.807  1760  1775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.807  1180  2060 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.807  1180  2060 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.807  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.807  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,09-06 19:16:26.807  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:26.817  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:26.817  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.817  1180  1180 D BluetoothTile:  getBluetoothState : 10
,09-06 19:16:26.817  1017  1344 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:26.817  1017  1136 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:26.817  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:26.827  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:26.827  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.827  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.827  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.827  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:26.827  1017  4205 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:16:26.837  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:16:26.837  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.837  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.837  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:26.837  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:26.847  4808  4808 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:26.847  1017  3360 D SSRM:n  : SIOP:: AP = 350
,09-06 19:16:26.847  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:26.847  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.847  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:16:27.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:27.737  1017  1096 V AlarmManager: waitForAlarm result :4,
,09-06 19:16:27.747   277   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-06 19:16:27.747   277   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-06 19:16:27.757  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:27.757  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:27.757  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-06 19:16:28.587   290   290 E SMD     : DCD OFF,
,09-06 19:16:28.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:29.457  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:29.457  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:29.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:29.707  1017  1473 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:29.707  1017  1473 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:16:29.707  1017  1473 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:16:29.717  1017  1473 D BatteryService: stay LED for charging
09-06 19:16:29.717  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:29.717  1017  1017 I MotionRecognitionService: Plugged,
09-06 19:16:29.717  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:16:29.717  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,09-06 19:16:29.717  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,09-06 19:16:29.717  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:16:29.717  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,09-06 19:16:29.737  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:29.737  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
09-06 19:16:29.737  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,09-06 19:16:30.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:31.587   290   290 E SMD     : DCD OFF,
,09-06 19:16:31.657   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:32.457  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:32.457  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32eeafdf added. We now have 6 listener(s)
,09-06 19:16:32.457  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:32.467  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:32.467  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb1042c added. We now have 7 listener(s)
,09-06 19:16:32.467  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:32.467  6825  6992 I System.out: IsBluetoothEnabled
,09-06 19:16:32.467  6825  6992 D BluetoothAdapter: disable()
,09-06 19:16:32.467  1017  1473 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 19:16:32.477  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.477  6825  6992 D BluetoothAdapter: enable()
,09-06 19:16:32.477  1017  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:32.477  1017  1505 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:16:32.477  1017  1505 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:32.487  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:16:32.487  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:32.487  1017  1505 D SettingsProvider: name = bluetooth_on
,09-06 19:16:32.487  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:16:32.487  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:32.497  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:16:32.497  3221  3293 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:16:32.497  3221  3293 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:16:32.497  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:16:32.497  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 19:16:32.497  3221  3293 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:16:32.497  3221  3293 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:32.497  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-06 19:16:32.507  3221  3293 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12,
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:32.507  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.507  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:32.507  1017  1017 I InputMethodManagerService: [BT Setting State] State =11,
,09-06 19:16:32.507  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:32.517  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:32.517  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.517  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-06 19:16:32.527  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:32.527  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:32.527  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:32.527  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.527  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.537  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.537  1017  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:32.537  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.537  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.537  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.537  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:32.537  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.537  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.537  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:16:32.537  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:16:32.537  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:32.537  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.547  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.547  3221  3221 D HeadsetService: Received start request. Starting profile...
09-06 19:16:32.547  3221  3221 D HeadsetService: start()
09-06 19:16:32.547  3221  3221 D HeadsetStateMachine: make
,09-06 19:16:32.547  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.547  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.547  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.547  3221  3221 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:16:32.547  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-06 19:16:32.547  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:32.547  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:32.547  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.547  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:16:32.547  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.547  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.547  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.557  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:16:32.557  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:32.557  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:16:32.557  1017  1367 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:16:32.557  1017  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.557  1017  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.557  1017  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.557  1017  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:16:32.557  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:16:32.557  1017  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.557  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-06 19:16:32.557  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.557  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.557  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:32.557  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-06 19:16:32.557  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:32.557  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:16:32.567  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:32.567  1017  1505 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:16:32.567  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.567  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.567  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.567  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:16:32.567  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.567  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.567  3221  3221 I bluedroid: get_profile_interface handsfree
09-06 19:16:32.567  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.567  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.567  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.577  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:32.577  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:32.577  3221  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:32.577  1017  1759 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.577  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.587  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.587  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.587  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:32.587  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:16:32.587  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:32.587  3221  3293 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:32.587  1017  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.587  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.587  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.587  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.587  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.597  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:32.597  3221  3221 E DualScoManager: Dual Sco Manager already instantiated
,09-06 19:16:32.597  3221  3221 I DualScoManager: Set HeadsetServiceHelper
09-06 19:16:32.597  3221  3221 D BluetoothAtMessage: createCMTIContentObservers
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:32.597  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:32.597  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:32.597  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:32.597  3221  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:32.597  3221  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:32.597  3221  3293 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:16:32.597  1017  1223 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:16:32.597  1017  1223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:32.597  1017  1223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:32.597  1017  1223 D SettingsProvider: selectionArgs: false
09-06 19:16:32.597  1017  1223 D SettingsProvider: selectionArgs: 1002
09-06 19:16:32.597  1017  1223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:32.597  1017  1223 D SettingsProvider: ret = -1
,09-06 19:16:32.597  3221  7686 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:16:32.597  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.597  3221  3221 D HeadsetService: mStartError = false
,09-06 19:16:32.597  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:32.597  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:16:32.607  3221  3221 D A2dpService: Received start request. Starting profile...
09-06 19:16:32.607  3221  3221 D A2dpService: start()
,09-06 19:16:32.607  3221  3221 I bluedroid: get_profile_interface avrcp
,09-06 19:16:32.607  3221  7686 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:16:32.607  3221  7686 D HeadsetStateMachine: map size, before remove : 0
09-06 19:16:32.607  3221  7686 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:16:32.607  3221  3221 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:16:32.607  3221  3221 D Avrcp   : Initialize Media Controller
09-06 19:16:32.607  3221  3221 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:16:32.607  3221  3221 E Avrcp   : getActiveSessions
,09-06 19:16:32.607  3221  3221 D Avrcp   : pick active media Controller
09-06 19:16:32.607  3221  3221 D Avrcp   : Get the active Media Controller 
,09-06 19:16:32.617  3221  3221 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:16:32.617  3221  3221 D A2dpStateMachine: make
,09-06 19:16:32.617  3221  7687 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:16:32.617  3221  3221 I bluedroid: get_profile_interface a2dp
,09-06 19:16:32.617  3221  7689 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:16:32.617  3221  3221 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:16:32.627  3221  3221 D A2dpService: mStartError = false
,09-06 19:16:32.627  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:32.627  3221  3221 D HidService: Received start request. Starting profile...
,09-06 19:16:32.627  3221  3221 D HidService: start()
09-06 19:16:32.627  3221  3221 I bluedroid: get_profile_interface hidhost
,09-06 19:16:32.627  3221  3221 D HidService: setHidService(): set to: null
09-06 19:16:32.627  3221  3221 D HidService: mStartError = false
09-06 19:16:32.627  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:32.627  3221  7688 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:16:32.627  3221  3221 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:16:32.627  1431  1458 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:16:32.627  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:16:32.627  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:32.627  1431  1458 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:16:32.637  3221  3221 D HealthService: Received start request. Starting profile...
,09-06 19:16:32.637  3221  3221 D HealthService: start()
,09-06 19:16:32.637  3221  3221 I bluedroid: get_profile_interface health
09-06 19:16:32.637  3221  3221 D HealthService: mStartError = false
09-06 19:16:32.637  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:32.637  3221  3221 D HeadsetStateMachine: Proxy object connected
,09-06 19:16:32.637  3221  3221 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 19:16:32.637  3221  3221 D PanService: Received start request. Starting profile...
09-06 19:16:32.637  3221  7686 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:32.637  3221  3221 D PanService: start()
09-06 19:16:32.637  3221  3221 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:16:32.637  3221  3221 I bluedroid: get_profile_interface pan
09-06 19:16:32.637  3221  3221 D PanService: mStartError = false
09-06 19:16:32.637  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:32.637  3221  3221 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-06 19:16:32.637  3221  7686 D HeadsetStateMachine: Disconnected process message: 18
,09-06 19:16:32.637  3221  3221 D BluetoothMapService: Received start request. Starting profile...
09-06 19:16:32.637  3221  3221 D BluetoothMapService: start()
,09-06 19:16:32.637  3221  3221 D BluetoothMapService: mStartError = false
,09-06 19:16:32.637  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:32.637  3221  3221 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-06 19:16:32.637  3221  3221 D SapService: Received start request. Starting profile...
09-06 19:16:32.637  3221  3221 D SapService: start()
09-06 19:16:32.637  3221  3221 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:16:32.637  3221  3221 I bluedroid: get_profile_interface sap
09-06 19:16:32.637  3221  3221 D SapService: mStartError = false
09-06 19:16:32.637  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
09-06 19:16:32.637  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:16:32.637  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:16:32.647  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:16:32.647  3221  7686 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:16:32.647  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:16:32.647  3221  7686 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:16:32.647  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:16:32.647  3221  7686 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:32.647  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:16:32.647  3221  7687 D BluetoothMediaBrowser: no now playing list
,09-06 19:16:32.647  3221  7687 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:16:32.657  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:16:32.657  3221  3221 E BluetoothAdapterService(585287714): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:16:32.657  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 19:16:32.657  3221  3293 I bluedroid: enable
,09-06 19:16:32.657   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 19:16:32.667  3221  3296 E bt-btif : Calling BTA_HhEnable
,09-06 19:16:32.667  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-06 19:16:32.667  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:16:32.667  3221  3296 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:16:32.667  3221  3296 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-06 19:16:32.667  3221  3296 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:16:32.667  3221  3296 I bluedroid: getModelRssiValues
,09-06 19:16:32.667  3221  3296 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 19:16:32.667  3221  3296 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:32.677  3221  3296 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-06 19:16:32.677  1017  1017 D SettingsProvider: name = bluetooth_name
,09-06 19:16:32.677  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.677  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:16:32.677  3221  3296 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:16:32.677  3221  3296 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:32.677  3221  3296 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-06 19:16:32.677  3221  3296 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-06 19:16:32.677  3221  3296 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-06 19:16:32.677  3221  3296 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 19:16:32.677  3221  3296 E bt-btif : JVenable fails
,09-06 19:16:32.687  3221  3296 D bte_conf: Device ID record 1 : primary
,09-06 19:16:32.687  3221  3296 D bte_conf:   vendorId            = 0075
,09-06 19:16:32.687  3221  3296 D bte_conf:   vendorIdSource      = 0001
,09-06 19:16:32.687  3221  3296 D bte_conf:   product             = 0100
,09-06 19:16:32.687  3221  3296 D bte_conf:   version             = 0200
09-06 19:16:32.687  3221  3296 D bte_conf:   clientExecutableURL = 
,09-06 19:16:32.687  3221  3296 D bte_conf:   serviceDescription  = 
09-06 19:16:32.687  3221  3296 D bte_conf:   documentationURL    = 
09-06 19:16:32.687  3221  3296 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:16:32.687  3221  3296 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:16:32.687  3221  3296 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:16:32.687  3221  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:16:32.687  3221  3293 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:32.687  3221  3293 D BluetoothAdapterProperties: State =  11
,09-06 19:16:32.687  1017  4206 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:16:32.687  3221  3293 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:32.687  3221  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:16:32.687  1017  1344 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:16:32.687  1017  1344 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:32.687  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.687  1017  1344 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:32.687  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 19:16:32.687  1017  1344 D SettingsProvider: selectionArgs: false
09-06 19:16:32.687  1017  1344 D SettingsProvider: selectionArgs: 1002
09-06 19:16:32.687  1017  1344 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:32.687  1017  1344 D SettingsProvider: ret = -1
09-06 19:16:32.687  3221  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:32.687  3221  3293 D BluetoothAdapterService: updateAdapterState state is 12
09-06 19:16:32.697  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.697  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.697  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.697  3221  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:32.697  3221  3296 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:32.697  3221  3296 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:32.697  7140  7151 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:32.697  3221  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:32.697  3221  3293 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:16:32.697  3221  3293 D BluetoothAdapterService: starting service from this receiver
09-06 19:16:32.697  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.697  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:16:32.697  7140  7151 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.697  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.697  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.697  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.707  3221  3293 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:16:32.707  1431  3358 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.707  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:16:32.707  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.707  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:32.707  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:32.707  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.707  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.707  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.707  1431  3358 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:32.707  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:32.717  4808  7665 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:32.717  3221  3221 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:16:32.717  4808  7665 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.717  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:32.717  3221  7694 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:16:32.737  3221  7694 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:16:32.737  3221  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:32.737  3221  7694 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-06 19:16:32.737  3221  7694 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:32.737  3221  7694 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:32.737  3221  7694 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20176ab2
,09-06 19:16:32.737  3221  7694 D BluetoothSocket: channel: 19
09-06 19:16:32.737  3221  7694 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:16:32.867  1017  1047 I art     : Explicit concurrent mark sweep GC freed 61112(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.325ms total 142.971ms
09-06 19:16:32.867  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:32.867  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.867  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.867  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.867  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.867  4808  4808 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.867  4808  4808 D A2dpProfile: Bluetooth service connected
,09-06 19:16:32.867  4808  4817 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.867  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.867  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.867  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.867  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.867  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.867  4808  4817 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.867  4808  4816 D BluetoothPan: Binding service...
,09-06 19:16:32.867  4808  4808 D HeadsetProfile: Bluetooth service connected
,09-06 19:16:32.867  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:16:32.877  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.877  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.877  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.877  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.877  1457  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.877  1457  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.877  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:32.877  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.877  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:32.877  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.877  1457  4709 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.877  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.877  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.877  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.877  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.877  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.877  1457  4709 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.877  6825  6836 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.877  4808  4808 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:32.877  4808  4808 D PanProfile: Bluetooth service connected
,09-06 19:16:32.877  6825  6836 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.877  1442  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.877  1442  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.877  3221  3297 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.877  3221  3297 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.877  4808  4817 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:16:32.887  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:16:32.887  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.887  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.887  4808  4816 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:16:32.887  4808  4808 D BluetoothMap: Proxy object connected
09-06 19:16:32.887  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:16:32.887  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.887  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:16:32.887  4808  4808 D MapProfile: Bluetooth service connected
,09-06 19:16:32.887  1431  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.887  1431  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.887  4808  4808 D BluetoothMap: getConnectedDevices()
09-06 19:16:32.887  4808  7695 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:16:32.887  4808  7695 D Bluetoothsap: Binding service...
,09-06 19:16:32.887  4808  7695 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:16:32.887  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 19:16:32.887  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.887  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.887  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:16:32.887  4808  7695 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:16:32.897  1431  3358 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.897  4808  4808 D BluetoothInputDevice: Proxy object connected
09-06 19:16:32.897  4808  4808 D HidProfile: Bluetooth service connected
09-06 19:16:32.897  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.897  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.897  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.897  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.897  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.897  1431  3358 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.897  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:16:32.897  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:32.897  4808  4808 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:16:32.897  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:32.897  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.897  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.897  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.897  1017  1017 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.897  4808  4817 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.897  4808  4817 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.897  4808  4808 D SapProfile: Bluetooth service connected
09-06 19:16:32.897  4808  4808 D Bluetoothsap: getConnectedDevices()
09-06 19:16:32.897  4808  7665 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:16:32.897  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:16:32.897  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.897  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.897  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.897  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.897  4808  4808 D BluetoothPbap: Proxy object connected
,09-06 19:16:32.907  1431  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:32.907  4808  4808 D PbapServerProfile: Bluetooth service connected
,09-06 19:16:32.907  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:32.907  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:32.907  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.907  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.907  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.907  1431  1458 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:32.907  2642  2652 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.907  2642  2652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.907  3221  3247 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:32.907  3221  3247 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.907  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:32.907  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:16:32.907  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.907  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.907  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.907  3221  3221 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.907  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:16:32.907  1760  1768 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.907  1760  1768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.917  1017  1047 D BluetoothPan: Binding service...
,09-06 19:16:32.917  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:16:32.917  1180  1209 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.917  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.917  1180  1209 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.917  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:32.917  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:16:32.917  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:16:32.917  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.917  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:16:32.917  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:32.917  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@35dc0ca6, true
,09-06 19:16:32.917  1431  1431 D BluetoothHeadset: registerMessageListener
,09-06 19:16:32.917  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:32.917  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:16:32.927  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:32.927  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.927  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-06 19:16:32.927  4808  4808 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.927  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:32.937  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:32.937  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.937  3221  5334 D HeadsetService: registerMessageListener
,09-06 19:16:32.937  3221  5334 D HeadsetService: registerMessageListener
09-06 19:16:32.937  3221  7697 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:16:32.937  4808  4808 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:16:32.937  3221  7686 D HeadsetStateMachine: Disconnected process message: 70
,09-06 19:16:32.937  4808  4808 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:16:32.937  4808  4808 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:16:32.937  3221  7686 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@426da03
09-06 19:16:32.937  4808  4808 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:16:32.937  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.937  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-06 19:16:32.937  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:32.937  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:16:32.937  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.947  1180  1781 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:32.947  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:16:32.947  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 19:16:32.947  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:16:32.947  3221  7697 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:32.947  3221  7697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:32.947  3221  7697 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-06 19:16:32.947  3221  7697 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:32.947  3221  7697 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-06 19:16:32.947  3221  7697 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c49ed80
09-06 19:16:32.947  3221  7697 D BluetoothSocket: channel: 5
,09-06 19:16:32.947  3221  7686 D HeadsetStateMachine: Disconnected process message: 9
09-06 19:16:32.947  3221  7686 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:16:32.947  4808  4808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:32.947  1017  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:32.947  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.947  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.947  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.947  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:32.957   282   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:16:32.957   282   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:16:32.957   282   695 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:16:32.957   282   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:16:32.957   282   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:16:32.957   282   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:16:32.957   282   695 V audio_hw_primary: adev_set_parameters: exit
09-06 19:16:32.957  3221  7686 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:16:32.957  2642  2642 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:32.967  4808  4808 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:32.967  4808  4808 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:32.967  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.967  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:16:32.977  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e2c822
,09-06 19:16:32.977  3221  3221 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:16:32.977  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.977  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.977  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.977  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.977  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.987  1017  1487 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:32.997  3221  7702 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:32.997  3221  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:33.007  3221  7702 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
,09-06 19:16:33.007  3221  7702 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:33.007  3221  7702 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:33.007  3221  7702 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@152061ac
09-06 19:16:33.007  3221  7702 D BluetoothSocket: channel: 12
09-06 19:16:33.007  3221  7702 I BtOppRfcommListener: Accept thread started.
,09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:33.497  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:33.497  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:33.507  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:33.507  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16ac5ef5 added. We now have 8 listener(s)
,09-06 19:16:33.507  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:33.507  1017  1759 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:33.507  1017  1759 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:16:33.507  1017  1759 D SecContentProvider2: mCursor = null
,09-06 19:16:33.517  1017  1759 D WifiService: setWifiEnabled: false pid=6825, uid=10170
,09-06 19:16:33.517  1017  1759 D SettingsProvider: name = wifi_on
,09-06 19:16:33.517  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:33.517  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:33.517  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:16:33.517  1017  1029 D SecContentProvider2: mCursor = null
,09-06 19:16:33.527  1017  1029 D WifiService: setWifiEnabled: true pid=6825, uid=10170
,09-06 19:16:33.527  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:33.527  1017  1029 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:16:33.527  1017  1029 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6825, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:33.527  1017  1029 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:33.527  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:33.527  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:33.527  1017  1029 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:33.527  1017  1029 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:33.527  1017  1029 D SettingsProvider: name = wifi_on
,09-06 19:16:33.537  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################,
,09-06 19:16:33.857  1017  1045 D Tethering: interfaceAdded wlan0
,09-06 19:16:33.857  1017  1131 E Tethering: No numeric data
,09-06 19:16:33.867  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-06 19:16:33.867  1017  1131 D Tethering: clearTetheredNotification()
,09-06 19:16:33.867  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.867  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:33.867  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:33.867  1017  1123 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:33.867  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:33.867  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.867  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:33.867  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:16:33.877  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:33.877  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:33.877  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:33.877  1017  1131 D Tethering: InitialState.processMessage what=4
09-06 19:16:33.877  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.877  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.877  1017  1131 E Tethering: No numeric data
,09-06 19:16:33.877  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:33.877  1017  1131 D Tethering: clearTetheredNotification()
,09-06 19:16:33.887  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:16:33.887  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:33.887  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:33.887  1017  1045 D Tethering: interfaceAdded p2p0
09-06 19:16:33.887  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-06 19:16:33.887  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
09-06 19:16:33.887  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:33.887  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.887  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:16:33.887  1017  1123 V NetworkStats: performPollLocked() took 8ms
,09-06 19:16:33.897  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:33.897  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:33.897  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:33.897  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.897  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.897   277   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:16:33.897   277   983 D SoftapController: Softap fwReload - Ok
,09-06 19:16:33.897   277   983 D CommandListener: Setting iface cfg
09-06 19:16:33.897   277   983 D CommandListener: Trying to bring down wlan0
,09-06 19:16:33.897   277   983 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:33.907  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:16:33.907  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:16:33.927  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:33.937  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:33.937  1017  4206 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:33.937  1017  4206 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:33.947  1017  4206 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:33.947  1017  4206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:33.947  1017  4206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:33.947  1634  1634 I Hs20UtilService: Starting #19
09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:33.947  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:33.947  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:33.947  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:33.947  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:33.947  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:16:33.947  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:33.947  1180  1180 D HotspotTile: onReceive : 2, 0
,09-06 19:16:33.947  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:33.957  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:33.957  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:33.957  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:33.957  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:33.967  7713  7713 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:16:33.967  7713  7713 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:16:33.967  7713  7713 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:16:33.987  7713  7713 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-06 19:16:33.987   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7713
09-06 19:16:33.987   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-06 19:16:33.987  7713  7713 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:16:33.987  7713  7713 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:33.987  7713  7713 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:16:33.987  7713  7713 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:16:33.987   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7713
09-06 19:16:33.987   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:16:34.157   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 19:16:34.157  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 19:16:34.197  7713  7713 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-06 19:16:34.207  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:16:34.207  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-06 19:16:34.217   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7713
09-06 19:16:34.217   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:16:34.217  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:16:34.217  7713  7713 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:34.217  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:34.217  7713  7713 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:34.217  7713  7713 E wpa_supplicant: SIM READ ERROR
09-06 19:16:34.217  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:34.217  7713  7713 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:34.217  7713  7713 E wpa_supplicant: SIM READ ERROR
09-06 19:16:34.217  7713  7713 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:16:34.217  7713  7713 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:34.217  7713  7713 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:34.217  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:34.217  7713  7713 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:16:34.217  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:34.217  7713  7713 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:16:34.217  7713  7713 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:34.217  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:34.217  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:34.217  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:34.367  7713  7713 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 19:16:34.547  7713  7713 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:34.547  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:16:34.557  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-06 19:16:34.557   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7713
09-06 19:16:34.557   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:16:34.557  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:16:34.557  7713  7713 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:34.557  7713  7713 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-06 19:16:34.567  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:16:34.577  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-06 19:16:34.577   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7713
09-06 19:16:34.577   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:16:34.577  7713  7713 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-06 19:16:34.577  7713  7713 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:34.577  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:16:34.577  7713  7713 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:34.577  7713  7713 E wpa_supplicant: SIM READ ERROR
09-06 19:16:34.577  7713  7713 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:34.577  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.577  7713  7713 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:34.577  7713  7713 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:16:34.577  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.577  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:34.587  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-06 19:16:34.587  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.587  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:34.587   290   290 E SMD     : DCD OFF,
,09-06 19:16:34.737  7713  7713 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:16:34.737  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:16:34.777  7713  7713 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:16:34.777  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:16:34.777  7713  7713 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:34.787  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:16:34.787  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:34.787  7713  7713 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-06 19:16:34.787  7713  7713 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:34.787  7713  7713 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:34.787  7713  7713 E wpa_supplicant: SIM READ ERROR
09-06 19:16:34.787  7713  7713 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:34.807  7713  7713 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:16:34.817  7713  7713 I wpa_supplicant: Skip scan - bUseNetwork false
09-06 19:16:34.817  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:16:34.827  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:34.827  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:34.827  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:34.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:34.827  4808  4808 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:34.827  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:34.837  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:34.837  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:34.837  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:34.837  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:16:34.837  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:34.837  1180  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:34.837  1017  1759 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:34.837  1017  1759 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:34.837  1180  1180 D HotspotTile: onReceive : 3, 0
,09-06 19:16:34.837  1017  1759 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:34.837  1017  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:34.837  1017  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:34.837  1634  1634 I Hs20UtilService: Starting #20
,09-06 19:16:34.837  1634  1661 I Hs20UtilService: Message received 5011
,09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:34.847  6825  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:34.847  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:34.847  7044  7044 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:34.847  7044  7044 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:34.847  7044  7044 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:34.847  6825  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:34.847  1017  1126 E WifiConfigStore: Not a HS20
,09-06 19:16:34.857  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65],
,09-06 19:16:34.857  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:16:34.857  7713  7713 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,09-06 19:16:34.857  7713  7713 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:34.857  7713  7713 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:34.857  7713  7713 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:34.857  7713  7713 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:16:34.857  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:16:34.857  7713  7713 I wpa_supplicant: First Scan Start
09-06 19:16:34.857  7713  7713 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:16:34.857  1017  1126 D WifiNative-wlan0: Setting external_sim to 1,
09-06 19:16:34.857  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:34.857  1017  1126 I WifiNative-HAL: startHal
,09-06 19:16:34.857  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f59488c
09-06 19:16:34.857  1017  1126 I WifiNative-HAL: Could not start hal
09-06 19:16:34.857  7219  7219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:34.867  1017  1126 E WifiNative-wlan0: do suspend true
,09-06 19:16:34.867  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 },
09-06 19:16:34.867  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:16:34.867  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:16:34.867   277   983 D CommandListener: Setting iface cfg
09-06 19:16:34.867  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-06 19:16:34.867   277   983 D CommandListener: Trying to bring up p2p0
09-06 19:16:34.867  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:34.867  1017  1151 I WifiNative-HAL: startHal
09-06 19:16:34.867  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e4569bc
09-06 19:16:34.867  1017  1151 I WifiNative-HAL: Could not start hal
09-06 19:16:34.867  1017  1151 E WifiScanningService: could not start HAL
09-06 19:16:34.867  1017  1125 D WifiP2pService: P2pEnablingState
09-06 19:16:34.867  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:34.867  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:16:34.867  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:16:34.867  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:34.867  1017  1125 D WifiP2pService: P2p socket connection successful
09-06 19:16:34.867  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:34.867  1017  1125 D WifiP2pService: P2pEnabledState
09-06 19:16:34.867  1017  1126 E WifiNative-wlan0: invaild command id : 215
09-06 19:16:34.867  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:34.867  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:34.867  1017  1126 E WifiNative-wlan0: invaild command id : 215
,09-06 19:16:34.877  7713  7713 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:16:34.877  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:34.877  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:34.877  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.877  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.877  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:16:34.877  7713  7713 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:34.877  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:16:34.877  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:16:34.877  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:34.877  7713  7713 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:16:34.877  1017  1048 D WifiDisplayController: disconnect
09-06 19:16:34.877  1017  1048 D WifiDisplayController: updateConnection
09-06 19:16:34.877  1017  1126 E WifiStateMachine: Failed to set frequency band 0
09-06 19:16:34.877  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:34.877  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:34.877  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:34.877  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:34.877  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:16:34.877  1017  1473 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:34.877  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:16:34.877  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:34.887  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:34.887  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:34.887  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:16:34.887  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:16:34.887  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-06 19:16:34.887  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:16:34.887  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
09-06 19:16:34.887  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:34.887  1017  1126 D SecContentProvider2: mCursor = null
09-06 19:16:34.887  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  secondary type: null
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  wps: 0
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  grpcapab: 0
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  devcapab: 0
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  status: 3
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  wfdInfo: null
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  groupownerAddress: null
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  GOdeviceName: null
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  interfaceAddress: 
09-06 19:16:34.887  1017  1048 D WifiDisplayController:  SConnectInfo : null
09-06 19:16:34.887  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:34.887  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:34.887  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:34.887  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:34.887  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:34.887  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:16:34.897  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-06 19:16:34.897  7597  7597 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:34.897  7597  7597 D FileShare-Client: Outbound.stopDelayTimer - 
09-06 19:16:34.897  7204  7204 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-06 19:16:34.917  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:16:34.917  1017  1125 D WifiP2pService: InactiveState
09-06 19:16:34.917  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:16:34.917  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
09-06 19:16:34.917  7713  7713 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:16:34.917  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:16:34.917  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:35.537  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:35.547  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:35.547  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:16:35.547  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:16:35.547  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@343d05a0 Bundle[{}]
,09-06 19:16:35.557  6825  6992 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:16:35.557  6825  6992 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:16:35.557  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:16:35.557  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:16:35.557  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:16:35.557  6825  6992 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:16:35.557  6825  6992 I System.out: Running OutgoingSocketThread
,09-06 19:16:35.567  6825  7724 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1374)
,09-06 19:16:35.567  6825  7724 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54492
,09-06 19:16:35.567  6825  7724 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:16:36.097  7713  7713 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
09-06 19:16:36.097  7713  7713 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:16:36.097  7713  7713 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:16:36.097  7713  7713 I wpa_supplicant: Trying to associate with  'G700'
,09-06 19:16:36.097  7713  7713 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:16:36.097  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 19:16:36.107  1017  7719 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:16:36.127  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:16:36.127  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:36.227  7713  7713 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:16:36.227  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:36.227  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:36.227  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:36.227  7713  7713 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:16:36.227  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:16:36.227  7713  7713 I wpa_supplicant: Associated with F4.99.3E
,09-06 19:16:36.227  7713  7713 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:36.227  7713  7713 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-06 19:16:36.227  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:36.227  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:36.227  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-06 19:16:36.227  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:16:36.227  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:36.227  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-06 19:16:36.227  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:36.227  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:36.227  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:36.227  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:36.237  1017  1131 E Tethering: No numeric data
09-06 19:16:36.237  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:36.237  1017  1126 D SecContentProvider2: mCursor = null
09-06 19:16:36.237  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:36.237  1017  1131 D Tethering: clearTetheredNotification()
09-06 19:16:36.237  7713  7713 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:36.237  7713  7713 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:16:36.237  7713  7713 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:16:36.237  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:36.237  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:36.237  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:36.237  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:36.237  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:36.237  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:36.237  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:16:36.247  7713  7713 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:36.247  7713  7713 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:16:36.247  7713  7713 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:16:36.247  7713  7713 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:16:36.247  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:36.247  1017  1126 D SecContentProvider2: mCursor = null
09-06 19:16:36.247  7713  7713 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:36.247  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:36.247  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:36.247  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:36.247  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.247  1017  1123 V NetworkStats: performPollLocked() took 8ms
,09-06 19:16:36.247  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.247  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:36.247  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:16:36.257  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:16:36.257  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:36.257  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:36.257  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:36.257  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.267  1017  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:36.267  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:36.267  1017  1473 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:16:36.267  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:16:36.267  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:36.267  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:36.267  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:36.267  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:16:36.267  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:36.267  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:36.267  1634  1634 I Hs20UtilService: Starting #21
,09-06 19:16:36.267  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:36.267  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:36.267  1634  1661 I Hs20UtilService: Message received 5007
09-06 19:16:36.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:36.277  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:36.277  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:36.277  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:36.277  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:36.277  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:36.287   277   983 D CommandListener: Setting iface cfg
,09-06 19:16:36.287  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3,
,09-06 19:16:36.287  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:36.287  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:36.297  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:16:36.297  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:36.297  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:16:36.297  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.307  1017  1126 E WifiNative-wlan0: do suspend false
,09-06 19:16:36.307  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:16:36.317  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 19:16:36.317  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:36.317  1017  1126 D SecContentProvider2: mCursor = null
,09-06 19:16:36.527  7727  7727 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:16:36.527  7727  7727 I dhcpcd  : version 5.5.6 starting,
,09-06 19:16:36.537  7727  7727 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:16:36.567  6825  6992 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1375),
09-06 19:16:36.567  6825  6992 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1375)
,09-06 19:16:36.567  6825  6992 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1380),
09-06 19:16:36.567  6825  6992 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
09-06 19:16:36.567  6825  6992 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1381)
,09-06 19:16:36.567  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-06 19:16:36.567  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12d1448a added. We now have 2 listener(s),
,09-06 19:16:36.567  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-06 19:16:36.567  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.567  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:16:36.567  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.577  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b86afb added. We now have 9 listener(s),
09-06 19:16:36.577  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.577  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.577  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.587  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:36.587  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:36.587  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:36.587  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:36.587  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:36.587  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.587  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab0f571 added. We now have 3 listener(s)
09-06 19:16:36.587  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:36.587  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.587  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.587  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:36.587  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e871f56 added. We now have 10 listener(s)
09-06 19:16:36.587  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.587  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:36.587  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:36.587  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:36.587  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.587  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.587  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:36.587  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:36.587  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12d1448a removed from the list
09-06 19:16:36.587  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b86afb removed from the list
09-06 19:16:36.597  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.597  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.597  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b86afb not in the list
09-06 19:16:36.597  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e871f56 removed from the list
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.597  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab0f571 removed from the list
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d98bbd7 added. We now have 2 listener(s)
,09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.597  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128dacc4 added. We now have 9 listener(s)
09-06 19:16:36.597  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.597  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.607  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.607  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:36.607  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:36.607  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:36.607  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.607  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eddae2 added. We now have 3 listener(s),
,09-06 19:16:36.607  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.617  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.617  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:36.617  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.617  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.617  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.617  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bc33e73 added. We now have 10 listener(s)
09-06 19:16:36.617  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.617  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.617  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-06 19:16:36.617  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-06 19:16:36.617  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:36.617  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:36.617  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:36.617  7727  7727 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:16:36.617  7727  7727 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:16:36.617  7727  7727 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-06 19:16:36.617  7727  7727 I dhcpcd  : bssid match
09-06 19:16:36.617  7727  7727 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-06 19:16:36.627  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:36.627  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-06 19:16:36.627  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:16:36.627  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:16:36.627  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:36.627  3221  7696 D BtGatt.GattService: registerClient() - UUID=600d9221-2365-4ff4-af32-81b24ddabb34,
,09-06 19:16:36.667  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=600d9221-2365-4ff4-af32-81b24ddabb34, clientIf=6
,09-06 19:16:36.677  6825  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:36.677  3221  5334 D BtGatt.GattService: start scan with filters
,09-06 19:16:36.677  3221  3357 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:36.677  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-06 19:16:36.677  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:16:36.677  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:16:36.677  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:36.677  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:36.677  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.687  3221  3357 D BtGatt.ScanManager: allow scan with filters
,09-06 19:16:36.687  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:36.687  3221  3357 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-06 19:16:36.687  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:16:36.687  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.687  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:36.687  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:36.687  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:36.687  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.687  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:36.697  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:36.697  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:36.697  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.697  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.697  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:36.707  6825  6992 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:16:36.707  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:36.707  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:36.707  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.707  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:36.707  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:36.707  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:36.707  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:36.707  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:36.707  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:36.707  7727  7727 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
09-06 19:16:36.707  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:36.707  3221  3380 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:36.707  3221  3357 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:36.707  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 6
,09-06 19:16:36.707  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:36.707  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.717  3221  3235 D BtGatt.GattService: unregisterClient() - clientIf=6,
09-06 19:16:36.717  3221  3357 D BtGatt.ScanManager: stopping BLe Batch,
,09-06 19:16:36.717  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:36.717  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:36.717  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:36.717  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:36.717  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:36.717  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:36.717  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:36.717  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.717  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:16:36.727  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:16:36.727  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.727  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:16:36.727  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:16:36.727  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:36.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.737  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:36.737  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:36.737  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:36.737  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:36.737  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:36.737  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:36.737  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:36.737  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.737  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.737  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:36.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d98bbd7 removed from the list
09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128dacc4 removed from the list
09-06 19:16:36.747  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:36.747  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.747  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.747  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:36.747  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128dacc4 not in the list
09-06 19:16:36.747  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:16:36.747  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:36.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bc33e73 removed from the list
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.747  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.747  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.747  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:36.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eddae2 removed from the list
,09-06 19:16:36.747  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:16:36.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b094ecf added. We now have 2 listener(s)
,09-06 19:16:36.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:16:36.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:16:36.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:16:36.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:36.757  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c13d05c added. We now have 9 listener(s)
09-06 19:16:36.757  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:36.757  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.767  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.767  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:36.767  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:36.767  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:36.767  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.767  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358be43a added. We now have 3 listener(s)
,09-06 19:16:36.767  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.777  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 19:16:36.777  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:16:36.777  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.777  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:16:36.777  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.777  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af608eb added. We now have 10 listener(s)
09-06 19:16:36.777  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.777  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-06 19:16:36.777  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:16:36.777  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:36.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:36.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:36.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-06 19:16:36.777  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-06 19:16:36.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:36.777  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:36.787  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:36.787  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:36.787  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:36.787  3221  3235 D BtGatt.GattService: registerClient() - UUID=6b935dbd-50af-470e-8cf1-f384c8250aa1
,09-06 19:16:36.827  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=6b935dbd-50af-470e-8cf1-f384c8250aa1, clientIf=6
,09-06 19:16:36.827  6825  6839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:36.827  3221  3247 D BtGatt.GattService: start scan with filters
,09-06 19:16:36.827  3221  3357 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:36.837  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:36.837  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:36.837  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:36.837  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:36.837  7727  7727 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-06 19:16:36.837  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-06 19:16:36.837  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.837  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:36.847  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:36.847  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.847  3221  3357 D BtGatt.ScanManager: allow scan with filters
,09-06 19:16:36.847  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:16:36.847  3221  3357 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-06 19:16:36.847  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:36.847  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.847  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:16:36.847  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:36.847  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:16:36.847  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:36.847  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.857  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:36.857  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.857  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.857  6825  6992 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:16:36.857  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:36.857  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:36.857  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.857  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.857  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b094ecf removed from the list
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.857  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c13d05c removed from the list
09-06 19:16:36.857  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.857  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:16:36.857  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.857  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c13d05c not in the list
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:36.857  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:36.857  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,09-06 19:16:36.867  3221  7696 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:36.867  1017  3360 D SSRM:n  : SIOP:: AP = 330
09-06 19:16:36.867  3221  5334 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:36.867  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:36.867  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:36.867  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:36.867  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:36.867  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:36.867  3221  3357 D BtGatt.ScanManager: filter size is 1
09-06 19:16:36.867  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 7
,09-06 19:16:36.867  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:36.867  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-06 19:16:36.867  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.867  3221  3357 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:36.877  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:36.877  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:36.877  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.877  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:36.877  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.877  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:36.877  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af608eb removed from the list
09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:36.877  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.877  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.877  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:36.877  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.877  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:36.877  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358be43a removed from the list,
,09-06 19:16:36.877  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:36.877  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.877  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eaa48c7 added. We now have 2 listener(s)
09-06 19:16:36.877  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:36.877  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:36.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.887  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.887  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1197cef4 added. We now have 9 listener(s)
09-06 19:16:36.887  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:36.887  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.897  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.897  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:36.897  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:36.897  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:36.897  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.897  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c06c092 added. We now have 3 listener(s)
,09-06 19:16:36.907  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.907  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:36.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:16:36.907  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.907  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2078aa63 added. We now have 10 listener(s)
09-06 19:16:36.907  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.907  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.907  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:36.907  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:36.907  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.907  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:36.917  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:36.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:36.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:36.937  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:36.937  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:36.937  6825  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:36.947  3221  3380 D BtGatt.GattService: registerClient() - UUID=df45e29d-1a9e-4f3b-a441-cf3b9fac655b,
,09-06 19:16:36.997  3221  3296 D BtGatt.GattService: onClientRegistered() - UUID=df45e29d-1a9e-4f3b-a441-cf3b9fac655b, clientIf=6
,09-06 19:16:36.997  6825  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:36.997  3221  3235 D BtGatt.GattService: start scan with filters
,09-06 19:16:36.997  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-06 19:16:36.997  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:36.997  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:16:36.997  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:16:36.997  3221  3357 D BtGatt.ScanManager: handling starting scan
09-06 19:16:36.997  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.997  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.997  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:37.007  3221  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:37.007  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:37.007  3221  3357 D BtGatt.ScanManager: allow scan with filters,
09-06 19:16:37.007  3221  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:37.007  3221  3357 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-06 19:16:37.007  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:37.007  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:16:37.007  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:37.007  3221  3357 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:37.007  3221  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:37.007  3221  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:37.007  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:37.017  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:37.017  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:37.027  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:16:37.027  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-06 19:16:37.027  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:37.027  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:37.027  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.027  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:16:37.027  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:37.027  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eaa48c7 removed from the list
,09-06 19:16:37.027  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.027  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1197cef4 removed from the list,
09-06 19:16:37.027  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:37.027  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:37.027  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.027  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-06 19:16:37.027  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.027  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.037  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1197cef4 not in the list
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:16:37.037  3221  3235 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:16:37.037  3221  3357 D BtGatt.ScanManager: filter size is 1
09-06 19:16:37.037  3221  3357 D BtGatt.ScanManager: delete FilterIndex - 8
,09-06 19:16:37.037  3221  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:16:37.037  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:37.037  3221  3297 D BtGatt.GattService: unregisterClient() - clientIf=6
09-06 19:16:37.037  3221  3357 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:37.037  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:16:37.037  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:37.047  3221  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:37.047  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-06 19:16:37.047  3221  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:37.047  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:37.047  6825  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:37.047  6825  6825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2078aa63 removed from the list
,09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:37.047  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c06c092 removed from the list
09-06 19:16:37.047  3221  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:37.047  3221  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@234189bf added. We now have 2 listener(s)
,09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:37.047  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a088c added. We now have 9 listener(s)
09-06 19:16:37.047  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:37.047  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:37.057  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:37.057  6825  6992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:37.057  6825  6992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:37.057  6825  6992 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:37.057  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:37.057  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c5cfea added. We now have 3 listener(s)
,09-06 19:16:37.057  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:37.057  6825  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d8f02db added. We now have 10 listener(s)
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:37.067  6825  6992 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:37.067  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@234189bf removed from the list
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a088c removed from the list
09-06 19:16:37.067  6825  6992 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:37.067  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.067  6825  6992 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a088c not in the list
09-06 19:16:37.067  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d8f02db removed from the list
,09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:37.067  6825  6992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:37.067  6825  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:37.067  6825  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:37.067  6825  6992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c5cfea removed from the list
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:16:37.067  6825  6992 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:37.077  6825  7758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1388, name: My test thread name)
,09-06 19:16:37.077  6825  7758 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1388, thread name: My test thread name)
,09-06 19:16:37.077  6825  7758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1388, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:16:37.077  6825  7759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1390, name: My test thread name)
,09-06 19:16:37.077  6825  7759 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1390, thread name: My test thread name)
,09-06 19:16:37.077  6825  7759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1390, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:16:37.077  6825  6992 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:16:37.087  6825  6992 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:16:37.087  6825  6992 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:16:37.087  6825  6992 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:16:37.087  6825  6992 D com.test.thalitest.ThaliTestRunner: Total duration: 23351 ms
,09-06 19:16:37.087  6825  6992 I jxcore-log: *Native tests were executed*
09-06 19:16:37.087  6825  6992 I jxcore-log: 
,09-06 19:16:37.087  6825  6992 I jxcore-log: Total number of executed tests:  80
09-06 19:16:37.087  6825  6992 I jxcore-log: 
09-06 19:16:37.087  6825  6992 I jxcore-log: Number of passed tests:  80
09-06 19:16:37.087  6825  6992 I jxcore-log: 
09-06 19:16:37.087  6825  6992 I jxcore-log: Number of failed tests:  0
09-06 19:16:37.087  6825  6992 I jxcore-log: 
,09-06 19:16:37.087  6825  6992 I jxcore-log: Number of ignored tests:  0
09-06 19:16:37.087  6825  6992 I jxcore-log: 
,09-06 19:16:37.087  6825  6992 I jxcore-log: Total duration:  23351
09-06 19:16:37.087  6825  6992 I jxcore-log: 
09-06 19:16:37.087  6825  6992 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:16:37.087  6825  6992 I jxcore-log: 
,09-06 19:16:37.087  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.087  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6825 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.097  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:37.097  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: ,
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
,09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
,09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
,09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
,09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.107  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-06 19:16:37.107  6825  6992 I jxcore-log: 
09-06 19:16:37.117  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.117  6825  6992 I jxcore-log: 
,09-06 19:16:37.117  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:37.117  6825  6992 I jxcore-log: 
,09-06 19:16:37.127  1017  1126 E WifiNative-wlan0: do suspend true
,09-06 19:16:37.147  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:16:37.147  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:37.157  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
09-06 19:16:37.157  1017  1126 E WifiStateMachine: VerifyingLinkState enter
,09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:37.167  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:37.167  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504
09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.167  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.167  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:37.167  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-06 19:16:37.187  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-06 19:16:37.187  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:37.187  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:37.187  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:37.187  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:16:37.197  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.197  1017  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:37.197  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:37.207  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
,09-06 19:16:37.207  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:37.207  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:37.207  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:37.207  1634  1634 I Hs20UtilService: Starting #22
,09-06 19:16:37.217  1634  1661 I Hs20UtilService: Message received 5007
09-06 19:16:37.217  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-06 19:16:37.217  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-06 19:16:37.217  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:37.217  4808  4808 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 19:16:37.217  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-06 19:16:37.217  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:16:37.217  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-06 19:16:37.217  1017  1128 D ConnectivityService: LTETest block dns file not exists
,09-06 19:16:37.227  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.227  1017  1128 V NetworkStats: updateIfacesLocked()
09-06 19:16:37.227  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:37.227  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:37.227  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:37.237  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:16:37.237  1017  1128 V NetworkStats: performPollLocked() took 13ms
09-06 19:16:37.237  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:16:37.237  6825  6825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:16:37.237  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.237  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:37.237  6825  6992 I jxcore-log: 
,09-06 19:16:37.247  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:37.247  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.247  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:37.247  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 19:16:37.247  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,09-06 19:16:37.257  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:37.257  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 19:16:37.257  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.267  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:37.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.267  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:37.267  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:37.267  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.267  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:37.267  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.267  1634  1634 I Hs20UtilService: Starting #23
09-06 19:16:37.267  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:16:37.267  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.267  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:37.267  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.267  1017  1128 V NetworkStats: updateIfacesLocked()
09-06 19:16:37.267  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:37.267  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:37.267  1017  1128 E ConnectivityService: updateNetworkInfo()
09-06 19:16:37.267  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.267  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:37.267  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:37.267  1634  1661 I Hs20UtilService: Message received 5007
,09-06 19:16:37.267  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:37.267  4808  4808 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:37.267  1017  1128 V NetworkStats: performPollLocked() took 3ms
09-06 19:16:37.267  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:37.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:37.267  4808  4808 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:37.267  4808  4808 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:37.267  4808  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:37.277  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.277  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.277  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.277  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:37.277  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.277  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:16:37.277  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:37.277  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 19:16:37.277  1017  7725 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:16:37.277  1017  1128 D ConnectivityService:    accepting network in place of null
,09-06 19:16:37.277  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:16:37.277  1457  1457 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:37.287   277   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:37.287   277   979 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-06 19:16:37.287  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:16:37.287  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:16:37.287  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:16:37.287  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-06 19:16:37.287  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:16:37.287  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-06 19:16:37.287  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-06 19:16:37.287  1017  1131 D Tethering: MasterInitialState.processMessage what=3
09-06 19:16:37.287  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:16:37.287  1017  7725 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-06 19:16:37.287  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.287  1017  1123 V NetworkStats: updateIfacesLocked()
09-06 19:16:37.287  1017  1123 V NetworkStats: performPollLocked(flags=0x1),
,09-06 19:16:37.287  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:37.287  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.287  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:37.287  1017  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:37.287  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:16:37.287  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:37.297  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:37.297  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.297  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.297  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.297  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:37.297  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-06 19:16:37.297  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:16:37.297  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-06 19:16:37.297  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:16:37.297  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:16:37.297  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:16:37.297  1017  1123 V NetworkStats: performPollLocked() took 5ms
09-06 19:16:37.297  1180  1180 D StatusBar.NetworkController: updateDataNetType()
09-06 19:16:37.297  1180  1755 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:16:37.297  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.297  1634  1634 I Hs20UtilService: Starting #24
09-06 19:16:37.297  4808  4808 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:37.297  4808  4808 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 19:16:37.297  1634  1661 I Hs20UtilService: Message received 5007
,09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.297  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.297  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.297  1180  1755 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:37.307  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:37.307  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:16:37.307  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:37.307  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.307  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:37.317  1017  1487 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-06 19:16:37.317  1017  4205 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-06 19:16:37.317  1017  4205 D SecContentProvider2: mCursor = null
,09-06 19:16:37.317  1017  1759 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 19:16:37.317  1017  1759 D SecContentProvider2: mCursor = null
,09-06 19:16:37.317  1017  1367 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-06 19:16:37.317  1017  1367 D SecContentProvider2: mCursor = null
09-06 19:16:37.317  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 19:16:37.317  1017  1029 D SecContentProvider2: mCursor = null
,09-06 19:16:37.317  1017  1498 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-06 19:16:37.317  1017  1498 D SecContentProvider2: mCursor = null
,09-06 19:16:37.327  1017  1223 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-06 19:16:37.327  1017  1223 D SecContentProvider2: mCursor = null
,09-06 19:16:37.347   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-06 19:16:37.367  1017  1487 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,09-06 19:16:37.377  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:16:37.377  6825  6825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:16:37.377  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:37.377  6825  6992 I jxcore-log: 
,09-06 19:16:37.397  7760  7760 D AndroidRuntime: ,
09-06 19:16:37.397  7760  7760 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:16:37.407  7760  7760 D AndroidRuntime: CheckJNI is OFF,
09-06 19:16:37.407  7760  7760 D AndroidRuntime: readGMSProperty: start
,09-06 19:16:37.407  7760  7760 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:16:37.407  7760  7760 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,09-06 19:16:37.407  7760  7760 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:16:37.407  7760  7760 D AndroidRuntime: readGMSProperty: end
,09-06 19:16:37.407  7760  7760 D AndroidRuntime: addProductProperty: start,
,09-06 19:16:37.527  7760  7760 E AffinityControl: AffinityControl: registerfunction enter
,09-06 19:16:37.547  6825  6825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:16:37.547  6825  6992 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-06 19:16:37.547  6825  6992 I jxcore-log: 
,09-06 19:16:37.557  7760  7760 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:16:37.587  1017  1344 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-06 19:16:37.587  1017  1344 D PackageManager: START PACKAGE DELETE: observer{952891080}
09-06 19:16:37.587  1017  1344 D PackageManager: pkg{<packageName>}
09-06 19:16:37.587  1017  1344 D PackageManager: user{0}
09-06 19:16:37.587  1017  1344 D PackageManager: caller{2000}
09-06 19:16:37.587  1017  1344 D PackageManager: flags{2}
09-06 19:16:37.587  1017  1344 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-06 19:16:37.587  1017  1344 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-06 19:16:37.587  1017  1344 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
09-06 19:16:37.587  1017  1344 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 19:16:37.587   290   290 E SMD     : DCD OFF,
,09-06 19:16:37.597  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-06 19:16:37.597  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 19:16:37.597  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 19:16:37.597  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-06 19:16:37.597  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:16:37.597  1017  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,09-06 19:16:37.597  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
09-06 19:16:37.597  1017  1043 I ActivityManager: Killing 6825:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:16:37.597  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{127cf234 u0 com.test.thalitest/.MainActivity t163}
,09-06 19:16:37.617  1017  1043 D InputDispatcher: Focus left window: 6825
,09-06 19:16:37.617   257  1039 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-06 19:16:37.617   257   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-06 19:16:37.637  1017  1043 D InputDispatcher: Focused application released
,09-06 19:16:37.637  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:16:37.637  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:37.717  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-06 19:16:37.737  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:16:37.767  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:16:37.777  2835  2835 I art     : Explicit concurrent mark sweep GC freed 17386(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 796us total 38.249ms
,09-06 19:16:37.777  1874  1874 E SamsungIME: mOCRHelper is null
09-06 19:16:37.777  1760  2011 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:16:37.787  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:16:37.787  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:37.797  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-06 19:16:37.797  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 19:16:37.797  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 19:16:37.797  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-06 19:16:37.797  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:37.807  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:16:37 GMT+02:00 2016
,09-06 19:16:37.807  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:16:37.817  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:16:37.837  1442  1442 D RegisteredServicesCache: empty dynamic service
,09-06 19:16:37.847  1017  4205 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:16:37.847  1017  4205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:37.847  1017  4205 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:37.847  1017  4205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.847  1017  4205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:16:37.847  2819  2819 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:16:37.867  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:16:37.877  1017  1498 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,09-06 19:16:37.877  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-06 19:16:37.877  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.877  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
09-06 19:16:37.877  1017  1498 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-06 19:16:37.877  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:37.877  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:37.877  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:16:37.877  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.877  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.877  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.877  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.877  1017  1123 V NetworkStats: performPollLocked() took 6ms
09-06 19:16:37.877  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.897  7778  7778 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.897  7778  7778 E Zygote  : v2
09-06 19:16:37.897  7778  7778 I libpersona: KNOX_SDCARD checking this for 10090
09-06 19:16:37.897  7778  7778 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.897  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.897  2819  2819 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:16:37.897  1017  1498 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7778 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:37.897  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:37.907  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-06 19:16:37.907  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:37.907  2819  2819 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-06 19:16:37.907  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.907  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.907  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.907  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.917  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:16:37.917  7789  7789 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.917  7789  7789 I libpersona: KNOX_SDCARD checking this for 10052
09-06 19:16:37.917  7789  7789 E Zygote  : v2
09-06 19:16:37.917  7789  7789 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.917  7789  7789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:37.917  1017  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7789 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-06 19:16:37.927  7789  7789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:37.927  7789  7789 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:16:37.927  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast,
09-06 19:16:37.927  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-06 19:16:37.937  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.937  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.937  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
09-06 19:16:37.937  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.937  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.947  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.947  7778  7778 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.947   315   315 I art     : Explicit concurrent mark sweep GC freed 8679(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 27.098ms
,09-06 19:16:37.957  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-06 19:16:37.967  7789  7789 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.967  7789  7789 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.967   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.772ms
,09-06 19:16:37.977  1017  1344 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:16:37.977  1017  1344 D SecContentProvider2: mCursor = null
,09-06 19:16:37.987   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 641us total 16.506ms
,09-06 19:16:37.997  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 19:16:37.997  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-06 19:16:37.997  1017  1042 W TextServicesManagerService: no available spell checker services found
,09-06 19:16:37.997  7808  7808 E Zygote  : MountEmulatedStorage()
,09-06 19:16:37.997  7808  7808 E Zygote  : v2
09-06 19:16:37.997  7808  7808 I libpersona: KNOX_SDCARD checking this for 10098
09-06 19:16:37.997  7808  7808 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.997  7808  7808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.997  7808  7808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:37.997  1017  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7808 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:16:38.007  7808  7808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:38.007  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:16:38.027  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:16:38.027  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:16:38.027  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:16:38.027  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.027  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:16:38.027  1017  1017 V EnterpriseBillingPolicy: uID is 10170
09-06 19:16:38.027  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:16:38.027  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:16:38.037  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:16:38.037  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:16:38.037  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:16:38.037  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:16:38.037  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:16:38.037  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.037  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.037  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.047  7808  7808 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.047  7808  7808 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.057  7821  7821 E Zygote  : MountEmulatedStorage()
09-06 19:16:38.057  7821  7821 I libpersona: KNOX_SDCARD checking this for 10032
09-06 19:16:38.057  7821  7821 E Zygote  : v2
09-06 19:16:38.057  7821  7821 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:38.057  7821  7821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:38.057  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.057  1017  1498 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7821 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:38.067  7821  7821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:38.067  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:38.067  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:38.067  7821  7821 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 19:16:38.067  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:16:38.067  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:16:38.067  1017  3360 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-06 19:16:38.077  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-06 19:16:38.077  7778  7778 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-06 19:16:38.077  7778  7778 D elm:15121: ELMEngine.ELMEngine( context ).
,09-06 19:16:38.077  7778  7778 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-06 19:16:38.077  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-06 19:16:38.087  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-06 19:16:38.087  1017  1505 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-06 19:16:38.087  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.107  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.107  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:38.107  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-06 19:16:38.107  2819  7777 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-06 19:16:38.107  7778  7778 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-06 19:16:38.117  2819  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-06 19:16:38.117  7778  7778 D elm:15121: ElmAgentService : onCreate()
,09-06 19:16:38.117  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.127  7778  7837 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-06 19:16:38.127  7778  7837 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-06 19:16:38.127  7778  7837 D elm:15121: MDMBridge.getInstance()
09-06 19:16:38.127  7778  7837 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:16:38.127  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.127  7821  7821 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.127  2819  2819 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:16:38.127  7821  7821 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.127  7778  7837 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-06 19:16:38.147  1017  4206 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicy: uID is 10170
,09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:16:38.147  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.147  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.147  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.147  1017  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0,
09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:16:38.147  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:16:38.157  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:16:38.167  7840  7840 E Zygote  : MountEmulatedStorage(),
09-06 19:16:38.167  7840  7840 I libpersona: KNOX_SDCARD checking this for 1000
,09-06 19:16:38.167  7840  7840 E Zygote  : v2
09-06 19:16:38.167  7840  7840 I libpersona: KNOX_SDCARD not a persona,
,09-06 19:16:38.167  7840  7840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:38.167  1017  4206 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:38.167  1017  4206 I ActivityManager: Killing 7279:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 19:16:38.177  7840  7840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:38.177  7840  7840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.187  7778  7778 D elm:15121: ElmAgentService : onDestroy().
09-06 19:16:38.187  1017  4205 I ActivityManager: Killing 7294:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:16:38.197  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.217  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-06 19:16:38.217  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.217  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.217  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.217  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-06 19:16:38.227  7840  7840 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.227  7840  7840 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.227  7821  7856 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:16:38.227  7821  7856 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-06 19:16:38.227  2642  2642 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-06 19:16:38.227  2642  2642 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-06 19:16:38.237  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-06 19:16:38.237  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.247  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.247  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.247  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-06 19:16:38.247  7821  7856 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:16:38.247  7821  7856 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:16:38.247  7821  7856 D SPPClientService: ============PushLog. stop!
,09-06 19:16:38.247  1017  1058 I art     : Explicit concurrent mark sweep GC freed 72929(4MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 7.055ms total 398.695ms
,09-06 19:16:38.247  1017  1027 I art     : WaitForGcToComplete blocked for 385.082ms for cause HeapTrim
,09-06 19:16:38.267  1017  1498 I ActivityManager: Killing 7336:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-06 19:16:38.277  1017  1473 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-06 19:16:38.277  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.287  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.287  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:38.287  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.287  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 19:16:38.297  1017  1029 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-06 19:16:38.297  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.297  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.297  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:38.297  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-06 19:16:38.297  7309  7859 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-06 19:16:38.317  7118  7118 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-06 19:16:38.327  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-06 19:16:38.327  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.327  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.327  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.327  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.347  7861  7861 E Zygote  : MountEmulatedStorage()
,09-06 19:16:38.347  7861  7861 E Zygote  : v2
09-06 19:16:38.347  7861  7861 I libpersona: KNOX_SDCARD checking this for 10039
09-06 19:16:38.347  7861  7861 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.347  7861  7861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:38.347  7861  7861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:38.347  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 19:16:38.347  7861  7861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.357  1017  1030 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7861 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-06 19:16:38.367  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.367  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-06 19:16:38.367  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.367  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.367  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.367  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.367  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.387  7875  7875 E Zygote  : MountEmulatedStorage()
,09-06 19:16:38.387  7875  7875 E Zygote  : v2
09-06 19:16:38.387  7875  7875 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:38.387  7875  7875 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.387  1017  1030 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7875 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:38.387  7875  7875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:38.387  7309  7859 D AccountUtils: Clearing selected account for com.test.thalitest
,09-06 19:16:38.387  7875  7875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:38.387  7875  7875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.397  1017  1473 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-06 19:16:38.397  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-06 19:16:38.407  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.407  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-06 19:16:38.407  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.407  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,09-06 19:16:38.407  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-06 19:16:38.417  7895  7895 E Zygote  : MountEmulatedStorage(),
09-06 19:16:38.417  7895  7895 I libpersona: KNOX_SDCARD checking this for 1000
,09-06 19:16:38.417  7895  7895 E Zygote  : v2
09-06 19:16:38.417  7895  7895 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:38.417  7861  7861 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:38.427  1017  1473 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:38.417  7895  7895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:38.427  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:16:38.417  7861  7861 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:38.417  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.417  7895  7895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:38.417  7895  7895 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.427  7118  7118 D BluetoothAdapter: cancelDiscovery
,09-06 19:16:38.437  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.437  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.437  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.447  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:38.447  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.447  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.447  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.447  7875  7875 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.447  7875  7875 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.457  3221  3380 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:16:38.457  3221  3380 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,09-06 19:16:38.457  7118  7118 D BluetoothAdapter: cancelDiscovery = true
,09-06 19:16:38.457  7118  7118 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-06 19:16:38.457  7895  7895 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.457  7895  7895 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:16:38.467  7861  7861 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:16:38.467  1017  1058 D PackageManager: delete codoeFile: 
,09-06 19:16:38.477  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:16:38.477  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:16:38.477  7118  7118 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:16:38.477  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 19:16:38.477  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:38.477  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:38.477  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.477  1017  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:38.477  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.487  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.487  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:38.487  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.497  7875  7875 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:38.497  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-06 19:16:38.497  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.507  1017  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-06 19:16:38.507  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.507  1017  1058 D PackageManager: result of delete: 1{952891080}
,09-06 19:16:38.507  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.507  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:38.507  7309  7859 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-06 19:16:38.517  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.517  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:38.517  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:38.517  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.517  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:38.517  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 19:16:38.527  7760  7760 D AndroidRuntime: Shutting down VM
,09-06 19:16:38.527  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.527  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.527  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:38.527  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:38.527  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.537  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-06 19:16:38.537  7309  7309 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-06 19:16:38.537  7309  7309 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,09-06 19:16:38.537  7895  7895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-06 19:16:38.537  1017  1223 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-06 19:16:38.537  1017  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.537  1017  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:38.537  1017  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:38.537  1017  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-06 19:16:38.547  1017  1759 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-06 19:16:38.547  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.547  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.547  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.547  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.557  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-06 19:16:38.557  7917  7917 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:38.557  7917  7917 E Zygote  : MountEmulatedStorage()
09-06 19:16:38.557  7917  7917 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:38.557  7917  7917 E Zygote  : v2
09-06 19:16:38.567  7917  7917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:38.567  7917  7917 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:38.567  7917  7917 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.577  1017  1759 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7917 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:38.577  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:38.577  1017  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:38.577  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:16:38.577  1017  1058 D PackageManager: userId{-1}
09-06 19:16:38.577  1017  1058 D PackageManager: andCode{true}
,09-06 19:16:38.577  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.577  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.577  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.587  7309  7914 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,09-06 19:16:38.587  7309  7914 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,09-06 19:16:38.587  7309  7914 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
09-06 19:16:38.587  7309  7914 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,09-06 19:16:38.597  7309  7914 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
09-06 19:16:38.597  7309  7914 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,09-06 19:16:38.597  7309  7914 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,09-06 19:16:38.597  1017  1030 I ActivityManager: Killing 7369:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:16:38.607  1017  1344 D LocationManagerService: getProviders()=[passive, gps]
,09-06 19:16:38.617  7309  7914 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
09-06 19:16:38.617  7309  7914 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,09-06 19:16:38.617  7309  7914 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,09-06 19:16:38.617  7917  7917 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.617  7917  7917 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.617  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:38.617  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.617  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.617  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.617  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.627  7309  7914 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,09-06 19:16:38.627  7309  7914 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
09-06 19:16:38.627  7309  7914 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,09-06 19:16:38.647  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.647  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.647  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.647  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.647  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.667  7938  7938 E Zygote  : MountEmulatedStorage()
,09-06 19:16:38.667  7938  7938 E Zygote  : v2
09-06 19:16:38.667  7938  7938 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:16:38.667  7938  7938 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.667  7938  7938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:38.677  1017  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7938 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 19:16:38.677  7938  7938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:38.677  1017  1505 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-06 19:16:38.677  7938  7938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.677  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.677  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.677  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.687  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.687  3221  3294 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:16:38.697  7947  7947 E Zygote  : MountEmulatedStorage(),
09-06 19:16:38.697  7947  7947 E Zygote  : v2
,09-06 19:16:38.697  7947  7947 I libpersona: KNOX_SDCARD checking this for 10014,
09-06 19:16:38.697  1017  1505 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7947 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:38.707  7947  7947 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.707  7947  7947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:16:38.707  7947  7947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:38.707  7947  7947 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.717  7917  7954 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-06 19:16:38.717  7917  7954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-06 19:16:38.747  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-06 19:16:38.747  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.747  7938  7938 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.747  7938  7938 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:38.747  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.747  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:38.747  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-06 19:16:38.747  7760  7760 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 19:16:38.747  7917  7917 D AcmsService: Enter Oncreate
09-06 19:16:38.757  7917  7917 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-06 19:16:38.757  7917  7917 D AcmsService: creating AcmsCore
09-06 19:16:38.757  7917  7917 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-06 19:16:38.757  7917  7917 D AcmsCore: AcmsCore
09-06 19:16:38.757  7947  7947 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:38.757  7947  7947 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:38.767  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:16:38.767  1017  1128 V NetworkStats: updateIfacesLocked()
09-06 19:16:38.767  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:38.767  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:38.767  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:38.767  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:38.767  1017  1128 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:38.767  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:38.767  7917  7917 D AcmsCore: init
09-06 19:16:38.767  7917  7917 D AcmsCore: Looper handler is not null
09-06 19:16:38.767  7917  7917 D AcmsCore: Post to AcmsCoreHandler
,09-06 19:16:38.767  7917  7917 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-06 19:16:38.767  7917  7917 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-06 19:16:38.767  7917  7917 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-06 19:16:38.767  7917  7917 D AcmsService: onStartCommand
09-06 19:16:38.767  7917  7917 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-06 19:16:38.767  7917  7917 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-06 19:16:38.767  7917  7917 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-06 19:16:38.767  7917  7917 D AcmsService: Incremented Counter Value : onStartCommand
,09-06 19:16:38.777  7917  7970 D AcmsCertificateMngr: AcmsCertificateMngr
,09-06 19:16:38.777  7917  7970 D AcmsRevocationMngr: AcmsRevocationMngr
,09-06 19:16:38.787  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:16:38.787  7875  7875 I art     : Explicit concurrent mark sweep GC freed 5510(273KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 3.772ms total 89.530ms
,09-06 19:16:38.787  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.787  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.787  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:38.787  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:16:38.787  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:38.787  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:16:38.787  1180  1755 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:16:38.787  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:38.797  1180  1755 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:16:38.807  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-06 19:16:38.807  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.807  7875  7933 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-06 19:16:38.807  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.807  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.807  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-06 19:16:38.817  1017  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-06 19:16:38.817  7789  7858 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-06 19:16:38.827  7917  7917 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-06 19:16:38.827  1017  1759 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:16:38.837  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.837  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.837  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.837  1017  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.837  7917  7917 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-06 19:16:38.837  7309  7309 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-06 19:16:38.837  7309  7309 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-06 19:16:38.847  7976  7976 E Zygote  : MountEmulatedStorage()
09-06 19:16:38.847  7976  7976 E Zygote  : v2
09-06 19:16:38.847  7976  7976 I libpersona: KNOX_SDCARD checking this for 1000,
,09-06 19:16:38.847  1017  1759 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-06 19:16:38.857  7976  7976 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.867  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-06 19:16:38.867  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-06 19:16:38.867  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:38.867  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:38.867  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-06 19:16:38.877  7976  7976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:38.877  7861  7861 D NearbySource: Nearby Source Create!
09-06 19:16:38.877  7861  7861 D NearbyContext: Nearby Context Create!
09-06 19:16:38.877  7976  7976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:38.877  7976  7976 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.897  7789  7858 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 19:16:38.897  1017  1473 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-06 19:16:38.907  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.907  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.907  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.e.Jx(UpdateIcingCorporaService.java:408)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.g.bdp(UpdateIcingCorporaService.java:347)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:38.907  7789  7858 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:16:38.907  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:38.917  7541  7554 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
09-06 19:16:38.917  7541  7554 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,09-06 19:16:38.917  7541  7554 E DatabaseUtils: Writing exception to parcel
09-06 19:16:38.917  7541  7554 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
09-06 19:16:38.917  7541  7554 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:38.917  7976  7976 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:38.917  7976  7976 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:38.917  7998  7998 E Zygote  : MountEmulatedStorage()
09-06 19:16:38.917  7998  7998 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:38.917  7998  7998 E Zygote  : v2
09-06 19:16:38.917  7998  7998 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:38.917  7998  7998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:38.927  7998  7998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:38.927  7998  7998 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:38.927  1017  1473 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a

```
