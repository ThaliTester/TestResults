#### Test 8286536244f8192_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-26 14:59:43.234  6407  6407 D ComposerPerformance: 1472216383240 ms / [DONE] Composer constructor
08-26 14:59:43.234  6407  6407 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-26 14:59:43.234  6407  6407 I Mms/ReservationManager: ReservationManager()
08-26 14:59:43.234  6407  6407 I Mms/ReservationManager: resetAfterConnected()
08-26 14:59:43.234  1484  1810 D TP/MmsSmsProvider: query,matched:7, calling pid = 6407
08-26 14:59:43.234  1484  1810 D TP/MmsSmsProvider: match 7:Elapsed time : 1.255 ms
08-26 14:59:43.244  6407  6407 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-26 14:59:43.244  6407  6407 D Mms/MmsApp: [end]    onCreate() consume time = 92.576563
08-26 14:59:43.254  1857  6462 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1857, getuid(): 10011
08-26 14:59:43.254  6407  6632 D Mms/Conversation: [start]    init() consume time = 7.284947
08-26 14:59:43.254  1484  1499 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-26 14:59:43.254  1484  1499 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-26 14:59:43.254  1484  1499 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-26 14:59:43.254  1484  1499 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-26 14:59:43.254  6407  6407 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-26 14:59:43.254  6407  6407 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-26 14:59:43.254  6407  6407 D Mms/MethodReflector: getSubId is called
08-26 14:59:43.254  6407  6407 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 14:59:43.264  1484  1499 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 14:59:43.264  1484  1499 D TP/MmsSmsProvider: need read changed broadcast:false
08-26 14:59:43.264  6407  6407 D Mms/MethodReflector: getTelephonyProperty is called
08-26 14:59:43.264  6407  6407 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 14:59:43.264  6407  6407 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 14:59:43.264  6407  6632 D Mms/Conversation: [end]    init consume time = 10.78875
08-26 14:59:43.264  6407  6407 D Mms/DownloadManager: auto download without roaming -> true
08-26 14:59:43.264  6407  6407 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 14:59:43.264  6407  6407 D Mms/DownloadManager: mAutoDownload ------> true
08-26 14:59:43.264  6407  6632 D Mms/MessagingNotification: [start]    init() consume time = 2.588438
08-26 14:59:43.264  6407  6632 D Mms/MessagingNotification: [end]    init consume time = 1.535625
08-26 14:59:43.274  1484  1810 D TP/MmsSmsProvider: query,matched:0, calling pid = 6407
08-26 14:59:43.274  1484  1810 V TP/MmsSmsProvider: getSimpleConversations entered.
08-26 14:59:43.274  1484  1810 D TP/MmsSmsProvider: match 0:Elapsed time : 1.148 ms
08-26 14:59:43.274  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.274  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.274  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
--------- beginning of system
08-26 14:59:43.274  1018  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 14:59:43.284  6407  6634 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 13.260052
08-26 14:59:43.284  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.284  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.284  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:59:43.284  6407  6635 D Mms/Synchronizer: [start]    doSync consume time = 1.664583
08-26 14:59:43.284  1484  1679 D TP/MmsSmsProvider: query,matched:400, calling pid = 6407
08-26 14:59:43.284  6407  6407 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-26 14:59:43.284  1018  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:59:43.284  1018  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 14:59:43.284  1018  1497 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-26 14:59:43.284  1018  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.284  1018  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.284  1018  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.284  1018  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.294  6407  6569 D Mms/ArtClassLoader: init [DONE] art
08-26 14:59:43.304  6638  6638 E Zygote  : MountEmulatedStorage()
08-26 14:59:43.304  6638  6638 E Zygote  : v2
08-26 14:59:43.304  6638  6638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:43.304  6638  6638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:43.304  1484  5710 D TP/MmsSmsProvider: update, matched:300, calling pid = 6407
08-26 14:59:43.304  1484  5710 V TP/MmsSmsProvider: syncDBData start
08-26 14:59:43.304  1484  5710 V TP/MmsSmsProvider: syncDBData sms end
08-26 14:59:43.304  1484  5710 V TP/MmsSmsProvider: syncDBData mms end
08-26 14:59:43.304  1484  5710 V TP/MmsSmsProvider: syncDBData end
08-26 14:59:43.304  6638  6638 I libpersona: KNOX_SDCARD checking this for 10068
08-26 14:59:43.304  6638  6638 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:43.304  1018  1497 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6638 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 14:59:43.304  1018  1321 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-26 14:59:43.304  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-26 14:59:43.314  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.314  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:59:43.314  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-26 14:59:43.314  6638  6638 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 14:59:43.314  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.314  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.314  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:43.314  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 14:59:43.324  6407  6635 D Mms/Synchronizer: [end]    doSync consume time = 38.334219
08-26 14:59:43.324  1018  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-26 14:59:43.324  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.324  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.324  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.324  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.334  6653  6653 E Zygote  : MountEmulatedStorage()
08-26 14:59:43.334  6653  6653 E Zygote  : v2
08-26 14:59:43.334  6653  6653 I libpersona: KNOX_SDCARD checking this for 10042
08-26 14:59:43.334  6653  6653 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:43.334  6653  6653 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:43.334  1018  1458 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6653 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-26 14:59:43.344  6638  6638 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:43.344  6638  6638 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:43.344  6653  6653 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:43.344  6653  6653 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-26 14:59:43.344  6407  6634 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 26.905938
08-26 14:59:43.364  6653  6653 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:43.364  6653  6653 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:43.374  6407  6659 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-26 14:59:43.374  6407  6659 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-26 14:59:43.374  1018  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:59:43.374  1018  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 14:59:43.374  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.374  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.374  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:59:43.384  1018  3340 I ActivityManager: Killing 6255:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-26 14:59:43.384  1018  3340 I ActivityManager: Killing 6234:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #22
08-26 14:59:43.394   295   295 E SMD     : DCD OFF
08-26 14:59:43.394  6638  6638 D BadgeProvider: onCreate
08-26 14:59:43.394  6638  6638 D BadgeProvider: DatabaseHelper
08-26 14:59:43.414  6653  6653 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:59:43.414  6653  6653 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:59:43.414  6653  6653 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 14:59:43.504  1018  1042 W libprocessgroup: failed to kill pid 6234: No such process
08-26 14:59:43.574  1018  1321 I art     : Explicit concurrent mark sweep GC freed 147190(8MB) AllocSpace objects, 3(1913KB) LOS objects, 33% free, 23MB/34MB, paused 2.549ms total 172.973ms
08-26 14:59:43.574  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 14:59:43.574  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.574  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.574  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:59:43.594  6653  6653 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-26 14:59:43.604  6670  6670 D AndroidRuntime: 
08-26 14:59:43.604  6670  6670 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:59:43.604  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-26 14:59:43.604  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 14:59:43.604  6670  6670 D AndroidRuntime: CheckJNI is OFF
08-26 14:59:43.604  6670  6670 D AndroidRuntime: readGMSProperty: start
08-26 14:59:43.604  6670  6670 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:59:43.604  6670  6670 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:59:43.604  6670  6670 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:59:43.604  6670  6670 D AndroidRuntime: readGMSProperty: end
08-26 14:59:43.604  6670  6670 D AndroidRuntime: addProductProperty: start
08-26 14:59:43.634  1018  1497 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 14:59:43.634   289   289 E installd: system dir 0 : /system/app/
08-26 14:59:43.634   289   289 E installd: system dir 1 : /system/priv-app/
08-26 14:59:43.634   289   289 E installd: system dir 2 : /vendor/app/
08-26 14:59:43.634   289   289 E installd: system dir 3 : /oem/app/
08-26 14:59:43.644  1018  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 14:59:43.644  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:43.644  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:43.644  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-26 14:59:43.654  6407  6632 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 14:59:43.654  1484  1496 D TP/SmsProvider: query,matched:26, calling pid = 6407
08-26 14:59:43.654  1484  1496 D TP/SmsProvider: match 26:Elapsed time : 1.408 ms
08-26 14:59:43.674  1484  1499 D TP/MmsSmsProvider: query,matched:6, calling pid = 6407
08-26 14:59:43.674  1484  1499 D TP/MmsSmsProvider: match 6:Elapsed time : 1.665 ms
08-26 14:59:43.694  1018  1458 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-26 14:59:43.694  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.694  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.694  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.694  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.714  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-26 14:59:43.714  6682  6682 E Zygote  : MountEmulatedStorage()
08-26 14:59:43.714  6682  6682 I libpersona: KNOX_SDCARD checking this for 10023
08-26 14:59:43.714  6682  6682 E Zygote  : v2
08-26 14:59:43.714  6682  6682 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:43.714  6682  6682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:43.724  1018  1458 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6682 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-26 14:59:43.724  6682  6682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:43.724  6682  6682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:59:43.754   322   322 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 632us total 33.590ms
08-26 14:59:43.764  6670  6670 E AffinityControl: AffinityControl: registerfunction enter
08-26 14:59:43.774   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 19.229ms
08-26 14:59:43.774  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:43.774  6682  6682 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:43.784  1018  1506 I ActivityManager: Killing 5955:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-26 14:59:43.794  6670  6670 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 14:59:43.804   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 19.570ms
08-26 14:59:43.824  1857  6488 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 161.419ms
08-26 14:59:43.824  6389  6449 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 1024 ms] updated apps [took 1024 ms] 
08-26 14:59:43.834  1018  1521 E PersonaManagerService: inState():  stateMachine is null !!
08-26 14:59:43.834  1018  1521 I PersonaManagerService: PersonaId don't exist
08-26 14:59:43.834  1018  1521 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 14:59:43.834  1018  3340 I ActivityManager: Killing 6326:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-26 14:59:43.844  1018  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:59:43.854  1018  1521 W ActivityManager: mDVFSHelper.acquire()
08-26 14:59:43.864  1018  1521 D FocusedStackFrame: Set to : 0
08-26 14:59:43.864  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.864  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.864  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.864  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:43.874  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 14:59:43.874  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 14:59:43.884  6701  6701 E Zygote  : MountEmulatedStorage()
08-26 14:59:43.884  6701  6701 E Zygote  : v2
08-26 14:59:43.884  6701  6701 I libpersona: KNOX_SDCARD checking this for 10170
08-26 14:59:43.884  6701  6701 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:43.884  6701  6701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:43.884  6701  6701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:43.884  6701  6701 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 14:59:43.884  1018  1521 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6701 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:59:43.894  1018  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 14:59:43.894  1018  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:59:43.894  1018  1521 D InputDispatcher: Focused application set to: xxxx
08-26 14:59:43.894  1018  1521 D InputDispatcher: Focus left window: 1508
08-26 14:59:43.894  6670  6670 D AndroidRuntime: Shutting down VM
08-26 14:59:43.904  6682  6682 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-26 14:59:43.904  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:59:43.904  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 14:59:43.904   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 14:59:43.934  6701  6701 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:43.934  6701  6701 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:43.934  6407  6632 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 14:59:43.944  1018  1544 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 14:59:43.944  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:59:43.944  6490  6561 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-26 14:59:43.944  6490  6561 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 14:59:43.944  6490  6561 I GAv4    :   adb logcat -s GAv4
08-26 14:59:43.954  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:59:43.954  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:43.954  1018  1018 V ActivityManager: Display changed displayId=0
08-26 14:59:43.964  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 14:59:43.964  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 14:59:43.974  1018  1544 D PersonaManager: isKioskContainerExistOnDevice
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 14:59:43.984  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 14:59:44.004  6490  6561 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 14:59:44.004  1018  1506 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 14:59:44.014  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 14:59:44.014   258   440 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-26 14:59:44.014   258  1976 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-26 14:59:44.024  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 14:59:44.024  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 14:59:44.024  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 14:59:44.024  6682  6682 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-26 14:59:44.034  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{130a44cd token=android.os.BinderProxy@e52e0ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 14:59:44.034  1508  1508 D Launcher: onTrimMemory. Level: 20
08-26 14:59:44.074  6490  6561 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-26 14:59:44.094  1857  6462 I qtaguid : Untagging socket 101
08-26 14:59:44.104  6670  6670 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 14:59:44.114  1857  1857 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 14:59:44.114  1857  1857 I ConfigFetchService: stopping self
,08-26 14:59:44.114  6490  6561 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-26 14:59:44.124  6490  6719 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:59:44.144  6701  6701 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 14:59:44.154  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:59:44.164  6701  6701 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5646-5648)
,08-26 14:59:44.164  6701  6701 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 14:59:44.234  6701  6701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26c08a28}
,08-26 14:59:44.234  6701  6701 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 14:59:44.234  6701  6701 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:59:44.284  6701  6701 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 14:59:44.284  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:59:44.284  6701  6701 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 14:59:44.304  6701  6701 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:59:44.304  6701  6701 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:59:44.304  6701  6701 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:59:44.304  6701  6701 I Adreno-EGL: Local Branch: 
08-26 14:59:44.304  6701  6701 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:59:44.304  6701  6701 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:59:44.304  6701  6701 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:59:44.314  1018  3340 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-26 14:59:44.314  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:44.314  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:44.314  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:44.314  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:44.334  6732  6732 E Zygote  : MountEmulatedStorage()
08-26 14:59:44.334  6732  6732 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:59:44.334  6732  6732 E Zygote  : v2
08-26 14:59:44.334  6732  6732 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:44.334  6732  6732 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:44.334  1018  3340 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6732 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 14:59:44.334  6732  6732 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:44.334  1018  3340 I ActivityManager: Killing 6356:com.sec.spp.push/u0a32 (adj 15): empty #21
08-26 14:59:44.334  6732  6732 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:44.374  6732  6732 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:44.374  6732  6732 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:44.404  6701  6701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 14:59:44.414  6732  6732 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-26 14:59:44.424  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:59:44.424  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 14:59:44.424  6732  6732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-26 14:59:44.424  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:59:44.424  1018  1137 D BatteryService: stay LED for charging
08-26 14:59:44.424  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:59:44.424  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-26 14:59:44.424  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-26 14:59:44.424  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:44.424  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:59:44.424  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-26 14:59:44.434  1018  1018 I MotionRecognitionService: Plugged
,08-26 14:59:44.434  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:59:44.434  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:59:44.434  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:59:44.434  6732  6732 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-26 14:59:44.434  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:59:44.434  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 14:59:44.434  6701  6701 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 14:59:44.434  6701  6701 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>,
,08-26 14:59:44.444  1018  3340 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-26 14:59:44.444  6701  6701 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 14:59:44.444  6701  6701 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 14:59:44.444  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:59:44.444  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:59:44.454  6732  6759 E FilterInstaller: installFilters
,08-26 14:59:44.454  6732  6759 E FilterInstaller: There is no requred permission
,08-26 14:59:44.454  1018  1521 I ActivityManager: Killing 4738:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-26 14:59:44.464  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 14:59:44.464  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 14:59:44.464  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 14:59:44.464  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 14:59:44.464  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 14:59:44.464  6490  6730 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 14:59:44.464  6490  6730 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 14:59:44.484  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{305ea660 u0 com.test.thalitest/.MainActivity t163}
,08-26 14:59:44.504  6490  6730 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 14:59:44.574  6490  6730 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:59:44.574  6490  6730 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@378ec6de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 14:59:44.574  6490  6730 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 14:59:44.574  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:59:44.584  6701  6701 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 14:59:44.594  6701  6701 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 14:59:44.594  6701  6701 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 14:59:44.604  6701  6701 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 14:59:44.604  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:59:44.604  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:59:44.654  6701  6767 D OpenGLRenderer: Render dirty regions requested: true
,08-26 14:59:44.664  1018  1497 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 14:59:44.664  1018  1497 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 14:59:44.664  1018  1497 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:59:44.664  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 14:59:44.664  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:59:44.664  6701  6751 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 14:59:44.674  6701  6701 V ActivityThread: updateVisibility : ActivityRecord{12c3c88 token=android.os.BinderProxy@20c424a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 14:59:44.674  6701  6701 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:59:44.674  6701  6701 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 14:59:44.684   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 14:59:44.714  1018  1031 D InputDispatcher: Focus entered window: 6701
,08-26 14:59:44.714  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:59:44.714  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101,
08-26 14:59:44.714  6701  6701 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 14:59:44.714  6701  6767 I OpenGLRenderer: Initialized EGL, version 1.4,
,08-26 14:59:44.714  6701  6767 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 14:59:44.714  6701  6767 D OpenGLRenderer: Enabling debug mode 0
,08-26 14:59:44.774  1018  1497 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:59:44.784  1178  1178 D PanelView: There is/are notification(s) 
,08-26 14:59:44.784  1018  6771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:59:44.804  1018  1048 I ActivityManager: Displayed Component not be shown by security: +814ms (total +934ms)
,08-26 14:59:44.804  1018  1048 W ActivityManager: mDVFSHelper.release()
08-26 14:59:44.804  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{305ea660 u0 com.test.thalitest/.MainActivity t163} time:96284
,08-26 14:59:44.814  6701  6701 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
08-26 14:59:44.814   258   446 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 14:59:44.814   258   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 14:59:44.814  6701  6701 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20c424a5 time:96299
,08-26 14:59:44.834  1857  4046 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-26 14:59:44.844  1980  1980 I SamsungIME: getCurrentCandidateView
,08-26 14:59:44.884  1857  4046 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-26 14:59:44.914  6701  6701 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6701
,08-26 14:59:44.944  1980  1980 D SamsungIME: Dismiss ExpandCandiate
,08-26 14:59:44.944  1857  4046 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-26 14:59:44.964  1018  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-26 14:59:44.964  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:44.964  1018  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:44.964  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:44.964  1018  1458 I ActivityManager: Killing 6340:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-26 14:59:45.094  1980  1980 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:59:45.094  6701  6701 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:59:45.114  6425  6450 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-26 14:59:45.134  1980  1980 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:59:45.134  6425  6450 I AcmsKeyStoreHelper: Key Store exist
08-26 14:59:45.134  6425  6450 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-26 14:59:45.154  1980  1980 I SamsungIME: KeybaordView init() : load resources
,08-26 14:59:45.174  1980  1980 I SamsungIME: getCurrentKeyboard
08-26 14:59:45.174  1980  1980 I SamsungIME: getTextKeyboard
,08-26 14:59:45.194  6701  6776 D jxcore_app_log: JniHelper::setJavaVM(0xb82c12b0), pthread_self() = -1199244968,
,08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 14:59:45.194  6701  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a0cc1e added. We now have 1 listener(s)
,08-26 14:59:45.204  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41,
,08-26 14:59:45.204  6701  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 14:59:45.204  6701  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:59:45.204  6701  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:59:45.204  6425  6450 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-26 14:59:45.204  6425  6450 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-26 14:59:45.204  6425  6450 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-26 14:59:45.204  6425  6450 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 14:59:45.204  6425  6450 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-26 14:59:45.204  6425  6450 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-26 14:59:45.204  6425  6450 D AcmsCore: This is NOT a valid MirrorLink app
08-26 14:59:45.204  6425  6450 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-26 14:59:45.204  6425  6450 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 14:59:45.204  6425  6450 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-26 14:59:45.204  6425  6450 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-26 14:59:45.214  1980  1980 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 14:59:45.214  6425  6425 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 14:59:45.214  6425  6425 D AcmsService: Enter onDestroy
08-26 14:59:45.214  6425  6425 I AcmsService: cleanUp(): inside service clean up
08-26 14:59:45.214  6425  6425 D AcmsCore: AcmsCore: inside DeInit
08-26 14:59:45.214  6425  6425 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-26 14:59:45.214  6425  6425 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-26 14:59:45.214  6425  6425 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-26 14:59:45.214  6425  6425 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-26 14:59:45.214  6425  6425 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-26 14:59:45.214  6425  6425 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 14:59:45.214  6425  6425 D AcmsService: killing acms process
08-26 14:59:45.214  6425  6425 I Process : Sending signal. PID: 6425 SIG: 9
,08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 14:59:45.214  6701  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27408115 added. We now have 1 listener(s)
,08-26 14:59:45.214  6701  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:59:45.224  6701  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-26 14:59:45.234  6701  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:59:45.234  6701  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:59:45.234  6701  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:59:45.234  6701  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:59:45.234  6701  6776 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:59:45.234  6701  6701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:45.244  6701  6701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:45.254  6407  6407 I Mms/MmsApp:  start initViewCache mms,
,08-26 14:59:45.254  6407  6407 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1903.735624
,08-26 14:59:45.254  6407  6407 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-26 14:59:45.274  6701  6701 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:59:45.294  1018  3337 I ActivityManager: Process ACMS.Process (pid 6425)(adj 0) has died(26,772)
,08-26 14:59:45.374  6407  6407 D AbsListView: Get MotionRecognitionManager
,08-26 14:59:45.374  1018  1521 D MotionRecognitionService:  ssp status : false
,08-26 14:59:45.374  6407  6407 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 123.95125
,08-26 14:59:45.454  6407  6407 D Mms/BubbleViewCache: fillCache bubble = 1
,08-26 14:59:45.774  6701  6783 W jxcore-log: Initializing JXcore engine
08-26 14:59:45.774  6701  6783 W jxcore-log: JXcore engine is ready
08-26 14:59:45.834  1975  1975 E audit   : type=1400 msg=audit(1472216385.834:205): avc:  denied  { ioctl } for  pid=6783 comm="Thread-1246" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 14:59:45.834  1975  1975 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:45.834  1975  1975 E audit   : type=1300 msg=audit(1472216385.834:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e3fb8f8 items=0 ppid=322 ppcomm=main pid=6783 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1246" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 14:59:45.834  1975  1975 E audit   : type=1320 msg=audit(1472216385.834:205): 
08-26 14:59:45.844  6701  6783 W jxcore-log: Starting JXcore engine
08-26 14:59:45.894   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85eb7c8
08-26 14:59:45.894   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 14:59:45.894   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 14:59:45.894   273   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201751928)
08-26 14:59:45.924  1018  2884 D SSRM:n  : SIOP:: AP = 420
08-26 14:59:45.944   273   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-26 14:59:45.944   273   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 14:59:45.944   273   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201751928) wakelock released: 1, error no: 0
08-26 14:59:45.944   273   302 I rmt_storage: 
08-26 14:59:45.944   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb85eb7c8
08-26 14:59:45.964  6701  6783 W jxcore-log: Platform android
08-26 14:59:45.964  6701  6783 W jxcore-log: 
08-26 14:59:45.964  6701  6783 W jxcore-log: Process ARCH arm
08-26 14:59:45.964  6701  6783 W jxcore-log: 
08-26 14:59:46.174  6701  6783 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:59:46.174  6701  6783 I jxcore-log: 
08-26 14:59:46.174  6701  6783 W jxcore-log: JXcore engine is started
08-26 14:59:46.174  6701  6776 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 14:59:46.184  6701  6701 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:59:46.404   295   295 E SMD     : DCD OFF,
,08-26 14:59:49.124  1689  1689 I ConfigService: onDestroy
,08-26 14:59:49.404   295   295 E SMD     : DCD OFF
,08-26 14:59:52.404   295   295 E SMD     : DCD OFF
,08-26 14:59:53.784  1018  1058 D PackageManager: [MSG] MCS_UNBIND
,08-26 14:59:53.784  1018  1511 I ActivityManager: Killing 6372:com.samsung.helphub/1000 (adj 15): empty #21
,08-26 14:59:53.864  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 14:59:54.464  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:59:54.464  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 14:59:54.464  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 14:59:54.464  1018  1521 D BatteryService: stay LED for charging
08-26 14:59:54.464  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:59:54.464  1018  1018 I MotionRecognitionService: Plugged
,08-26 14:59:54.464  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:59:54.464  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:59:54.474  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:59:54.474  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:59:54.474  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 14:59:54.484  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:59:54.484  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:59:54.494  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 14:59:54.494  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 14:59:54.494  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 14:59:54.494  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 14:59:54.494  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 14:59:55.404   295   295 E SMD     : DCD OFF,
,08-26 14:59:55.944  1018  2884 D SSRM:n  : SIOP:: AP = 400
,08-26 14:59:55.964  1018  1050 I PowerManagerService: [PWL] Off : 30s ago
,08-26 14:59:56.484  1018  1329 E Watchdog: !@Sync 3,
,08-26 14:59:56.944  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{1ccce79c u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-26 14:59:57.904  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-26 14:59:57.914  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,08-26 14:59:57.924  1018  1392 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:59:57.934  1018  1392 D AlarmManagerService: Setting time of day to sec=1472216398
08-26 14:59:57.934  1018  1392 D AlarmManagerService: Trying to open a file
,08-26 14:59:57.934  1018  1392 D AlarmManagerService: File Open Success
08-26 14:59:57.934  1018  1392 D AlarmManagerService: File Close Success
08-26 14:59:57.934  1018  1392 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,08-26 14:59:58.530  1018  1392 W AlarmManagerService: Unable to set rtc to 1472216398: Invalid argument
08-26 14:59:58.530  1018  1096 V AlarmManager: waitForAlarm result :65536
,08-26 14:59:58.530  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=109426 batch.start=110888
,08-26 14:59:58.539  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,08-26 14:59:58.549  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 14:59:58.549  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 14:59:58.559  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 14:59:58.569  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:59:58.569  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,08-26 14:59:58.579  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,08-26 14:59:58.589  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-26 14:59:58.589  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472216398593
,08-26 14:59:58.589  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:59:58.589  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:59:58.589  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-26 14:59:58.589  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-26 14:59:58.589  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:59:58.589  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:59:58.599  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 14:59:58.599  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 14:59:58.609  1018  1321 D SettingsProvider: name = lockscreen_zoom_panning_effect
,08-26 14:59:58.609  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:59:58.609  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:59:58.609  1018  1321 D SettingsProvider: selectionArgs: false
08-26 14:59:58.609  1018  1321 D SettingsProvider: selectionArgs: 10049
08-26 14:59:58.609  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:59:58.609  1018  1321 D SettingsProvider: ret = -1
,08-26 14:59:58.609  1018  1018 I DrmEventService:  no response from SecureClock 
,08-26 14:59:58.609  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-26 14:59:58.609  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-26 14:59:58.609  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-26 14:59:58.609  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-26 14:59:58.609  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 14:59:58.609  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:58.609  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:58.609  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:58.609  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:58.629  1018  1321 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 14:59:58.629  6791  6791 E Zygote  : MountEmulatedStorage()
08-26 14:59:58.629  6791  6791 E Zygote  : v2
08-26 14:59:58.629  6791  6791 I libpersona: KNOX_SDCARD checking this for 10008
08-26 14:59:58.629  6791  6791 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:58.629  6791  6791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 14:59:58.629  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6791 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:59:58.639  1018  1018 I BackgroundCompactionService: onStart. jobID=801
,08-26 14:59:58.639  1178  1178 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false,
,08-26 14:59:58.639  6791  6791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:58.639  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
,08-26 14:59:58.639  6791  6791 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 14:59:58.639  1178  1178 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-26 14:59:58.639  1178  1178 I GeometricMosaic_Keyguard: update
,08-26 14:59:58.649  1018  6797 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-26 14:59:58.649  1018  6797 I BackgroundCompactionService: compact_memory command done
,08-26 14:59:58.649  1178  1178 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-26 14:59:58.679  6791  6791 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 14:59:58.679  6791  6791 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:58.709   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 14:59:58.709   336   336 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 14:59:58.729  1178  1178 I KeyguardEffectViewUtil: set current wallpaper info,
08-26 14:59:58.729  1018  1424 D SettingsProvider: name = keyguard_current_wallpaper_type
08-26 14:59:58.729  1018  1424 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:59:58.729  1018  1424 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:59:58.729  1018  1424 D SettingsProvider: selectionArgs: false
08-26 14:59:58.729  1018  1424 D SettingsProvider: selectionArgs: 10049
08-26 14:59:58.729  1018  1424 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:59:58.729  1018  1424 D SettingsProvider: ret = -1
,08-26 14:59:58.729  1018  1424 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 14:59:58.739  1018  1030 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,08-26 14:59:58.739  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:59:58.739  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:59:58.739  1018  1030 D SettingsProvider: selectionArgs: false
,08-26 14:59:58.739  1018  1030 D SettingsProvider: selectionArgs: 10049
08-26 14:59:58.739  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:59:58.739  1018  1030 D SettingsProvider: ret = -1
,08-26 14:59:58.739  1018  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 14:59:58.749  1018  1030 D SettingsProvider: name = keyguard_current_wallpaper_res_id
,08-26 14:59:58.749  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:59:58.749  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:59:58.749  1018  1030 D SettingsProvider: selectionArgs: false
,08-26 14:59:58.749  1018  1030 D SettingsProvider: selectionArgs: 10049
08-26 14:59:58.749  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:59:58.749  1018  1030 D SettingsProvider: ret = -1
,08-26 14:59:58.759  1018  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 14:59:58.779  6791  6791 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 14:59:58.799  6791  6791 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-26 14:59:58.809  1018  1506 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:58.809  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-26 14:59:58.809  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:58.809  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:58.809  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:58.839  1178  1591 D TEST    : run!!!
,08-26 14:59:58.849  1178  1591 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-26 14:59:58.859  1018  3340 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:59:58.859  1018  3340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-26 14:59:58.869  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:58.869  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:59:58.869  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:59:58.869  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 14:59:58.869  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 14:59:58.879  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 14:59:58.879  2941  2941 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Aug 26 14:59:58 GMT+02:00 2016
,08-26 14:59:58.879  1018  1544 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 14:59:58.879  1018  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 14:59:58.889  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:58.889  1018  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:59:58.889  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 14:59:58.889  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 14:59:58.889  2941  2941 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 14:59:58.889  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 14:59:58.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:58.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:58.899  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:58.899  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:58.899  1178  1178 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-26 14:59:58.909  6810  6810 E Zygote  : MountEmulatedStorage()
08-26 14:59:58.909  6810  6810 E Zygote  : v2
08-26 14:59:58.909  6810  6810 I libpersona: KNOX_SDCARD checking this for 10036
08-26 14:59:58.909  6810  6810 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:58.909  6810  6810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:58.909  2941  2941 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
08-26 14:59:58.909  6810  6810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:59:58.909  6810  6810 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,08-26 14:59:58.909  1018  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6810 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:59:58.929  2941  2941 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 14:59:58.929  2941  2941 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 14:59:58.939  2941  6809 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-26 14:59:58.939  2941  6809 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-26 14:59:58.939  2941  6809 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Fri Aug 26 14:59:58 GMT+02:00 2016
,08-26 14:59:58.939  6810  6810 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:58.939  6810  6810 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:58.979  2941  6809 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-26 14:59:58.979  2941  2941 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 14:59:58.989  6810  6810 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@c78a910
,08-26 14:59:58.989   295   295 E SMD     : DCD OFF,
,08-26 14:59:58.999  6810  6810 I SA      : [SSP] onCreated
,08-26 14:59:59.009  6810  6810 I SA      : [TPM] There is no property file
,08-26 14:59:59.009  6810  6810 I SA      : [SCU] isHaveSA() - false
,08-26 14:59:59.019  6810  6810 I SA      : [TPM] getModelProperty : null
08-26 14:59:59.019  6810  6810 I SA      : [TPM] getCSCProperty : null
,08-26 14:59:59.019  6810  6810 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 14:59:59.019  6810  6810 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 14:59:59.019  6810  6810 I SA      : [DM] TFT FEATURE: false
,08-26 14:59:59.019  6810  6810 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-26 14:59:59.019  6810  6810 I SA      : [DM] init START
,08-26 14:59:59.029  6810  6810 I SA      : [DM] This device is not a Vodafone
,08-26 14:59:59.039  5838  5951 D Finsky  : [1054] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 14:59:59.039  5838  5838 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 14:59:59.039  6810  6810 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 14:59:59.049  1018  1030 I ActivityManager: Killing 5547:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 14:59:59.049  6810  6810 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 14:59:59.059  6810  6810 I SA      : [SCU] isHaveSA() - false
08-26 14:59:59.059  6810  6810 I SA      : support phone number id : false
08-26 14:59:59.059  6810  6810 I SA      : [DM] Supports Ref Jpn : true
,08-26 14:59:59.059  6810  6810 I SA      : [DM] init END
,08-26 14:59:59.089  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-26 14:59:59.089  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.089  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.089  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.099  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.109  6829  6829 E Zygote  : MountEmulatedStorage(),
08-26 14:59:59.109  6829  6829 I libpersona: KNOX_SDCARD checking this for 10058
08-26 14:59:59.109  6829  6829 E Zygote  : v2
08-26 14:59:59.109  6829  6829 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.109  6829  6829 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:59.109  1018  1137 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6829 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:59:59.109  1018  1137 I ActivityManager: Killing 6389:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 14:59:59.109  6829  6829 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:59:59.109  6829  6829 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:59.139  6829  6829 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.139  6829  6829 D ActivityThread: Added TimaKeyStore provider,
,08-26 14:59:59.189  6829  6829 I ExternalOEMControlProvider: onCreate
,08-26 14:59:59.209  1018  1521 I ActivityManager: Killing 5895:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 14:59:59.209  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
08-26 14:59:59.209  6829  6844 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-26 14:59:59.209  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 14:59:59.209  1018  1424 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-26 14:59:59.209  1018  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.209  1018  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.209  1018  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.209  1018  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.219  6845  6845 E Zygote  : MountEmulatedStorage()
08-26 14:59:59.219  6845  6845 E Zygote  : v2
,08-26 14:59:59.219  6845  6845 I libpersona: KNOX_SDCARD checking this for 10081
08-26 14:59:59.219  6845  6845 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.229  6845  6845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:59.229  1018  1424 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6845 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:59:59.229  6845  6845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:59:59.229  6845  6845 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:59.249  6845  6845 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.249  6845  6845 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.259  6845  6845 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 14:59:59.259  6845  6845 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:59:59.259  6845  6845 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:59:59.259  6845  6845 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:59:59.259  6845  6845 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 14:59:59.339  1018  1544 D SettingsProvider: name = next_alarm_formatted
,08-26 14:59:59.339  1018  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:59:59.339  1018  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:59:59.339  1018  1544 D SettingsProvider: selectionArgs: false
08-26 14:59:59.339  1018  1544 D SettingsProvider: selectionArgs: 10081
08-26 14:59:59.339  1018  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:59:59.339  1018  1544 D SettingsProvider: ret = -1
,08-26 14:59:59.449  6845  6845 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 102.981ms
,08-26 14:59:59.549  1018  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 14:59:59.549  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.549  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.549  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.549  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.559  6860  6860 E Zygote  : MountEmulatedStorage(),
08-26 14:59:59.559  1018  1458 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6860 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-26 14:59:59.559  6860  6860 E Zygote  : v2
08-26 14:59:59.559  6860  6860 I libpersona: KNOX_SDCARD checking this for 10090
08-26 14:59:59.559  6860  6860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:59.559  6860  6860 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.559  1018  1458 I ActivityManager: Killing 6472:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-26 14:59:59.569  6860  6860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:59:59.569  6860  6860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:59.589  6860  6860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.589  6860  6860 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.609  6860  6860 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-26 14:59:59.609  6860  6860 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 14:59:59.619  6860  6860 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 14:59:59.619  1018  1497 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 14:59:59.619  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 14:59:59.619  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:59.619  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:59:59.619  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 14:59:59.619  6860  6860 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-26 14:59:59.619  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-26 14:59:59.619  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.619  6860  6860 D elm:15121: ElmAgentService : onCreate()
08-26 14:59:59.619  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.619  6860  6875 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
08-26 14:59:59.619  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.619  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.629  6860  6875 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-26 14:59:59.629  6860  6860 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-26 14:59:59.639  6877  6877 E Zygote  : MountEmulatedStorage(),
08-26 14:59:59.639  6877  6877 E Zygote  : v2
08-26 14:59:59.639  6877  6877 I libpersona: KNOX_SDCARD checking this for 10130
08-26 14:59:59.639  6877  6877 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.639  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:59.639  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:59:59.639  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-26 14:59:59.639  1018  1321 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6877 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-26 14:59:59.639  6860  6860 D elm:15121: ModuleBase.ModifySetAlarm()
08-26 14:59:59.649  6860  6860 D elm:15121: MDMBridge.getInstance()
08-26 14:59:59.649  6860  6860 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 14:59:59.649  6860  6860 D elm:15121: ElmAgentService : onDestroy().
,08-26 14:59:59.649  1018  1030 I ActivityManager: Killing 6454:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-26 14:59:59.669  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.669  6877  6877 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.679  6877  6877 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:59:59.679  6877  6877 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-26 14:59:59.699  1018  3337 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-26 14:59:59.699  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.699  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.699  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.699  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.709  6892  6892 E Zygote  : MountEmulatedStorage(),
08-26 14:59:59.719  6892  6892 E Zygote  : v2
08-26 14:59:59.719  6892  6892 I libpersona: KNOX_SDCARD checking this for 10131,
08-26 14:59:59.719  6892  6892 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.719  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:59.719  1018  3337 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6892 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,08-26 14:59:59.719  1018  3337 I ActivityManager: Killing 6490:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-26 14:59:59.719  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:59:59.719  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:59.739  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.739  6892  6892 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.759  6892  6892 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:59:59.759  6892  6892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:59:59.759  6892  6892 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:59:59.789  2691  2706 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 14:59:59.789  1018  1137 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-26 14:59:59.789  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 14:59:59.799  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:59.799  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:59:59.799  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 14:59:59.809  1018  1137 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 14:59:59.809  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 14:59:59.809  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:59.809  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:59:59.809  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 14:59:59.809  1018  3337 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-26 14:59:59.819  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.819  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.819  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.819  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.829  6913  6913 E Zygote  : MountEmulatedStorage(),
,08-26 14:59:59.829  6913  6913 E Zygote  : v2
08-26 14:59:59.829  6913  6913 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:59:59.829  6913  6913 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:59.839  1018  3337 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6913 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 14:59:59.839  6913  6913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:59.839  6913  6913 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 14:59:59.839  1018  1321 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-26 14:59:59.839  6913  6913 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:59:59.839  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.839  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.839  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.839  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.859  6923  6923 E Zygote  : MountEmulatedStorage()
,08-26 14:59:59.859  6923  6923 E Zygote  : v2
08-26 14:59:59.859  6923  6923 I libpersona: KNOX_SDCARD checking this for 10037
08-26 14:59:59.859  6923  6923 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.859  6923  6923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:59.859  1018  1321 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6923 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 14:59:59.859  6923  6923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:59:59.869  6923  6923 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-26 14:59:59.869  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:59.869  6913  6913 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.879   322   322 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.084ms total 25.082ms
,08-26 14:59:59.889  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.889  6923  6923 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.899   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 16.825ms
,08-26 14:59:59.899  6923  6923 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-26 14:59:59.919   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.778ms,
,08-26 14:59:59.919  6913  6913 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:59:59.919  6913  6913 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:59:59.919  6913  6913 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:59:59.929  1018  3340 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-26 14:59:59.929  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.929  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.929  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.929  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.929  6923  6923 I CalendarProvider2: CalendarProvider2.onCreate() called,
,08-26 14:59:59.949  6946  6946 E Zygote  : MountEmulatedStorage(),
08-26 14:59:59.949  6946  6946 E Zygote  : v2
08-26 14:59:59.949  6946  6946 I libpersona: KNOX_SDCARD checking this for 10153
,08-26 14:59:59.949  6946  6946 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:59.949  6946  6946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 14:59:59.949  6946  6946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:59:59.949  6946  6946 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:59:59.949  1018  3340 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6946 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-26 14:59:59.959  1018  3340 I ActivityManager: Killing 6531:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-26 14:59:59.969  6946  6946 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:59.969  6946  6946 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:59.989  6946  6946 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:59:59.989  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 14:59:59.999  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-26 14:59:59.999  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:59.999  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.999  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:59.999  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:00.009  6962  6962 E Zygote  : MountEmulatedStorage()
,08-26 15:00:00.009  1018  1031 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:00:00.009  6962  6962 E Zygote  : v2
08-26 15:00:00.009  6962  6962 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:00:00.009  6962  6962 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:00.009  1018  1031 I ActivityManager: Killing 6513:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-26 15:00:00.019  6962  6962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:00.019  6962  6962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:00.019  6962  6962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:00.039  6962  6962 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:00.039  6962  6962 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:00.049  1018  1424 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-26 15:00:00.049  1018  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-26 15:00:00.049  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:00.049  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:00.059  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 15:00:00.079  6962  6962 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472216400085
,08-26 15:00:00.079  6962  6962 D         : TimeServiceNative: User Time to be set is 1472216400085
08-26 15:00:00.079  6962  6962 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-26 15:00:00.079  6962  6962 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-26 15:00:00.079  6962  6962 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472216400085
,08-26 15:00:00.079   338   424 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472216400085
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472216400085, operation = 0
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/21/71 6:42:50
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:Value read from RTC seconds = 35966570000
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:new time 1472216400085 
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon: delta 1436249830085 genoff 1436249830085 
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249830085 to memory
,08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-26 15:00:00.079   338  6978 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-26 15:00:00.079  6962  6962 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-26 15:00:00.099   338  6978 D QC-time-services: Updating the TOD offset
08-26 15:00:00.099   338  6978 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249830085 to memory
08-26 15:00:00.099   338  6978 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-26 15:00:00.099   338  6978 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 15:00:00.109   338  6978 E QC-time-services: Daemon:Update to modem bit set
08-26 15:00:00.109   338  6978 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-26 15:00:00.109   338  6978 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285030085
,08-26 15:00:00.109  6962  6962 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-26 15:00:00.109   338   419 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-26 15:00:00.109   338   424 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 15:00:00.109  1018  1424 I ActivityManager: Killing 6554:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 15:00:00.119  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 15:00:00.119  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 15:00:00.119  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:00:00.119  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:00:00.129  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:00:00.129  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-26 15:00:00.129  2691  2691 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:00:00.129  2691  2691 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-26 15:00:00.129  2691  2691 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-26 15:00:00.129  2691  2691 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:00:00.129  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-26 15:00:00.129  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:00:00.139  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-26 15:00:00.139  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 15:00:00.139  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-26 15:00:00.139  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-26 15:00:00.149  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:00:00.149  2691  2691 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-26 15:00:00.159  2691  2691 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-26 15:00:00.159  2691  2691 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-26 15:00:00.179  1018  1030 I art     : Explicit concurrent mark sweep GC freed 24599(1424KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 2.498ms total 152.731ms
,08-26 15:00:00.229  1018  1031 I ActivityManager: Killing 6579:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-26 15:00:01.059  6923  6923 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-26 15:00:01.059  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:01.059  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.059  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-26 15:00:01.069  1018  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-26 15:00:01.069  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:01.069  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.069  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 15:00:01.069  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:01.069  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.069  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:00:01.069  1018  1511 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-26 15:00:01.069  1018  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 15:00:01.079  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:01.079  1018  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.079  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:00:01.079  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:01.079  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.079  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:00:01.089  1018  1544 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 15:00:01.089  1018  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 15:00:01.089  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:01.089  1018  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:01.089  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:00:01.099  1018  1321 I ActivityManager: Killing 6608:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-26 15:00:01.989   295   295 E SMD     : DCD OFF
,08-26 15:00:03.709   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:04.709   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:04.739  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:04.859  6701  6783 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:00:04.859  6701  6783 I jxcore-log: 
,08-26 15:00:04.859  6701  6783 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:00:04.859  6701  6783 I jxcore-log: 
,08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:00:04.869  6701  6783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:00:04.869  6701  6783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:00:04.869  6701  6783 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:00:04.869  6701  6783 I jxcore-log: 
,08-26 15:00:04.869  6701  6783 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:00:04.869  6701  6783 I jxcore-log: 
,08-26 15:00:04.989   295   295 E SMD     : DCD OFF
,08-26 15:00:05.089  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:05.089  1018  1458 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:00:05.089  1018  1458 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:00:05.089  1018  1458 D BatteryService: stay LED for charging
,08-26 15:00:05.099  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:05.099  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:00:05.099  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:00:05.099  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:05.099  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:05.109  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:00:05.109  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:05.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:05.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:05.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:05.119  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:05.119  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:05.129  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:00:05.129  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:05.349  6701  6783 I jxcore-log: Running unit tests
08-26 15:00:05.349  6701  6783 I jxcore-log: 
,08-26 15:00:05.359  6701  6783 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-26 15:00:05.359  6701  6783 I jxcore-log: Failed to execute UT.
08-26 15:00:05.359  6701  6783 I jxcore-log: 
,08-26 15:00:05.359  6701  6783 I jxcore-log: Unit Test app is loaded
08-26 15:00:05.359  6701  6783 I jxcore-log: 
,08-26 15:00:05.359  6701  6783 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:00:05.359  6701  6783 I jxcore-log: 
,08-26 15:00:05.369  6701  6701 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 15:00:05.369  6701  6783 I jxcore-log: My device name is: samsung-SM-A300FU
08-26 15:00:05.369  6701  6783 I jxcore-log: 
,08-26 15:00:05.369  6701  6783 I jxcore-log: WARN testUtils: myNameCallback not set!,
08-26 15:00:05.369  6701  6783 I jxcore-log: 
,08-26 15:00:05.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:05.989  6701  6783 W jxcore-log: !!! js_ReportOverRecursed called !!!,
,08-26 15:00:06.009  5984  5984 D FactoryTest: Not factory mode
,08-26 15:00:06.009  5984  5984 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 15:00:06.009  5984  5984 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
,08-26 15:00:06.009  5984  5984 D MTPRx   : still no open session command from host, so toast
,08-26 15:00:06.009  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 15:00:06.019  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 15:00:06.019  5984  5984 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116911
08-26 15:00:06.019  1018  1137 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 15:00:06.019  1018  1137 I PersonaManagerService: PersonaId don't exist
08-26 15:00:06.019  1018  1137 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 15:00:06.029  1018  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:00:06.029  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:06.029  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:06.029  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 15:00:06.039  1018  1137 W ActivityManager: mDVFSHelper.acquire()
,08-26 15:00:06.059  1018  1137 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:00:06.079  1018  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:00:06.079  1018  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:00:06.079  1018  1137 D InputDispatcher: Focused application set to: xxxx
08-26 15:00:06.079  1018  1137 D InputDispatcher: Focus left window: 6701
,08-26 15:00:06.079  5984  5984 E MTPRx   : started activity for popup
,08-26 15:00:06.089  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:00:06.089  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:00:06.109  6989  6989 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
08-26 15:00:06.109  6989  6989 W google-breakpad: V WebView:45.0.2454.95
08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:00:06.109  6989  6989 W google-breakpad: O A arm 04 samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
08-26 15:00:06.109  6989  6989 W google-breakpad: S 0 9E37D038 9E37D000 00008000
,08-26 15:00:06.109  5984  5984 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:00:06.139  5984  5984 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 15:00:06.139  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:00:06.139  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:00:06.139  1018  1031 D InputDispatcher: Focused application set to: xxxx
,08-26 15:00:06.139  1018  1031 D InputDispatcher: Focus entered window: 6701
,08-26 15:00:06.139  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:00:06.139  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D000 00B467B80000000085FFFFFF30EEA0B86CD0379E20B9F89C0000000030D0379E00B467B8000000006C87529D80D0379E7487529D6CD0379E07000000000000000000000090B8E0E6102FA39B85FFFFFFE01D819C00B467B8F0D0379E9CD0379E74D0379E85FFFFFF94D0379E209E179D102FA39BE01D819C0000000060D1379E9CD0379EF0D0379E7487529D102FA39BBCD0379E5847399DFC90A0B9000000000000000082FFFFFFF0D0379E60D1379EE0D0379E00B467B824D1379E1CDB319DE448529D504C529D584B689D22000000FC90A0B9E490A0B900000000F4D0379E102FA39B85FFFFFF00B467B800000000102FA39B85FFFFFFA8D1379E78D2379E1831699D70D1379E000000000100000060D1379E50D1379E2200000000B467B8B4D2379E2804359DB890A0B90000000000B467B840D1379E0200000088D1379EE01CF69BA8D1379E1023A09B88FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF00B467B8000000000000000000B467B801000000D8D2379E
,08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D180 E8D2379E01000000B890A0B9070000000700000001000000802DA39B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF00000000C890A0B922000000882DA39B0700000000000000010000001800809CE8BDEBB881FFFFFF14D2379EE01A229D07000000802DA39B00B467B8000000001000809C20D2379E54D2379EE85C229D0000000000000000000000000C440A9E88D2379E01000000000000009027A09BE01B819C802DA39B00000000FFFFFFFFE8BDEBB881FFFFFFF0D2379EB0440A9E48D3379E64D2379EB0D2379E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF802DA39B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB881FFFFFFF0D2379E385F619E00000000C4D2379E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF802DA39B85FFFFFF4CD3379E58BEEBB888DC669E01050000
,08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D300 802DA39B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFF7CD3379E94D3379E0000000070D3379E8C69619E820100008086769C010000000000000082FFFFFF802DA39B85FFFFFF1CD4379EC0B88FB92C5C639E010A0000802DA39B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFFE8BB4A9C020000000000000048D4379E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF802DA39B85FFFFFFA0F9E69B88FFFFFFBCD4379E285273B9BCFC4A9C81060000F0D9819C85FFFFFF802DA39B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF
08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D480 0000000082FFFFFF0000000082FFFFFFC1030000A0D4379E0000000083FFFFFF6800000060CA229A882DA39B010000003000000060CA229A00000000E0D4379E8C69619E820100004077D69B010000000000000082FFFFFF802DA39B85FFFFFF64D5379E58AAB2BAFCF44A9C81070000802DA39B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5379E78D5379E70D5379EE4D5379E7800000060CA229A00000000A66A14B9584B689D00B467B80000000088D5379E8C69619E820100008077D69B010000000000000082FFFFFF802DA39B85FFFFFFF4D5379EB8610BB9DCEA4A9C01060000802DA39B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000D6379E18D6379E040000006000000060CA229A48073DBA81FFFFFF84D6379EF81F619E0000000018D6379E8C69619E82010000
08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D600 A077D69B010000000000000082FFFFFF802DA39B85FFFFFF84D6379E20BF0DB9E0E14A9C01060000802DA39B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B83027A09B000000009808229B600000006027A09B04000000E8BB4A9C94D6379E7874049D04000000A8D6379E8C69619E82010000C077D69B010000000000000082FFFFFF3027A09B88FFFFFF24D7379ED0FF3CBAF4D84A9C010700003027A09B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF802DA39B85FFFFFF18D7379E18D7379E14D7379E88FFFFFF700000000027A09B103FA19B40E0729CC089729C000000000400000048D7379E8C69619E820100004078D69B0100000030A4079C88FFFFFF7023A09B88FFFFFFA4D7379E408E62BA60D24A9C010500007023A09B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFF103FA19B01000000
08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D780 D4D7379EECD7379E50000000509E5A9A02000000C8A95BB9C4D7379EC873049D00000000D8D7379EDCED2E9E8202000060980F9C030000000000000082FFFFFF7023A09B88FFFFFF0000000081FFFFFF103FA19B88FFFFFF74D8379E301412BAE852019E01090000103FA19B88FFFFFF0000000081FFFFFF7023A09B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF10150D9B88FFFFFF0000000082FFFFFF0900000081FFFFFF103FA19B88FFFFFF603FA19B00000000A4D8379EC0D6729C9000000020C0729CE8BB4A9C02000000002B66B981FFFFFF0000000098D8379E8C69619E82010000B002739C01000000103FA19B88FFFFFF60980F9C88FFFFFF1CD9379E002666B9D0CB4A9C8107000060980F9C88FFFFFF103FA19B88FFFFFFB002739C88FFFFFF603FA19B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFF603FA19B88FFFFFF0000000082FFFFFF40D9379E385F619E0000000004D9379E
08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37D900 78000000509E5A9A0000000024C24A9C42030000030000000000000048D9379E8C69619E0202000080980F9C02000000007AD39988FFFFFFE01CF69B88FFFFFF103FA19B88FFFFFFB4D9379EF04DACB9F0C64A9C01060000103FA19B88FFFFFFE01CF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFF78D9379EA035749CB02EA39B4011819C60000000509E5A9A85FFFFFFDC06969C85FFFFFFB4D9379E000000000037749CE811969C800B0000C0980F9C020000000037749C88FFFFFFE01CF69B88FFFFFF2039A19B88FFFFFFC02EA39B85FFFFFFC03EA19B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF9024A09B2039A19BA035749CE0D9AB9B8A0000004026A09BC02EA39BC03EA19B2039A19BA035749CB02EA39B8018809C40DAAB9B0900000040F9E69BD0B0729CD0B0729C2039A19B88FFFFFF090000004011819C090000000037749CE01CF69B4023A09B40F9E69B88FFFFFF00000000643D2A9E
08-26 15:00:06.149  6989  6989 W google-breakpad: S 9E37DA80 083F2A9E000400008036749C010000000037749C88FFFFFFE01CF69B88FFFFFF0000000082FFFFFFF09A719DE01CF69B1023A09BE022A09B0000000087FFFFFFA00F739CB022A09BE022A09B20F9E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFFB022A09B88FFFFFF30DB379EB022A09B5022A09B8022A09BFC700A9E800200000037749C000000005022A09B88FFFFFF8015A59B8A000000070000009015A59B00B467B840B0729CD0D9AB9B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFFD0D9AB9B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B608DD379E0100000081FFFFFF60DC379ECCDC379E14340A9D603F779C000000000000000030DC379EE4DB379E3897609E584B689D00B467B89835A6B84CED379E00000000000000000000000001000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37DC00 34E4379E00B467B80001000000000000B06F0A9E00000000603F779CC0E0379E020000000100000000000000000000000100000081FFFFFF000000000000000098E0379EF6FFFFFF0CB467B80100000000B467B860DC379E00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000008DD379E00B467B878AB719D80827A9C00000000108CA0B9CCDC379E7CD86A160000000000B467B808DD379ED0DC379E603F779C80827A9C00000000108CA0B9F4DC379E2CD5279D000000000000000000000000E46DF9B60100000000B467B8C8E0379E00DD379E7CE0379E24D6279D12A582B9BBA682B9C8E0379E01000000E87C679D0100000080827A9C00DD379E0000000000A782B902000000020000000100000000000000802A679D5C000000060000000000000038EC379E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37DD80 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B90000000000000000010000000200000080F8E69B80837A9C0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9D98DE379E14E2379EA8D6279D0000000000000000B8E2379E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37DF00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B6B8E0379E00B467B868E1379EC8E0379E108CA0B924E1379EE4DA279D
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E080 00000000000000000000000040B0729CC8E0379E01000000A8ED379EF6FFFFFF0CB467B80000000000B467B8B8E0379E0300000008000000603F779C88FFFFFF40B0729C88FFFFFFD0D9AB9B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B878E1379E68E1379E70E1379E64E1379E82FFFFFF088CA0B954E1379E38C5179D088CA0B970E1379E40B0729C88FFFFFFB4E1379EE8E1379EC8E2379E0100000080E1379E00000000B4E1379E205B399D70E1379E000000000000000040B0729C603F779C88FFFFFF0000000082FFFFFF01000000088CA0B90000000082FFFFFF00B467B8000000006C87529DE8E1379ED8E1379E983597B8303897B800B467B8C8E2379E6C87529D24E2379EB86A309DE8E1379E000000C0B08BA0B908F8DBB93CE2379E8D81F6B6BC8BA0B90000000040B0729C88FFFFFF00B467B800000000D0D9AB9B85FFFFFF00B467B80000000038E2379E18E0539D
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E200 DD8BA0B958E2379EC8E2379E48E2379E00B467B83CE2379E22000000983597B88CE2379EECDA319DE448529D504C529D584B689D22000000BC8BA0B9A48BA0B9000000005CE2379E2200000000000000E0E3379E0000000074E2379E14A5EF9C10E3379EE0E3379E1831699DD8E2379E0000000001000000C8E2379EB8E2379E2200000000B467B81CE4379E2804359D788BA0B90000000000B467B8A8E2379E02000000F0E2379E901CF69B10E3379E905DAD9B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B80100000040E4379E50E4379E01000000788BA0B907000000070000000100000070D8AB9B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF00000000888BA0B92200000078D8AB9B0700000000000000010000001800809CE8BDEBB881FFFFFF7CE3379EE01A229D0700000070D8AB9B00B467B8000000001000809C88E3379EBCE3379EE85C229D
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E380 0000000000000000000000000C440A9EF0E3379E01000000000000002022A09BE01B819C70D8AB9B00000000FFFFFFFFE8BDEBB881FFFFFF58E4379EB0440A9EB0E4379ECCE3379E18E4379E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF70D8AB9B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB881FFFFFF58E4379E385F619E000000002CE4379E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF70D8AB9B85FFFFFFB4E4379E58BEEBB888DC669E0105000070D8AB9B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFFE4E4379EFCE4379E00000000D8E4379E8C69619E820100008086769C010000000000000082FFFFFF70D8AB9B85FFFFFF84E5379EC0B88FB92C5C639E010A000070D8AB9B85FFFFFF0000000082FFFFFF8086769C88FFFFFF
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E500 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFFE8BB4A9C0200000000000000B0E5379E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF70D8AB9B85FFFFFF00F9E69B88FFFFFF24E6379E285273B9BCFC4A9C81060000F0D9819C85FFFFFF70D8AB9B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000008E6379E0000000083FFFFFF6800000060CA229A78D8AB9B010000003000000060CA229A0000000048E6379E8C69619E820100004077D69B010000000000000082FFFFFF70D8AB9B85FFFFFFCCE6379E58AAB2BAFCF44A9C8107000070D8AB9B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E680 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE8E6379EE0E6379ED8E6379E4CE7379E7800000060CA229A00000000A66A14B9584B689D00B467B800000000F0E6379E8C69619E820100008077D69B010000000000000082FFFFFF70D8AB9B85FFFFFF5CE7379EB8610BB9DCEA4A9C0106000070D8AB9B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000068E7379E80E7379E040000006000000060CA229A48073DBA81FFFFFFECE7379EF81F619E0000000080E7379E8C69619E82010000A077D69B010000000000000082FFFFFF70D8AB9B85FFFFFFECE7379E20BF0DB9E0E14A9C0106000070D8AB9B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B8C021A09B000000009808229B60000000F021A09B04000000E8BB4A9CFCE7379E7874049D0400000010E8379E8C69619E82010000C077D69B01000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E800 0000000082FFFFFFC021A09B88FFFFFF8CE8379ED0FF3CBAF4D84A9C01070000C021A09B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF70D8AB9B85FFFFFF80E8379E80E8379E7CE8379E88FFFFFF700000009021A09B8038A19B40E0729CC089729C0000000004000000B0E8379E8C69619E820100004078D69B0100000030A4079C88FFFFFFF05DAD9B88FFFFFF0CE9379E408E62BA60D24A9C01050000F05DAD9B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFF8038A19B010000003CE9379E54E9379E50000000509E5A9A02000000C8A95BB92CE9379EC873049D0000000040E9379EDCED2E9E8202000060980F9C030000000000000082FFFFFFF05DAD9B88FFFFFF0000000081FFFFFF8038A19B88FFFFFFDCE9379E301412BAE852019E010900008038A19B88FFFFFF0000000081FFFFFFF05DAD9B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37E980 0000000082FFFFFF0000000081FFFFFF30140D9B88FFFFFF0000000082FFFFFF0900000081FFFFFF8038A19B88FFFFFFD038A19B000000000CEA379EC0D6729C9000000020C0729CE8BB4A9C02000000002B66B981FFFFFF0000000000EA379E8C69619E82010000B002739C010000008038A19B88FFFFFF60980F9C88FFFFFF84EA379E002666B9D0CB4A9C8107000060980F9C88FFFFFF8038A19B88FFFFFFB002739C88FFFFFFD038A19B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFFD038A19B88FFFFFF0000000082FFFFFFA8EA379E385F619E000000006CEA379E78000000509E5A9A0000000024C24A9C420300000300000000000000B0EA379E8C69619E0202000080980F9C02000000007AD39988FFFFFF901CF69B88FFFFFF8038A19B88FFFFFF1CEB379EF04DACB9F0C64A9C010600008038A19B88FFFFFF901CF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFE0EA379EA035749CA0D9AB9B4011819C
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37EB00 60000000509E5A9A85FFFFFFDC06969C85FFFFFF1CEB379E000000000037749CE811969C800B0000C0980F9C020000000037749C88FFFFFF901CF69B88FFFFFF9032A19B88FFFFFFB0D9AB9B85FFFFFF3038A19B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF105FAD9B9032A19BA035749C8015A59B8A000000D020A09BB0D9AB9B3038A19B9032A19BA035749CA0D9AB9B8018809CE015A59B09000000A0F8E69BD0B0729CD0B0729C9032A19B88FFFFFF090000004011819C090000000037749C901CF69BC05DAD9BA0F8E69B88FFFFFF00000000643D2A9E083F2A9E000400008036749C010000000037749C88FFFFFF901CF69B88FFFFFF0000000082FFFFFFF09A719D901CF69B905DAD9B605DAD9B0000000087FFFFFFA00F739C305DAD9B605DAD9B80F8E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFF305DAD9B88FFFFFF98EC379E305DAD9BD05CAD9B005DAD9BFC700A9E800200000037749C00000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37EC80 D05CAD9B88FFFFFFD0B1A39B8A00000007000000E0B1A39B00B467B840B0729C7015A59B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFF7015A59B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B670EE379E0100000081FFFFFFC8ED379E34EE379E14340A9D603F779C000000000000000098ED379E4CED379E3897609E584B689D00B467B89835A6B8B4FE379E000000000000000000000000010000009CF5379E00B467B80001000000000000B06F0A9E00000000603F779C28F2379E020000000100000000000000000000000100000081FFFFFF000000000000000000F2379EF6FFFFFF0CB467B80100000000B467B8C8ED379E00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000070EE379E00B467B878AB719D80827A9C
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37EE00 00000000D086A0B934EE379E7CD86A160000000000B467B870EE379E38EE379E603F779C80827A9C00000000D086A0B95CEE379E2CD5279D000000000000000000000000E46DF9B60100000000B467B830F2379E68EE379EE4F1379E24D6279D12A582B9BBA682B930F2379E01000000E87C679D0100000080827A9C68EE379E0000000000A782B902000000020000000100000000000000802A679D5C0000000600000000000000A0FD379E0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37EF80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B900000000000000000100000002000000E0F7E69B80837A9C0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9D00F0379E7CF3379EA8D6279D000000000000000020F4379E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37F100 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B620F2379E00B467B8D0F2379E30F2379ED086A0B98CF2379EE4DA279D00000000000000000000000040B0729C30F2379E0100000010FF379EF6FFFFFF0CB467B80000000000B467B820F2379E0300000008000000603F779C88FFFFFF40B0729C88FFFFFF7015A59B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B8E0F2379ED0F2379ED8F2379ECCF2379E
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37F280 82FFFFFFC886A0B9BCF2379E38C5179DC886A0B9D8F2379E40B0729C88FFFFFF1CF3379E50F3379E30F4379E01000000E8F2379E000000001CF3379E205B399DD8F2379E000000000000000040B0729C603F779C88FFFFFF0000000082FFFFFF01000000C886A0B90000000082FFFFFF00B467B8000000006C87529D50F3379E40F3379E983597B8303897B800B467B830F4379E6C87529D8CF3379EB86A309D50F3379E000000C07086A0B908F8DBB9A4F3379E8D81F6B67C86A0B90000000040B0729C88FFFFFF00B467B8000000007015A59B85FFFFFF00B467B800000000A0F3379E18E0539D9D86A0B9C0F3379E30F4379EB0F3379E00B467B8A4F3379E22000000983597B8F4F3379EECDA319DE448529D504C529D584B689D220000007C86A0B96486A0B900000000C4F3379E220000000000000048F5379E00000000DCF3379E14A5EF9C78F4379E48F5379E1831699D40F4379E000000000100000030F4379E20F4379E2200000000B467B884F5379E2804359D3886A0B900000000
08-26 15:00:06.159  6989  6989 W google-breakpad: S 9E37F400 00B467B810F4379E0200000058F4379E401CF69B78F4379E2058AD9B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B801000000A8F5379EB8F5379E010000003886A0B90700000007000000010000001014A59B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF000000004886A0B9220000001814A59B0700000000000000010000001800809CE8BDEBB881FFFFFFE4F4379EE01A229D070000001014A59B00B467B8000000001000809CF0F4379E24F5379EE85C229D0000000000000000000000000C440A9E58F5379E0100000000000000A05CAD9BE01B819C1014A59B00000000FFFFFFFFE8BDEBB881FFFFFFC0F5379EB0440A9E18F6379E34F5379E80F5379E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF1014A59B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB881FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37F580 C0F5379E385F619E0000000094F5379E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF1014A59B85FFFFFF1CF6379E58BEEBB888DC669E010500001014A59B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFF4CF6379E64F6379E0000000040F6379E8C69619E820100008086769C010000000000000082FFFFFF1014A59B85FFFFFFECF6379EC0B88FB92C5C639E010A00001014A59B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFFE8BB4A9C020000000000000018F7379E8C69619E02020000C04C769C02000000
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37F700 A0C6759C88FFFFFF1014A59B85FFFFFF60F8E69B88FFFFFF8CF7379E285273B9BCFC4A9C81060000F0D9819C85FFFFFF1014A59B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000070F7379E0000000083FFFFFF6800000060CA229A1814A59B010000003000000060CA229A00000000B0F7379E8C69619E820100004077D69B010000000000000082FFFFFF1014A59B85FFFFFF34F8379E58AAB2BAFCF44A9C810700001014A59B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF50F8379E48F8379E40F8379EB4F8379E7800000060CA229A00000000A66A14B9584B689D00B467B80000000058F8379E8C69619E820100008077D69B010000000000000082FFFFFF1014A59B85FFFFFFC4F8379EB8610BB9DCEA4A9C010600001014A59B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37F880 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D0F8379EE8F8379E040000006000000060CA229A48073DBA81FFFFFF54F9379EF81F619E00000000E8F8379E8C69619E82010000A077D69B010000000000000082FFFFFF1014A59B85FFFFFF54F9379E20BF0DB9E0E14A9C010600001014A59B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B8405CAD9B000000009808229B60000000705CAD9B04000000E8BB4A9C64F9379E7874049D0400000078F9379E8C69619E82010000C077D69B010000000000000082FFFFFF405CAD9B88FFFFFFF4F9379ED0FF3CBAF4D84A9C01070000405CAD9B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF1014A59B85FFFFFFE8F9379EE8F9379EE4F9379E88FFFFFF70000000105CAD9BF031A19B40E0729CC089729C000000000400000018FA379E8C69619E82010000
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37FA00 4078D69B0100000030A4079C88FFFFFF8058AD9B88FFFFFF74FA379E408E62BA60D24A9C010500008058AD9B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFFF031A19B01000000A4FA379EBCFA379E50000000509E5A9A02000000C8A95BB994FA379EC873049D00000000A8FA379EDCED2E9E8202000060980F9C030000000000000082FFFFFF8058AD9B88FFFFFF0000000081FFFFFFF031A19B88FFFFFF44FB379E301412BAE852019E01090000F031A19B88FFFFFF0000000081FFFFFF8058AD9B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFC0130D9B88FFFFFF0000000082FFFFFF0900000081FFFFFFF031A19B88FFFFFF4032A19B0000000074FB379EC0D6729C9000000020C0729CE8BB4A9C02000000002B66B981FFFFFF0000000068FB379E8C69619E82010000B002739C01000000F031A19B88FFFFFF60980F9C88FFFFFFECFB379E002666B9D0CB4A9C8107000060980F9C88FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37FB80 F031A19B88FFFFFFB002739C88FFFFFF4032A19B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFF4032A19B88FFFFFF0000000082FFFFFF10FC379E385F619E00000000D4FB379E78000000509E5A9A0000000024C24A9C42030000030000000000000018FC379E8C69619E0202000080980F9C02000000007AD39988FFFFFF401CF69B88FFFFFFF031A19B88FFFFFF84FC379EF04DACB9F0C64A9C01060000F031A19B88FFFFFF401CF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFF48FC379EA035749C4015A59B4011819C60000000509E5A9A85FFFFFFDC06969C85FFFFFF84FC379E000000000037749CE811969C800B0000C0980F9C020000000037749C88FFFFFF401CF69B88FFFFFFF0EBA69B88FFFFFF5015A59B85FFFFFFA031A19B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFA059AD9BF0EBA69BA035749CD0B1A39B8A000000505BAD9B5015A59BA031A19BF0EBA69B
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37FD00 A035749C4015A59B8018809C30B2A39B0900000000F8E69BD0B0729CD0B0729CF0EBA69B88FFFFFF090000004011819C090000000037749C401CF69B5058AD9B00F8E69B88FFFFFF00000000643D2A9E083F2A9E000400008036749C010000000037749C88FFFFFF401CF69B88FFFFFF0000000082FFFFFFF09A719D401CF69B2058AD9BF057AD9B0000000087FFFFFFA00F739CC057AD9BF057AD9BE0F7E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFFC057AD9B88FFFFFF00FE379EC057AD9B6057AD9B9057AD9BFC700A9E800200000037749C000000006057AD9B88FFFFFFC04EAA9B8A00000007000000D04EAA9B00B467B840B0729CC0B1A39B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFFC0B1A39B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B6
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E37FE80 D8FF379E0100000081FFFFFF30FF379E9CFF379E14340A9D603F779C000000000000000000FF379EB4FE379E3897609E584B689D00B467B89835A6B81C10389E000000000000000000000000010000000407389E00B467B80001389E00000000B06F0A9E00000000603F779C9003389E020000000100000024FF379E000000000100000081FFFFFF0001389E000000056803389EF6FFFFFF0CB467B80100000000B467B830FF379E000000000800000054FF379E14142E9D0000800020000000D801389EF87B7A9C0000100000000000A4FF379E01000000D8FF379E00B467B878AB719D80827A9C000000009081A0B99CFF379E7CD86A160000000000B467B8D8FF379EA0FF379E603F779C80827A9C000000009081A0B9C4FF379E2CD5279D00000000B4782F9D02000000E46DF9B60100000000B467B89803389ED0FF379E4C03389E24D6279DDCFF379E0C792F9D9803389E01000000E87C679D0100000080827A9CD0FF379E00000000000B2E9D02000000380000004C6896BA2C0A2E9D
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380000 1100389E38000000D003389E1101389E3C000000000000E0E46DF9B6D801389E7000389EF87B7A9CF01BF69B000000001C6896BAF0272E9D606896BA4C00389E010000005C00389E5C00389EFFFFFF00010000006C00389E08000000646896BA386896BA4C084B9C58084B9C20F02D9D30084B9CF0FFFFFFFFFFFFFF00000000D801389EBC9769452400000060084B9CD801389EB400389E10000000B400389E8401389ED800389E8401389EB800389ED400389EE0760D9D40084B9C58084B9C8401389E8401389E707E739A0801389EFC00389E48780D9D806796BA000000C0B8177ABA886796BA2080A0B9000000C0B8177ABA2880A0B9F01BF69B8D81F6B6D801389E01000000B8177ABA00B467B8F01BF69B4DEFF4B6D002389E2C33FA9C0809389ED801389E3C01389E24DB089D00000000E46DF9B6C40C389E5CAD0D9D400A7ABABC30539D0D00000044CCA0B9030000000000000000000000001B0E9D400A7ABA6433539D1825969CD801389E01000000400A7ABA9001389EF87B7A9C
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380180 F01BF69B283B669D41B0729C0811969C10000000280000001C0000002C00000000000000B8177ABA0D00000044CCA0B903000000000000000D000000CCEA2D9D0200000001000000D801389E000000000000000000000000E801389E00000000000000000000000000000000000000000002389E00000000000000000000000000000000000000001802389E00000000000000000000000000000000000000003002389E0000000000000000000000004002389E0000000001000000000000005002389E00000000000000000000000008000000000000006802389E0000000008000000000000007802389E0000000008000000000000008802389E0000000008000000000000009802389E000000000000000000000000A802389E000000000000000005000000B802389E00000000000000000200000002000000000000002880A0B90100000001000000000000000000000000000000E802389E00000000000000000000000020000000000000000003389E000000002000000000000000
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380300 0103389E000000001803389E0500000001000000050000002803389E0200000001000000D00000003803389E7CD86A16E46DF9B68803389E00B467B83804389E9803389E9081A0B9F403389EE4DA279D6003389E000000000100000040B0729C9803389E010000007810389EF6FFFFFF0CB467B80000000000B467B88803389E0300000008000000603F779C88FFFFFF40B0729C88FFFFFFC0B1A39B85FFFFFF20000000000000000103389E00000000709A659D386896BA016C96BA000096BA709A659D386896BA016C96BA7CD86A161300000000B467B84804389E3804389E4004389E3404389E82FFFFFF8881A0B92404389E38C5179D8881A0B94004389E40B0729C88FFFFFF8404389EB804389E9805389E010000005004389E000000008404389E205B399D4004389E08000000D87496BA40B0729C603F779C88FFFFFF0000000082FFFFFF010000008881A0B90000000082FFFFFF00B467B8000000006C87529DB804389EA804389E983597B8303897B800B467B89805389E6C87529D
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380480 F404389EB86A309DB804389E000000C03081A0B908F8DBB90C05389E8D81F6B63C81A0B90000000040B0729C88FFFFFF00B467B800000000C0B1A39B85FFFFFF00B467B8000000000805389E18E0539D5D81A0B92805389E9805389E1805389E00B467B80C05389E22000000983597B85C05389EECDA319DE448529D504C529D584B689D220000003C81A0B92481A0B9000000002C05389E2200000000000000B006389E000000004405389E14A5EF9CE005389EB006389E1831699DA805389E00000000010000009805389E8805389E2200000000B467B8EC06389E2804359DF880A0B90000000000B467B87805389E02000000C005389EF01BF69BE005389EB052AD9B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B8010000001007389E2007389E01000000F880A0B907000000070000000100000060B0A39B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380600 000000000881A0B92200000068B0A39B0700000000000000010000001800809CE8BDEBB881FFFFFF4C06389EE01A229D0700000060B0A39B00B467B8000000001000809C5806389E8C06389EE85C229D0000000000000000000000000C440A9EC006389E01000000000000003057AD9BE01B819C60B0A39B00000000FFFFFFFFE8BDEBB881FFFFFF2807389EB0440A9E8007389E9C06389EE806389E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF60B0A39B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB881FFFFFF2807389E385F619E00000000FC06389E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF60B0A39B85FFFFFF8407389E58BEEBB888DC669E0105000060B0A39B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFFB407389ECC07389E
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380780 00000000A807389E8C69619E820100008086769C010000000000000082FFFFFF60B0A39B85FFFFFF5408389EC0B88FB92C5C639E010A000060B0A39B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFFE8BB4A9C02000000000000008008389E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF60B0A39B85FFFFFFC0F7E69B88FFFFFFF408389E285273B9BCFC4A9C81060000F0D9819C85FFFFFF60B0A39B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D808389E0000000083FFFFFF6800000060CA229A68B0A39B010000003000000060CA229A000000001809389E8C69619E82010000
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380900 4077D69B010000000000000082FFFFFF60B0A39B85FFFFFF9C09389E58AAB2BAFCF44A9C8107000060B0A39B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB809389EB009389EA809389E1C0A389E7800000060CA229A00000000A66A14B9584B689D00B467B800000000C009389E8C69619E820100008077D69B010000000000000082FFFFFF60B0A39B85FFFFFF2C0A389EB8610BB9DCEA4A9C0106000060B0A39B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000380A389E500A389E040000006000000060CA229A48073DBA81FFFFFFBC0A389EF81F619E00000000500A389E8C69619E82010000A077D69B010000000000000082FFFFFF60B0A39B85FFFFFFBC0A389E20BF0DB9E0E14A9C0106000060B0A39B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380A80 0000000082FFFFFF0000000082FFFFFF6836A6B8D056AD9B000000009808229B600000000057AD9B04000000E8BB4A9CCC0A389E7874049D04000000E00A389E8C69619E82010000C077D69B010000000000000082FFFFFFD056AD9B88FFFFFF5C0B389ED0FF3CBAF4D84A9C01070000D056AD9B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF60B0A39B85FFFFFF500B389E500B389E4C0B389E88FFFFFF70000000A056AD9B50EBA69B40E0729CC089729C0000000004000000800B389E8C69619E820100004078D69B0100000030A4079C88FFFFFF1053AD9B88FFFFFFDC0B389E408E62BA60D24A9C010500001053AD9B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFF50EBA69B010000000C0C389E240C389E50000000509E5A9A02000000C8A95BB9FC0B389EC873049D00000000100C389EDCED2E9E8202000060980F9C030000000000000082FFFFFF1053AD9B88FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380C00 0000000081FFFFFF50EBA69B88FFFFFFAC0C389E301412BAE852019E0109000050EBA69B88FFFFFF0000000081FFFFFF1053AD9B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF50130D9B88FFFFFF0000000082FFFFFF0900000081FFFFFF50EBA69B88FFFFFFA0EBA69B00000000DC0C389EC0D6729C9000000020C0729CE8BB4A9C02000000002B66B981FFFFFF00000000D00C389E8C69619E82010000B002739C0100000050EBA69B88FFFFFF60980F9C88FFFFFF540D389E002666B9D0CB4A9C8107000060980F9C88FFFFFF50EBA69B88FFFFFFB002739C88FFFFFFA0EBA69B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFFA0EBA69B88FFFFFF0000000082FFFFFF780D389E385F619E000000003C0D389E78000000509E5A9A0000000024C24A9C420300000300000000000000800D389E8C69619E0202000080980F9C02000000007AD39988FFFFFFF01BF69B88FFFFFF50EBA69B88FFFFFF
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380D80 EC0D389EF04DACB9F0C64A9C0106000050EBA69B88FFFFFFF01BF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFB00D389EA035749C90B1A39B4011819C60000000509E5A9A85FFFFFFDC06969C85FFFFFFEC0D389E000000000037749CE811969C800B0000C0980F9C020000000037749C88FFFFFFF01BF69B88FFFFFF60E5A69B88FFFFFFA0B1A39B85FFFFFF00EBA69B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF3054AD9B60E5A69BA035749CC04EAA9B8A000000E055AD9BA0B1A39B00EBA69B60E5A69BA035749C90B1A39B8018809C204FAA9B0900000060F7E69BD0B0729CD0B0729C60E5A69B88FFFFFF090000004011819C090000000037749CF01BF69BE052AD9B60F7E69B88FFFFFF00000000643D2A9E083F2A9E000400008036749C010000000037749C88FFFFFFF01BF69B88FFFFFF0000000082FFFFFFF09A719DF01BF69BB052AD9B8052AD9B0000000087FFFFFFA00F739C5052AD9B
08-26 15:00:06.169  6989  6989 W google-breakpad: S 9E380F00 8052AD9B40F7E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFF5052AD9B88FFFFFF9C10389E5052AD9BF051AD9B2052AD9BFC700A9E800200000037749C00000000F051AD9B88FFFFFF3019389E48000000740F389E4017389E4800000040B0729CB04EAA9B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFFB04EAA9B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B64011389E0100000081FFFFFF9810389E0411389E14340A9D603F779C00000000000000006810389E1C10389E3897609E584B689D00B467B89835A6B88421389E000000000000000000000000010000006C18389E00B467B80001A7BA00000000B06F0A9E00000000603F779CF814389E0200000001000000F85AB5BA000000000100000081FFFFFF001F109DF8D6A0B9D014389EF6FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381080 0CB467B80100000000B467B89810389E0000000008000000D830A7BAB830A7BA485BB5BA9A0100003851B5BAB830A7BA2831A7BA18040000F060C6B9010000004011389E00B467B878AB719D80827A9C00000000507CA0B90411389E7CD86A160000000000B467B84011389E0811389E603F779C80827A9C00000000507CA0B92C11389E2CD5279D00000000C0D7A0B900000000E46DF9B60100000000B467B80015389E3811389EB414389E24D6279D12A582B9BBA682B90015389E01000000E87C679D0100000080827A9C3811389E0000000000A782B902000000020000000100000000000000802A679D5C00000006000000000000007020389E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B900000000000000000100000002000000A0F6E69B80837A9C0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9DD012389E4C16389EA8D6279D0000000000000000F016389E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381380 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B6F014389E00B467B8A015389E0015389E507CA0B95C15389EE4DA279D00000000000000000000000040B0729C0015389E01000000E021389EF6FFFFFF0CB467B80000000000B467B8F014389E0300000008000000603F779C88FFFFFF40B0729C88FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381500 B04EAA9B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B8B015389EA015389EA815389E9C15389E82FFFFFF487CA0B98C15389E38C5179D487CA0B9A815389E40B0729C88FFFFFFEC15389E2016389E0017389E01000000B815389E00000000EC15389E205B399DA815389E000000000000000040B0729C603F779C88FFFFFF0000000082FFFFFF01000000487CA0B90000000082FFFFFF00B467B8000000006C87529D2016389E1016389E983597B8303897B800B467B80017389E6C87529D5C16389EB86A309D2016389E000000C0F07BA0B908F8DBB97416389E8D81F6B6FC7BA0B90000000040B0729C88FFFFFF00B467B800000000B04EAA9B85FFFFFF00B467B8000000007016389E18E0539D1D7CA0B99016389E0017389E8016389E00B467B87416389E22000000983597B8C416389EECDA319DE448529D504C529D584B689D22000000FC7BA0B9E47BA0B9000000009416389E
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381680 22000000000000001818389E00000000AC16389E14A5EF9C4817389E1818389E1831699D1017389E00000000010000000017389EF016389E2200000000B467B85418389E2804359DB87BA0B90000000050ED63B900000000000000002817389E4417389E4817389E6017389E000000000000000082FFFFFF0000000000010000220000000000000000000000000000000017389E00B467B8010000007818389E8818389E01D3819CB87BA0B9070000000700000001000000504DAA9B0000002000B467B8F410389EA040DBBA060000003C31699D3C31699D060000001831699D00000000FFFFFFFF00000000C87BA0B922000000584DAA9B0700000000000000010000001800809CE8BDEBB801000000B417389EE01A229D07000000504DAA9B00B467B8000000001000809CC017389EF417389EE85C229DD86423BA306523BA886523BA0C440A9E2818389E01000000E86623BAC051AD9BE01B819C504DAA9B00000000FFFFFFFFE8BDEBB8010000009018389EB0440A9EE818389E0418389E
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381800 5018389E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF504DAA9B85FFFFFF1000809C85FFFFFF286F23BA6049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB8010000009018389E385F619E000000006418389E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF504DAA9B85FFFFFFEC18389E58BEEBB888DC669E01050000504DAA9B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFF1C19389E3419389E000000001019389E8C69619E820100008086769C010000000000000082FFFFFF504DAA9B85FFFFFFBC19389EC0B88FB92C5C639E010A0000504DAA9B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381980 3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFF7050AD9B0302000000000000E819389E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF504DAA9B85FFFFFF20F7E69B88FFFFFF5C1A389E285273B9BCFC4A9C81060000F0D9819C85FFFFFF504DAA9B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000401A389E0000000083FFFFFF6800000060CA229A584DAA9B010000003000000060CA229A00000000801A389E8C69619E820100004077D69B010000000000000082FFFFFF504DAA9B85FFFFFF041B389E58AAB2BAFCF44A9C81070000504DAA9B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF201B389E181B389E101B389E841B389E7800000060CA229A00000000A66A14B9584B689D00B467B8
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381B00 00000000281B389E8C69619E820100008077D69B010000000000000082FFFFFF504DAA9B85FFFFFF941B389EB8610BB9DCEA4A9C01060000504DAA9B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A01B389EB81B389E040000006000000060CA229A48073DBA01000000241C389EF81F619E00000000B81B389E8C69619E82010000A077D69B010000000000000082FFFFFF504DAA9B85FFFFFF241C389E20BF0DB9E0E14A9C01060000504DAA9B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B86051AD9B000000009808229B600000009051AD9B040000007050AD9B341C389E7874049D04000000481C389E8C69619E82010000C077D69B010000000000000082FFFFFF6051AD9B88FFFFFFC41C389ED0FF3CBAF4D84A9C010700006051AD9B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381C80 0700000081FFFFFF8013819C85FFFFFF504DAA9B85FFFFFFB81C389EB81C389EB41C389E88FFFFFF700000003051AD9BC0E4A69B40E0729CC089729C0000000004000000E81C389E8C69619E820100004078D69B0100000030A4079C88FFFFFF907DA59B88FFFFFF441D389E408E62BA60D24A9C01050000907DA59B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFFC0E4A69B01000000741D389E8C1D389E50000000509E5A9A03020000C8A95BB9641D389EC873049D00000000781D389EDCED2E9E8202000060980F9C030000000000000082FFFFFF907DA59B88FFFFFF0000000081FFFFFFC0E4A69B88FFFFFF141E389E301412BAE852019E01090000C0E4A69B88FFFFFF0000000081FFFFFF907DA59B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFE0120D9B88FFFFFF0000000082FFFFFF0900000081FFFFFFC0E4A69B88FFFFFF10E5A69B00000000441E389EC0D6729C9000000020C0729C
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381E00 7050AD9B03020000002B66B90100000000000000381E389E8C69619E82010000B002739C01000000C0E4A69B88FFFFFF60980F9C88FFFFFFBC1E389E002666B9D0CB4A9C8107000060980F9C88FFFFFFC0E4A69B88FFFFFFB002739C88FFFFFF10E5A69B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFF10E5A69B88FFFFFF0000000082FFFFFFE01E389E385F619E00000000A41E389E78000000509E5A9A0000000024C24A9C420300000300000000000000E81E389E8C69619E0202000080980F9C02000000007AD39988FFFFFFA01BF69B88FFFFFFC0E4A69B88FFFFFF541F389EF04DACB9F0C64A9C01060000C0E4A69B88FFFFFFA01BF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFCC81619E9C1F389EA01F389E0000000060000000509E5A9A881F389E000000007050AD9B0302000000000000801F389E8C69619E02020000C0980F9C020000000037749C88FFFFFFA01BF69B88FFFFFFC02EAF9B88FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E381F80 1C20389E50D1D6BAFC14669E01090000C02EAF9B88FFFFFFA01BF69B88FFFFFF0037749C88FFFFFFC0980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFF904EAA9B85FFFFFF70E4A69B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFC0F6E69B88FFFFFF7050AD9B88FFFFFF603F779C0100000090000000607DA59B2420389E1420389E0895719D00000000040000006C22389E083F2A9E000400008036749C010000000037749C88FFFFFFA01BF69B88FFFFFF0000000082FFFFFFF09A719DA01BF69B307DA59B007DA59B0000000087FFFFFFA00F739CD07CA59B007DA59BA0F6E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFFD07CA59B88FFFFFFD020389ED07CA59B707CA59BA07CA59BFC700A9E800200000037749C00000000707CA59B88FFFFFFD09AA49B8A00000007000000E09AA49B00B467B840B0729C602CA19B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFF602CA19B85FFFFFF
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382100 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B6A822389E0100000081FFFFFF0022389E6C22389E14340A9D603F779C0000000000000000D021389E8421389E3897609E584B689D00B467B89835A6B8EC32389E00000000000000000000000001000000D429389E00B467B80001000000000000B06F0A9E00000000603F779C6026389E020000000100000000000000000000000100000081FFFFFF00000000000000003826389EF6FFFFFF0CB467B80100000000B467B80022389E000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000A822389E00B467B878AB719D80827A9C000000001060C6B96C22389E7CD86A160000000000B467B8A822389E7022389E603F779C80827A9C000000001060C6B99422389E2CD5279D000000000000000000000000E46DF9B6
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382280 0100000000B467B86826389EA022389E1C26389E24D6279D12A582B9BBA682B96826389E01000000E87C679D0100000080827A9CA022389E0000000000A782B902000000020000000100000000000000802A679D5C0000000600000000000000D831389E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B90000000000000000010000000200000000F6E69B80837A9C
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382400 0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9D3824389EB427389EA8D6279D00000000000000005828389E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382580 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B65826389E00B467B80827389E6826389E1060C6B9C426389EE4DA279D00000000000000000000000040B0729C6826389E010000004833389EF6FFFFFF0CB467B80000000000B467B85826389E0300000008000000603F779C88FFFFFF40B0729C88FFFFFF602CA19B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B81827389E0827389E1027389E0427389E82FFFFFF0860C6B9F426389E38C5179D0860C6B91027389E40B0729C88FFFFFF5427389E8827389E6828389E010000002027389E000000005427389E205B399D1027389E00000000
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382700 0000000040B0729C603F779C88FFFFFF0000000082FFFFFF010000000860C6B90000000082FFFFFF00B467B8000000006C87529D8827389E7827389E983597B8303897B800B467B86828389E6C87529DC427389EB86A309D8827389E000000C0B05FC6B908F8DBB9DC27389E8D81F6B6BC5FC6B90000000040B0729C88FFFFFF00B467B800000000602CA19B85FFFFFF00B467B800000000D827389E18E0539DDD5FC6B9F827389E6828389EE827389E00B467B8DC27389E22000000983597B82C28389EECDA319DE448529D504C529D584B689D22000000BC5FC6B9A45FC6B900000000FC27389E22000000000000008029389E000000001428389E14A5EF9CB028389E8029389E1831699D7828389E00000000010000006828389E5828389E2200000000B467B8BC29389E2804359D785FC6B90000000000B467B84828389E020000009028389E501BF69BB028389EC077A59B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B8
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382880 01000000E029389EF029389E01000000785FC6B9070000000700000001000000002BA19B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF00000000885FC6B922000000082BA19B0700000000000000010000001800809CE8BDEBB8010000001C29389EE01A229D07000000002BA19B00B467B8000000001000809C2829389E5C29389EE85C229D0000000000000000000000000C440A9E9029389E0100000000000000407CA59BE01B819C002BA19B00000000FFFFFFFFE8BDEBB801000000F829389EB0440A9E502A389E6C29389EB829389E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF002BA19B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB801000000F829389E385F619E00000000CC29389E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF002BA19B85FFFFFF542A389E58BEEBB8
08-26 15:00:06.179  6989  6989 W google-breakpad: S 9E382A00 88DC669E01050000002BA19B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFF842A389E9C2A389E00000000782A389E8C69619E820100008086769C010000000000000082FFFFFF002BA19B85FFFFFF242B389EC0B88FB92C5C639E010A0000002BA19B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFFF07AA59B0302000000000000502B389E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF002BA19B85FFFFFF80F6E69B88FFFFFFC42B389E285273B9BCFC4A9C81060000F0D9819C85FFFFFF002BA19B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E382B80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000A82B389E0000000083FFFFFF6800000060CA229A082BA19B010000003000000060CA229A00000000E82B389E8C69619E820100004077D69B010000000000000082FFFFFF002BA19B85FFFFFF6C2C389E58AAB2BAFCF44A9C81070000002BA19B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF882C389E802C389E782C389EEC2C389E7800000060CA229A00000000A66A14B9584B689D00B467B800000000902C389E8C69619E820100008077D69B010000000000000082FFFFFF002BA19B85FFFFFFFC2C389EB8610BB9DCEA4A9C01060000002BA19B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000082D389E202D389E040000006000000060CA229A48073DBA010000008C2D389EF81F619E00000000202D389E
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E382D00 8C69619E82010000A077D69B010000000000000082FFFFFF002BA19B85FFFFFF8C2D389E20BF0DB9E0E14A9C01060000002BA19B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B8E07BA59B000000009808229B60000000107CA59B04000000F07AA59B9C2D389E7874049D04000000B02D389E8C69619E82010000C077D69B010000000000000082FFFFFFE07BA59B88FFFFFF2C2E389ED0FF3CBAF4D84A9C01070000E07BA59B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF002BA19B85FFFFFF202E389E202E389E1C2E389E88FFFFFF70000000B07BA59B202EAF9B40E0729CC089729C0000000004000000502E389E8C69619E820100004078D69B0100000030A4079C88FFFFFF2078A59B88FFFFFFAC2E389E408E62BA60D24A9C010500002078A59B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFF
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E382E80 202EAF9B01000000DC2E389EF42E389E50000000509E5A9A03020000C8A95BB9CC2E389EC873049D00000000E02E389EDCED2E9E8202000060980F9C030000000000000082FFFFFF2078A59B88FFFFFF0000000081FFFFFF202EAF9B88FFFFFF7C2F389E301412BAE852019E01090000202EAF9B88FFFFFF0000000081FFFFFF2078A59B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF70120D9B88FFFFFF0000000082FFFFFF0900000081FFFFFF202EAF9B88FFFFFF702EAF9B00000000AC2F389EC0D6729C9000000020C0729CF07AA59B03020000002B66B90100000000000000A02F389E8C69619E82010000B002739C01000000202EAF9B88FFFFFF60980F9C88FFFFFF2430389E002666B9D0CB4A9C8107000060980F9C88FFFFFF202EAF9B88FFFFFFB002739C88FFFFFF702EAF9B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFF702EAF9B88FFFFFF0000000082FFFFFF4830389E385F619E
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383000 000000000C30389E78000000509E5A9A0000000024C24A9C4203000003000000000000005030389E8C69619E0202000080980F9C02000000007AD39988FFFFFF501BF69B88FFFFFF202EAF9B88FFFFFFBC30389EF04DACB9F0C64A9C01060000202EAF9B88FFFFFF501BF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFCC81619E0431389E0831389E0000000060000000509E5A9AF030389E00000000F07AA59B0302000000000000E830389E8C69619E02020000C0980F9C020000000037749C88FFFFFF501BF69B88FFFFFF3028AF9B88FFFFFF8431389E50D1D6BAFC14669E010900003028AF9B88FFFFFF501BF69B88FFFFFF0037749C88FFFFFFC0980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFF402CA19B85FFFFFFD02DAF9B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF20F6E69B88FFFFFFF07AA59B88FFFFFF603F779C0100000090000000F077A59B8C31389E7C31389E0895719D00000000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383180 04000000D433389E083F2A9E000400008036749C010000000037749C88FFFFFF501BF69B88FFFFFF0000000082FFFFFFF09A719D501BF69BC077A59B9077A59B0000000087FFFFFFA00F739C6077A59B9077A59B00F6E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFF6077A59B88FFFFFF3832389E6077A59B0077A59B3077A59BFC700A9E800200000037749C000000000077A59B88FFFFFFE009A59B8A00000007000000F009A59B00B467B840B0729CC09AA49B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFFC09AA49B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B61034389E0100000081FFFFFF6833389ED433389E14340A9D603F779C00000000000000003833389EEC32389E3897609E584B689D00B467B89835A6B85444389E0000000000000000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383300 00000000010000003C3B389E00B467B80001000000000000B06F0A9E00000000603F779CC837389E020000000100000000000000000000000100000081FFFFFF0000000000000000A037389EF6FFFFFF0CB467B80100000000B467B86833389E0000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000001034389E00B467B878AB719D80827A9C00000000600366B9D433389E7CD86A160000000000B467B81034389ED833389E603F779C80827A9C00000000600366B9FC33389E2CD5279D000000000000000000000000E46DF9B60100000000B467B8D037389E0834389E8437389E24D6279D12A582B9BBA682B9D037389E01000000E87C679D0100000080827A9C0834389E0000000000A782B902000000020000000100000000000000802A679D5C00000006000000000000004043389E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B90000000000000000010000000200000060F5E69B80837A9C0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9DA035389E1C39389EA8D6279D0000000000000000C039389E0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383600 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B6C037389E00B467B87038389ED037389E600366B9
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383780 2C38389EE4DA279D00000000000000000000000040B0729CD037389E01000000B044389EF6FFFFFF0CB467B80000000000B467B8C037389E0300000008000000603F779C88FFFFFF40B0729C88FFFFFFC09AA49B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B88038389E7038389E7838389E6C38389E82FFFFFF580366B95C38389E38C5179D580366B97838389E40B0729C88FFFFFFBC38389EF038389ED039389E010000008838389E00000000BC38389E205B399D7838389E000000000000000040B0729C603F779C88FFFFFF0000000082FFFFFF01000000580366B90000000082FFFFFF00B467B8000000006C87529DF038389EE038389E983597B8303897B800B467B8D039389E6C87529D2C39389EB86A309DF038389E000000C0000366B908F8DBB94439389E8D81F6B60C0366B90000000040B0729C88FFFFFF00B467B800000000C09AA49B85FFFFFF00B467B800000000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383900 4039389E18E0539D2D0366B96039389ED039389E5039389E00B467B84439389E22000000983597B89439389EECDA319DE448529D504C529D584B689D220000000C0366B9F40266B9000000006439389E2200000000000000E83A389E000000007C39389E14A5EF9C183A389EE83A389E1831699DE039389E0000000001000000D039389EC039389E2200000000B467B8243B389E2804359DC80266B90000000000B467B8B039389E02000000F839389E001BF69B183A389E5072A59B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B801000000483B389E583B389E01000000C80266B90700000007000000010000006099A49B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF00000000D80266B9220000006899A49B0700000000000000010000001800809CE8BDEBB801000000843A389EE01A229D070000006099A49B00B467B8000000001000809C903A389E
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383A80 C43A389EE85C229D0000000000000000000000000C440A9EF83A389E0100000000000000D076A59BE01B819C6099A49B00000000FFFFFFFFE8BDEBB801000000603B389EB0440A9EB83B389ED43A389E203B389E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF6099A49B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF58BEEBB801000000603B389E385F619E00000000343B389E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF6099A49B85FFFFFFBC3B389E58BEEBB888DC669E010500006099A49B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFFEC3B389E043C389E00000000E03B389E8C69619E820100008086769C010000000000000082FFFFFF6099A49B85FFFFFF8C3C389EC0B88FB92C5C639E010A00006099A49B85FFFFFF0000000082FFFFFF
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383C00 8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFF8075A59B0302000000000000B83C389E8C69619E02020000C04C769C02000000A0C6759C88FFFFFF6099A49B85FFFFFFE0F5E69B88FFFFFF2C3D389E285273B9BCFC4A9C81060000F0D9819C85FFFFFF6099A49B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000103D389E0000000083FFFFFF6800000060CA229A6899A49B010000003000000060CA229A00000000503D389E8C69619E820100004077D69B010000000000000082FFFFFF6099A49B85FFFFFFD43D389E58AAB2BAFCF44A9C810700006099A49B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383D80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF03D389EE83D389EE03D389E543E389E7800000060CA229A00000000A66A14B9584B689D00B467B800000000F83D389E8C69619E820100008077D69B010000000000000082FFFFFF6099A49B85FFFFFF643E389EB8610BB9DCEA4A9C010600006099A49B85FFFFFF0000000082FFFFFF8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000703E389E883E389E040000006000000060CA229A48073DBA01000000F43E389EF81F619E00000000883E389E8C69619E82010000A077D69B010000000000000082FFFFFF6099A49B85FFFFFFF43E389E20BF0DB9E0E14A9C010600006099A49B85FFFFFF0000000082FFFFFFA077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6836A6B87076A59B000000009808229B60000000A076A59B040000008075A59B043F389E7874049D04000000183F389E8C69619E82010000
,08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E383F00 C077D69B010000000000000082FFFFFF7076A59B88FFFFFF943F389ED0FF3CBAF4D84A9C010700007076A59B88FFFFFF0000000082FFFFFFC077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013819C85FFFFFF6099A49B85FFFFFF883F389E883F389E843F389E88FFFFFF700000004076A59B9027AF9B40E0729CC089729C0000000004000000B83F389E8C69619E820100004078D69B0100000030A4079C88FFFFFFB072A59B88FFFFFF1440389E408E62BA60D24A9C01050000B072A59B88FFFFFF30A4079C88FFFFFF4078D69B88FFFFFFC0D3819C85FFFFFF9027AF9B010000004440389E5C40389E50000000509E5A9A03020000C8A95BB93440389EC873049D000000004840389EDCED2E9E8202000060980F9C030000000000000082FFFFFFB072A59B88FFFFFF0000000081FFFFFF9027AF9B88FFFFFFE440389E301412BAE852019E010900009027AF9B88FFFFFF0000000081FFFFFFB072A59B88FFFFFF0000000082FFFFFF60980F9C88FFFFFF
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E384080 0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00120D9B88FFFFFF0000000082FFFFFF0900000081FFFFFF9027AF9B88FFFFFFE027AF9B000000001441389EC0D6729C9000000020C0729C8075A59B03020000002B66B901000000000000000841389E8C69619E82010000B002739C010000009027AF9B88FFFFFF60980F9C88FFFFFF8C41389E002666B9D0CB4A9C8107000060980F9C88FFFFFF9027AF9B88FFFFFFB002739C88FFFFFFE027AF9B88FFFFFFC0D6729C88FFFFFFC0D0729C88FFFFFF0000000082FFFFFFE027AF9B88FFFFFF0000000082FFFFFFB041389E385F619E000000007441389E78000000509E5A9A0000000024C24A9C420300000300000000000000B841389E8C69619E0202000080980F9C02000000007AD39988FFFFFF001BF69B88FFFFFF9027AF9B88FFFFFF2442389EF04DACB9F0C64A9C010600009027AF9B88FFFFFF001BF69B88FFFFFF007AD39988FFFFFF80980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFCC81619E6C42389E
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E384200 7042389E0000000060000000509E5A9A5842389E000000008075A59B03020000000000005042389E8C69619E02020000C0980F9C020000000037749C88FFFFFF001BF69B88FFFFFFA021AF9B88FFFFFFEC42389E50D1D6BAFC14669E01090000A021AF9B88FFFFFF001BF69B88FFFFFF0037749C88FFFFFFC0980F9C88FFFFFF0000000082FFFFFF0000000082FFFFFFA09AA49B85FFFFFF4027AF9B88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF80F5E69B88FFFFFF8075A59B88FFFFFF603F779C01000000900000008072A59BF442389EE442389E0895719D00000000040000003C45389E083F2A9E000400008036749C010000000037749C88FFFFFF001BF69B88FFFFFF0000000082FFFFFFF09A719D001BF69B5072A59B2072A59B0000000087FFFFFFA00F739CF071A59B2072A59B60F5E69BE04D0A9E80020000C036749C020000000000000082FFFFFFA00F739C88FFFFFFF071A59B88FFFFFFA043389EF071A59B9071A59BC071A59BFC700A9E80020000
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E384380 0037749C000000009071A59B88FFFFFFA059A49B8A00000007000000B059A49B00B467B840B0729CD009A59B0037749C2098609E03020000603F779C0100000040B0729C88FFFFFFD009A59B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B467B8E46DF9B67845389E0100000081FFFFFFD044389E3C45389E14340A9D603F779C0000000000000000A044389E5444389E3897609E584B689D00B467B89835A6B8BC55389E00000000000000000000000001000000A44C389E00B467B80001000000000000B06F0A9E00000000603F779C3049389E020000000100000000000000000000000100000081FFFFFF00000000000000000849389EF6FFFFFF0CB467B80100000000B467B8D044389E0000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000007845389E00B467B8
08-26 15:00:06.189  6989  6989 W google-breakpad: S 9E384500 78AB719D80827A9C0000000020FE65B93C45389E7CD86A160000000000B467B87845389E4045389E603F779C80827A9C0000000020FE65B96445389E2CD5279D000000000000000000000000E46DF9B60100000000B467B83849389E7045389EEC48389E24D6279D12A582B9BBA682B93849389E01000000E87C679D0100000080827A9C7045389E0000000000A782B902000000020000000100000000000000802A679D5C0000000600000000000000A854389E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384680 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C09C82B900000000000000000100000002000000C0F4E69B80837A9C0537C5B800000000000000007CD86A1600000000E46DF9B60000000000B467B8C82A1A9D0847389E844A389EA8D6279D0000000000000000284B389E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384800 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A16E46DF9B62849389E00B467B8D849389E3849389E20FE65B99449389EE4DA279D00000000000000000000000040B0729C3849389E010000001856389EF6FFFFFF0CB467B80000000000B467B82849389E0300000008000000603F779C88FFFFFF40B0729C88FFFFFFD009A59B85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007CD86A161300000000B467B8E849389ED849389E
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384980 E049389ED449389E82FFFFFF18FE65B9C449389E38C5179D18FE65B9E049389E40B0729C88FFFFFF244A389E584A389E384B389E01000000F049389E00000000244A389E205B399DE049389E000000000000000040B0729C603F779C88FFFFFF0000000082FFFFFF0100000018FE65B90000000082FFFFFF00B467B8000000006C87529D584A389E484A389E983597B8303897B800B467B8384B389E6C87529D944A389EB86A309D584A389E000000C0C0FD65B908F8DBB9AC4A389E8D81F6B6CCFD65B90000000040B0729C88FFFFFF00B467B800000000D009A59B85FFFFFF00B467B800000000A84A389E18E0539DEDFD65B9C84A389E384B389EB84A389E00B467B8AC4A389E22000000983597B8FC4A389EECDA319DE448529D504C529D584B689D22000000CCFD65B9B4FD65B900000000CC4A389E2200000000000000504C389E00000000E44A389E14A5EF9C804B389E504C389E1831699D484B389E0000000001000000384B389E284B389E2200000000B467B88C4C389E2804359D
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384B00 88FD65B90000000000B467B8184B389E02000000604B389EB01AF69B804B389ED04CA89B88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000B467B801000000B04C389EC04C389E0100000088FD65B90700000007000000010000007008A59B0000000000B467B80000000000000000060000003C31699D3C31699D060000001831699D00000000FFFFFFFF0000000098FD65B9220000007808A59B0700000000000000010000001800809CE8BDEBB801000000EC4B389EE01A229D070000007008A59B00B467B8000000001000809CF84B389E2C4C389EE85C229D0000000000000000000000000C440A9E604C389E01000000000000006071A59BE01B819C7008A59B00000000FFFFFFFFE8BDEBB801000000C84C389EB0440A9E204D389E3C4C389E884C389E000000000000000078440A9E4003000001000000FFFFFFFF81FFFFFF7008A59B85FFFFFF1000809C85FFFFFF000000006049769C88FFFFFF88DC669E00000000FFFFFFFF
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384C80 58BEEBB801000000C84C389E385F619E000000009C4C389E8C69619E000000000000000088DC669E42020000010000006049769C88FFFFFF00EA729C88FFFFFF7008A59B85FFFFFF244D389E58BEEBB888DC669E010500007008A59B85FFFFFF00EA729C88FFFFFF6049769C88FFFFFF0000000082FFFFFF0000000028C1959C40020000000000005000000030BD729CF0D9819C85FFFFFF544D389E6C4D389E00000000484D389E8C69619E820100008086769C010000000000000082FFFFFF7008A59B85FFFFFFF44D389EC0B88FB92C5C639E010A00007008A59B85FFFFFF0000000082FFFFFF8086769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007809C85FFFFFFF0D9819C85FFFFFF82FFFFFF5888719DF0FB819CECBA4A9CA000000030BD729C0000000083FFFFFF1070A59B0302000000000000204E389E8C69619E02020000
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384E00 C04C769C02000000A0C6759C88FFFFFF7008A59B85FFFFFF40F5E69B88FFFFFF944E389E285273B9BCFC4A9C81060000F0D9819C85FFFFFF7008A59B85FFFFFFA0C6759C88FFFFFFC04C769C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000784E389E0000000083FFFFFF6800000060CA229A7808A59B010000003000000060CA229A00000000B84E389E8C69619E820100004077D69B010000000000000082FFFFFF7008A59B85FFFFFF3C4F389E58AAB2BAFCF44A9C810700007008A59B85FFFFFF0000000082FFFFFF4077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF584F389E504F389E484F389EBC4F389E7800000060CA229A00000000A66A14B9584B689D00B467B800000000604F389E8C69619E820100008077D69B010000000000000082FFFFFF7008A59B85FFFFFFCC4F389EB8610BB9DCEA4A9C010600007008A59B85FFFFFF0000000082FFFFFF
08-26 15:00:06.199  6989  6989 W google-breakpad: S 9E384F80 8077D69B88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D84F389EF04F389E040000006000000060CA229A48073DBA010000005C50389EF81F619E00000000F04F389E8C69619E82010000A077D69B010000000000000082FFFFFF7008A59B85FFFFFF5C50389E20BF0DB9E0E14A9C01060000
08-26 15:00:06.199  6989  6989 W google-breakpad: C 0600004030AEA0B80000000074D0379EF0D0379E48D0379E9CD0379E00B467B874D0379E102FA39B85FFFFFF983597B86CD0379E30D0379E38D0379E7899179D7C99179D10000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:06.199  6989  6989 W google-breakpad: M B6FB8000 00000000 00003000 C076D4C24C77979D0F88BE887CB5F0160 app_process32
08-26 15:00:06.199  6989  6989 W google-breakpad: M 9CC32000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A080A000 00000000 00003000 C92C8D5B6B698181A7DD1FB7E563E88A0 libqdMetaData.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A080D000 00000000 0000A000 22DE2F7A850976271F596FD7120471AC0 libqservice.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A0818000 00000000 00009000 EC3B3774E5CB032EE6BC192244EC0E1A0 libqdutils.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A0822000 00000000 00006000 91673970C17AB2DD7AB97FE633A7CC7F0 libmemalloc.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A0C2E000 00000000 00007000 FA30956B63451E4E9F4B6C7001FBD0F90 gralloc.msm8916.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A25EE000 00000000 0046A000 F1E6740F7B2AC1EADD232024D3726E350 libsc-a3xx.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M A4E3C000 00000000 01AEE000 6DC83C69BA92FC15D9BFC15CAA444FA30 libwebviewchromium.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M AEE90000 00000000 00009000 15E68926F10C52B9E1C918455B33395D0 librs_jni.so
08-26 15:00:06.199  6989  6989 W google-breakpad: M AEE9A000 00000000 0001B000 409A264B865DAA353D92FE1A41BA42010 libjavacrypto.so
08-26 15:00:06.199  5984  5984 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEEB5000 00000000 00006000 DCD8843E6E58F548A2F9F918E0F2250C0 libaudioeffect_jni.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEEBB000 00000000 00004000 430912DAAB9CCB0652C6C67ED71BD34A0 libsoundpool.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF40000 00000000 0000E000 65B4EE8C28DFCF943EF3BAB5CE2CF57E0 libstagefright_amrnb_common.so
08-26 15:00:06.209  5984  5984 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 15:00:06.209  5984  5984 D PhoneWindow: *FMB* installDecor flags : 8388610
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF4E000 00000000 0001A000 F596654166444B073C7B57DA85DDA86F0 libvorbisidec.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF68000 00000000 00004000 840EEE8827F765C9EEB69A82A5385D860 libstagefright_yuv.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF6C000 00000000 00020000 6A5DDC8F80D9496F56416E0CDC30C7860 libstagefright_omx.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF8C000 00000000 00003000 03B0255D304C04BA1CB893EF055C0D880 libstagefright_enc_common.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF8F000 00000000 00007000 BE9998F628EA6A5C32345D001998B9DE0 libstagefright_avc_common.so
08-26 15:00:06.209  6989  6989 W google-breakpad: M AEF96000 00000000 0000B000 E431EED302BEFED523DB8D7341DEEFBD0 libsfextcp.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AEFA1000 00000000 0000A000 BBE7244283F7E662D7E34D745C8451F80 libsecuibc.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AEFAB000 00000000 0005F000 098C11FE4C1E5783837B86006532FAB50 libsavsff.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AF00F000 00000000 0004E000 DF97B63F6B72A8BB76A1D8FBA29896010 libsavscmn.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AF05D000 00000000 00005000 89B5E9B7BF6412D458C721055A152C4A0 libpowermanager.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AF062000 00000000 00039000 34D438FC59A243B4B79B29B3300A98C30 libopus.so
08-26 15:00:06.219  6989  6989 W google-breakpad: M AF09B000 00000000 0001C000 1DA76B6D81AB593736F5F89F03BB089E0 libdrmframework.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF0B7000 00000000 003B4000 BD3C4CE5F3F0FA413707AB0A9757E0830 libMMFW_scone_stub.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF476000 00000000 00164000 4320EC321DE6EADC7528366646D5CA740 libstagefright.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF5DA000 00000000 00014000 C2FFC5B6A88CE765BBB0762DF08836520 libmtp.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF5EE000 00000000 0000B000 F8D7FA4760673A60E9A957A1FF0991BD0 libjhead.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF5FA000 00000000 0002C000 7FE1E6C0CA754D8F79E50A1CB5A2F4AF0 libexif.so
08-26 15:00:06.229  6989  6989 W google-breakpad: M AF626000 00000000 0003C000 07D5EEA8D30C78E1DBD86B63E0447FA50 libmedia_jni.so
,08-26 15:00:06.229  6989  6989 W google-breakpad: M AF68A000 00000000 00003000 07E50F790CF258618C54CBF3C74A6A1E0 libwebviewchromium_loader.so
,08-26 15:00:06.229  6989  6989 W google-breakpad: M AF68D000 00000000 00003000 1042592D6A7B2C021C7008CB35D370AA0 libjnigraphics.so
,08-26 15:00:06.229  6989  6989 W google-breakpad: M AF690000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M AF698000 00000000 00141000 A2F46E5CA0880CEF1C04E302488BB4E60 libGLESv2_adreno.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M AF7DA000 00000000 00034000 684DED99CC59C3906C82B7457EDB45F00 libGLESv1_CM_adreno.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M AF80E000 00000000 00035000 D4318DD5004755DA26AE6B0BBAF281DE0 libgsl.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M AF843000 00000000 0002A000 020C64D887DAD39ADBA1263F72513FED0 libEGL_adreno.so,
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B0A5E000 00000000 00010000 C7EB647818605F38532F9A290DDB69010 libandroid.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B0A75000 00000000 00004000 7969E81D0F5763BFDBC09C2B6D2F08250 libadreno_utils.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B0C8C000 00000000 00003000 B4D861A3F3ACFD7D321C59CB7177B7ED0 libqti-perfd-client.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B0C8F000 00000000 00003000 900F180B6ED1813B019148541FEBC4850 memtrack.msm8916.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B0CA7000 00000000 0000B000 77FE3A801397BE328D22A2C6CEDD5D190 eglsubAndroid.so,
08-26 15:00:06.239  6989  6989 W google-breakpad: M B23B5000 00000000 00038000 032BBF3A646CEC0E92F02F2607486BCA0 libjavacore.so,
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B48F3000 00000000 00004000 D8D9004A312C20C7AEAEE0BE3D460C970 libwebviewchromium_plat_support.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B4E82000 00000000 00008000 BABBF80B8FC90D8583D80A696A57B2130 libbacktrace_libc++.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B4E8A000 00000000 002FE000 E28D8FF4E9F5563C0B0777FF0B95B6720 libart.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B51AA000 00000000 00004000 62EFD3D29964E6B599D4FAE01272421C0 libusbhost.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B51AE000 00000000 0003F000 8F93763230E70AC1012CE2797EBDCD180 libssl.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B51ED000 00000000 0000E000 5531DBDE929DBC5D9C2D2973F0ACB63E0 libsoundtrigger.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B51FB000 00000000 00012000 F53050926856F9ED174D0B9FB54900510 libpcre.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B520D000 00000000 00012000 094A62A7F00C732AD95FB394CA44D7300 libselinux.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B521F000 00000000 00004000 099B10F2EAA0144B6769F0BF764BE16D0 libprocessgroup.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B5223000 00000000 00447000 F96B93C6164BBEFDAF535E909BE475720 libpdfium.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B566F000 00000000 00004000 2C94DBD2926E0C0A51C840F6C94B0A120 libnetd_client.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B5673000 00000000 00007000 8870FC1A3B0A0C618D77747DF2C5239F0 libnativehelper.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B567A000 00000000 00004000 BF30FE88A9C8EE464CC8F0BB519494960 libnativebridge.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B567E000 00000000 0000B000 0984D19CFFD7280D6559EA579517C0560 libminikin.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B5689000 00000000 00003000 E8D81805B27BF1C2BADC1C385C9D44110 libmemtrack.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B568C000 00000000 00014000 AB30B4F28663E54089CB0393F16EC42A0 libstagefright_foundation.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B56A0000 00000000 00009000 DF257BF35EC3333D10EF36A5C95A55CE0 libsec_km.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B56AA000 00000000 00007000 09E0E8E3AC05172EE6B3DC26270D49F70 libsdp_crypto.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B56B1000 00000000 00004000 678D29883C80386905E16BBCE7CF2E570 libpersona.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B56B6000 00000000 00085000 176AE350351B5C616895DE24B70FE7570 libsqlite.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B573D000 00000000 00050000 2FF9202116C3611BE6EFBD00407235750 libomafldrm.so
08-26 15:00:06.239  6989  6989 W google-breakpad: M B578E000 00000000 00050000 F8171C0B0A8FBD6C5438EA18037AAFE80 libsonivox.so
,08-26 15:00:06.239  6989  6989 W google-breakpad: M B57E3000 00000000 00005000 B928740DB1DCEFFD56EE67AE84B8EFC10 libsecnativefeature.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B57E8000 00000000 00008000 C04C622FA1AEFB29F88FEED961B34D680 lib_SamsungVAD_v01007.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B57F2000 00000000 00003000 E8AD41C2097B7B0A26463F3E900952FE0 libsamsungvad.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B57F5000 00000000 0000F000 0F206C184F10DAF8B580B1CA47FA6EC80 libcommon_time_client.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5804000 00000000 0000A000 ADDFBB302FF2440C1B86D12D70317C8F0 libnbaio.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B580E000 00000000 000BD000 BE2C9C97A647438CAB5EE6F3F9C6EB610 libmedia.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B58CC000 00000000 00040000 E7102D00C0372AA9E97071DD4BF6FDCC0 libinputflinger.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B590C000 00000000 0001B000 BB5BED8E5ADF4A119D5B2DA31DBAEC580 libinput.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5927000 00000000 0000D000 C17942DF5B7EBECE9049E849149CA1120 libimg_utils.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5934000 00000000 0001E000 18C32F00634AB7BB4010F2D59861567F0 libquramimagecodec.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5952000 00000000 00032000 8F255D73F53B095B1764C82186FE28FC0 libjpeg.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B5984000 00000000 00264000 4DCD73A518FC633987387494509BE53D0 libskia.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5BEE000 00000000 00011000 5F14FC290F6EBD6AFCC7BDA3F439C3E90 libsamsungeffect.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5BFF000 00000000 0001D000 90BC6412D2B13FFD96428D1B517BEDD00 libRScpp.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5C1D000 00000000 00027000 CA02F8123591B96EE9266BAA11675EEA0 libpng.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B5C45000 00000000 00059000 54828C4F4B56D81127BD1BAF9A48D64E0 libft2.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5C9E000 00000000 0003C000 A0A13C2D329CE4F443247914FBF76EA40 libbcinfo.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5CDA000 00000000 00022000 E421E96697C14EB985E7F06B412DFB2B0 libbcc.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5D1C000 00000000 0008C000 D2E4B8E2C12DFE9B2752E15EF016991E0 libc++.so,
08-26 15:00:06.249  6989  6989 W google-breakpad: M B5DA9000 00000000 008FE000 1E521DDD13333E86CCC3043C7BB1C7EF0 libLLVM.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B66AE000 00000000 00036000 2F058C02160C453D2C194C7A4498C7510 libRS.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B66E4000 00000000 00051000 7A9A46F8FEF9C704ACEEEFE03C2F36DE0 libhwui.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B6735000 00000000 000FF000 24D205C2C90637FA33CF50299F7199690 libicuuc.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6838000 00000000 00006000 6AC3328D55BE7167DD1549E59E88D8420 libgabi++.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B683E000 00000000 0014A000 30D014A51C507F017588CD57CC7ABDAD0 libicui18n.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6988000 00000000 00048000 58C7C20B9121CD68E9A3B78D8C6CF7190 libharfbuzz_ng.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B69D0000 00000000 00005000 1AB401385CC88F656E0CB80273DA89860 libwpa_client.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B69D5000 00000000 00007000 ACC103A77586F28DE7F6DA309DF82D320 libnetutils.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B69DC000 00000000 00007000 67762CE3DAA2297C6E0F58843AAAB3910 libhardware_legacy.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B69E4000 00000000 00017000 D1B3203E3493EE80553E5CF9C9905E320 libexpat.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B69FB000 00000000 00142000 2727DE264BD767080C4068EDB1F581960 libcrypto.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B3F000 00000000 00003000 6E72A700CCC315909A66D3E4D2AAAE410 libcc_manager.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B42000 00000000 00003000 7C24A254F6B1768D1FF8ADFB9A8A11500 libsync.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B45000 00000000 00003000 0C360DD265129CA1197EE36C44A162570 libhardware.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B49000 00000000 0000C000 AB61E5F34C506C41C8ACF65F1DF7A7690 libui.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B55000 00000000 0000B000 3EBFA8F358F7A386E377C708170C6A0B0 libremotedesktop_client.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6B60000 00000000 0004C000 D41F8C8CDABD00A9D5F6E03D9131C6FE0 libgui.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6BAC000 00000000 00008000 D86968593275725A009907DF162762E60 libcamera_metadata.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6BB4000 00000000 00041000 8F4B2C50A29960551F2159E0DAB20E260 libcamera_client.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6BF5000 00000000 00006000 20E951BEE083EAAC8A0EC8C9659BC90C0 libspeexresampler.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6BFB000 00000000 00006000 556F9F9B6E57A78532BC16CE0DAFDB920 libaudioutils.so,
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C01000 00000000 00019000 6FF245A929534129A0A09E804082C1F90 libz.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C1A000 00000000 0002D000 10C485FADAF2C720FDA5625DC38ABF2A0 libbinder.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C47000 00000000 00026000 65C138E33F598CC3AF5D7A6804A6293D0 libandroidfw.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C6D000 00000000 0000D000 FE94ED4BD906E283008A8207B21F731F0 libGLESv2.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C7A000 00000000 00008000 E20B832545D307124FB21DEB3AFA1EFA0 libGLESv1_CM.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C82000 00000000 00004000 C10A3FF24BC314BDB4276E3588B5CFEF0 libETC1.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C86000 00000000 00004000 9A82E5E5DC0FF6464E020C95D6C265430 libunwind-ptrace.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6C8A000 00000000 0000E000 FCC4CF7B44EE2AEE89CCE84DDB0A34E30 libunwind.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6CDE000 00000000 00007000 9AD603917CEBD0A26C5300A4455555250 libgccdemangle.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6CE7000 00000000 00008000 809C179831A89482ABAEF5D7DAE451C00 libbacktrace.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B6CF0000 00000000 00016000 F1EB1C81CF043EF6ACD6D977257B90FA0 libutils.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6D06000 00000000 00036000 A86B4524AFE0B8B31C00A4A9DA14FB720 libstlport.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6D3C000 00000000 0000D000 C5A05BA0312495F273F4D3DF9ECCA8830 libcutils.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6D4A000 00000000 0006B000 0003812AEBDD6FD4750BAB0D29164BB90 libGLES_trace.so
,08-26 15:00:06.249  6989  6989 W google-breakpad: M B6DB5000 00000000 0006A000 7F16035A8648874F086D60A0C922D76C0 libEGL.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6E22000 00000000 000F5000 C5F797DCDC70EF17BB357C3E2C8A5E4C0 libandroid_runtime.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6F1C000 00000000 00004000 D44FDF94BA8D734E5BC46C426F7316DE0 libstdc++.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6F20000 00000000 00018000 3D2BCD0A8F5E726801091CC87EA86DCC0 libm.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6F39000 00000000 00006000 D777457560B88DEC8383D062CA85BD860 liblog.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6F40000 00000000 00056000 D779447DA8EFA50115E42F43400903DD0 libc.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6FA0000 00000000 00003000 6942576880529816BD6C80C55563D51C0 libsigchain.so
08-26 15:00:06.249  6989  6989 W google-breakpad: M B6FA8000 00000000 0000F000 1A12EEA227DCC44493A0CB9F6FAD897C0 linker
,08-26 15:00:06.249  6989  6989 W google-breakpad: -----END BREAKPAD MICRODUMP-----
08-26 15:00:06.259  1018  1497 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 15:00:06.259  1018  1497 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@26b1b4e attribute=null, token = android.os.BinderProxy@331f48b5
,08-26 15:00:06.259  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 15:00:06.259  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-26 15:00:06.259  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 15:00:06.259  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 15:00:06.259  1018  1424 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 15:00:06.259  1018  1424 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:00:06.259  1018  1424 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 15:00:06.259  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:00:06.259  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:00:06.259  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 15:00:06.259  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 15:00:06.269  1018  1506 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:00:06.289  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b5e6eb1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@130a1b5e, 16908290=android.view.AbsSavedState$1@130a1b5e}, android:focusedViewId=100}]}]
,08-26 15:00:06.289  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 15:00:06.289  6701  6701 V ActivityThread: updateVisibility : ActivityRecord{12c3c88 token=android.os.BinderProxy@20c424a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 15:00:06.299  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
08-26 15:00:06.299  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 15:00:06.299  6701  6701 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20c424a5 time:117192
08-26 15:00:06.299  6701  6783 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:06.299  6701  6783 W google-breakpad: Chrome build fingerprint:
08-26 15:00:06.299  6701  6783 W google-breakpad: 0.0.1
08-26 15:00:06.299  6701  6783 W google-breakpad: 19
08-26 15:00:06.299  6701  6783 W google-breakpad: 3287cb47-323f-452a-9071-08e954855982
08-26 15:00:06.299  6701  6783 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
,08-26 15:00:06.299  6701  6783 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 6783 (Thread-1246)
,08-26 15:00:06.409   283   283 I DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:00:06.409   283   283 I DEBUG   : Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
08-26 15:00:06.409   283   283 I DEBUG   : Revision: '1'
08-26 15:00:06.409   283   283 I DEBUG   : ABI: 'arm'
08-26 15:00:06.409   283   283 I DEBUG   : pid: 6701, tid: 6783, name: Thread-1246  >>> com.test.thalitest <<<
,08-26 15:00:06.409   283   283 I DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-26 15:00:06.429   283   283 I DEBUG   :     r0 b8a0ae30  r1 00000000  r2 9e37d074  r3 9e37d0f0,
,08-26 15:00:06.429   283   283 I DEBUG   :     r4 9e37d048  r5 9e37d09c  r6 b867b400  r7 9e37d074
,08-26 15:00:06.429   283   283 I DEBUG   :     r8 9ba32f10  r9 ffffff85  sl b8973598  fp 9e37d06c
,08-26 15:00:06.429   283   283 I DEBUG   :     ip 9e37d030  sp 9e37d038  lr 9d179978  pc 9d17997c  cpsr 200f0010
,08-26 15:00:06.429   283   283 I DEBUG   : ,
08-26 15:00:06.429   283   283 I DEBUG   : backtrace:
,08-26 15:00:06.429   283   283 I DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 15:00:06.429   283   283 I DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
,08-26 15:00:06.429   283   283 I DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,08-26 15:00:06.539  1018  2884 D SSRM:n  : SIOP:: AP = 390
,08-26 15:00:06.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:07.239   283   283 I DEBUG   : 
08-26 15:00:07.239   283   283 I DEBUG   : Tombstone written to: /data/tombstones/tombstone_02
,08-26 15:00:07.239   283   283 E         : ro.product_ship = true
08-26 15:00:07.239   283   283 E         : ro.debug_level = 0x4f4c
08-26 15:00:07.249  1975  1975 E audit   : type=1701 msg=audit(1472216407.239:206): auid=4294967295 uid=10170 gid=10170 ses=4294967295 subj=u:r:untrusted_app:s0 pid=6783 comm="Thread-1246" reason="memory violation" sig=11
,08-26 15:00:07.249  1018  1044 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,08-26 15:00:07.259  1018  2868 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,08-26 15:00:07.269  1018  6993 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-26 15:00:07.269  1018  6993 D FocusedStackFrame: Set to : 0
08-26 15:00:07.269  1018  6993 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:00:07.269  1018  6993 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,08-26 15:00:07.269  1018  6993 D InputDispatcher: Focused application set to: xxxx
,08-26 15:00:07.269  1018  6993 D InputDispatcher: Focus left window: 6701
08-26 15:00:07.269  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:00:07.269  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:00:07.269   255   255 E lowmemorykiller: Error writing /proc/6701/oom_score_adj; errno=22
08-26 15:00:07.279  1018  6993 I ActivityManager: Killing 6638:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-26 15:00:07.289  6278  6278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.sm.common.SmartManagerReceiver.b:199 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:93 
,08-26 15:00:07.289  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.sm, calleePkgName: com.samsung.android.sm
08-26 15:00:07.289  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sm/com.samsung.android.sm.common.notification.CrashedAppLoggingService; callingUser = 0; userId(target) = 0
08-26 15:00:07.289  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.289  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.289  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sm, destAppInfo.processName = com.samsung.android.sm
,08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Hardware: MSM8916
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Revision: 1
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Bootloader: A300FUXXS1BPE1
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Radio: unknown
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Kernel: Linux version 3.10.49-6027881 (dpi@SWDD6014) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 6 21:20:10 KST 2016
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: 
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: Revision: '1'
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: ABI: 'arm'
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: pid: 6701, tid: 6783, name: Thread-1246  >>> com.test.thalitest <<<
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     r0 b8a0ae30  r1 00000000  r2 9e37d074  r3 9e37d0f0
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     r4 9e37d048  r5 9e37d09c  r6 b867b400  r7 9e37d074
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     r8 9ba32f10  r9 ffffff85  sl b8973598  fp 9e37d06c
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     ip 9e37d030  sp 9e37d038  lr 9d179978  pc 9d17997c  cpsr 200f0010
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d0  9d528c4c9c812200  d1  ba72bb709e370000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d2  b867b400b6f96d00  d3  9d29ff509e37c400
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d4  9e37c39c9c72a640  d5  9e37c3ac9e37c3ac
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d6  9e37c3ac9e37c740  d7  9d0e49849e37c3f4
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d16 0000000000000000  d17 746e65746e6f4365
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d20 0000000000000001  d21 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d26 0002000200020001  d27 0002000200020002
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     scr 20000013
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: 
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: backtrace:
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
08-26 15:00:07.299 , 1018  1018 D CrashAnrDetector: 
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: stack:
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfb8  b9a09140  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfbc  c0000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfc0  00000001  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfc4  b9a09148  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfc8  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfcc  00000969  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfd0  b8a05668  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfd4  96917010  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfd8  9e37d014  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfdc  9cf8b410  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZNK2js6detail9HashTableIKNS_14AtomStateEntryENS_7HashSetIS2_NS_10AtomHasherENS_17SystemAllocPolicyEE6SetOpsES6_E6lookupERKNS5_6LookupEjj+252)
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfe0  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfe4  9e37d080  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfe8  9e37d04c  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cfec  9e37d030  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cff0  9e37d008  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cff4  00000007  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cff8  9d684b58  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37cffc  9d528774  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d000  b867b400  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d004  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d008  ffffff85  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d00c  b8a0ee30  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d010  9e37d06c  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d014  9cf8b920  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN2js7AtomizeEPNS_16ExclusiveContextEPKcjNS_14InternBehaviorE+460)
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d018  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d01c  9e37d030  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d020  b867b400  [heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d024  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d028  9d52876c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d02c  9e37d080  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d030  9d528774  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d034  9e37d06c  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:     #00  9e37d038  00000007  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d03c  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d040  00000000  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d044  e6e0b890  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d048  9ba32f10  [anon:js-gc-heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d04c  ffffff85  
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d050  9c811de0  [anon:js-gc-heap]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d054  b867b400  [heap]
08-26 15:00:07.299  ,1018  1018 D CrashAnrDetector:          9e37d058  9e37d0f0  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37d05c  9e37d09c  [stack:6783]
08-26 15:00:07.299  1018  1018 D CrashAnrDetector:          9e37
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: processName:com.test.thalitest
08-26 15:00:07.299  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
08-26 15:00:07.299  1018  1018 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
,08-26 15:00:07.319  1018  1099 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
08-26 15:00:07.319  1018  1099 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,08-26 15:00:07.319  1018  1521 W InputDispatcher: Attempted to unregister already unregistered input channel,
08-26 15:00:07.319  1018  1521 I WindowState: WIN DEATH: Window{3d774b4a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:00:07.319   258   446 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
08-26 15:00:07.319   258  1098 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-26 15:00:07.319  1018  3340 I ActivityManager: Process com.test.thalitest (pid 6701)(adj 9) has died(136,733)
,08-26 15:00:07.329   258  1976 I SurfaceFlinger: id=13 Removed NainActivit (-2/8),
,08-26 15:00:07.339  1018  3340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.am.SmartAdjustManager.SPCMLocked:1235 com.android.server.am.ActivityManagerService.updateOomAdjLocked:22618 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:2721 com.android.server.am.ActivityStack.resumeTopActivityLocked:2240 
,08-26 15:00:07.349  1018  3340 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 15:00:07.349   322   322 I Zygote  : Process 6701 exited due to signal (11)
,08-26 15:00:07.369  1508  1508 D Launcher: onRestart, Launcher: 673396263
,08-26 15:00:07.369  1508  1508 D Launcher: onStart, Launcher: 673396263
,08-26 15:00:07.369  1508  1508 D Launcher.HomeView: onStart
,08-26 15:00:07.369  1508  1508 D Launcher: onResume, Launcher: 673396263
,08-26 15:00:07.369  1018  1030 D SettingsProvider: name = kids_home_mode
,08-26 15:00:07.369  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:00:07.369  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:00:07.369  1018  1030 D SettingsProvider: selectionArgs: false
08-26 15:00:07.369  1018  1030 D SettingsProvider: selectionArgs: 10006
,08-26 15:00:07.369  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:00:07.369  1018  1030 D SettingsProvider: ret = -1
,08-26 15:00:07.369  1508  1508 D Launcher.HomeView: onResume
,08-26 15:00:07.379  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:00:07.379  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.379  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 15:00:07.379  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-26 15:00:07.379  1508  1508 D MenuAppsGridFragment: onResume
,08-26 15:00:07.389  1018  1321 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-26 15:00:07.389  1018  1321 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
08-26 15:00:07.389  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 15:00:07.389  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.389  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-26 15:00:07.389  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:00:07.389  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-26 15:00:07.389  1018  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-26 15:00:07.389  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.389  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.389  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.389  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.399  6997  6997 E Zygote  : MountEmulatedStorage(),
,08-26 15:00:07.409  6997  6997 E Zygote  : v2
08-26 15:00:07.409  6997  6997 I libpersona: KNOX_SDCARD checking this for 10039
08-26 15:00:07.409  6997  6997 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:07.409  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:07.409  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:00:07.409  1018  1321 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6997 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-26 15:00:07.409  1018  1030 D ActivityManager: handle home activity for 0,
08-26 15:00:07.409  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 15:00:07.409  1018  1030 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 15:00:07.409  1018  1030 D KnoxTimeoutHandler: post home show event for user 0
08-26 15:00:07.409  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:00:07.409  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:00:07.409  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:00:07.409  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:00:07.409  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-26 15:00:07.409  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 15:00:07.409  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:00:07.409  1508  1508 D Launcher.HomeView: onPause
08-26 15:00:07.409  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-26 15:00:07.409  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.409  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.409  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-26 15:00:07.419  1018  1043 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:00:07.419  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-26 15:00:07.419  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:00:07.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.419  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-26 15:00:07.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.439  7012  7012 E Zygote  : MountEmulatedStorage()
,08-26 15:00:07.439  7012  7012 E Zygote  : v2
08-26 15:00:07.439  7012  7012 I libpersona: KNOX_SDCARD checking this for 10089
08-26 15:00:07.439  7012  7012 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:07.439  7012  7012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:07.439  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:07.439  6997  6997 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:07.439  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7012 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-26 15:00:07.439  7012  7012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:07.449  7012  7012 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 15:00:07.449  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.449  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:00:07.449  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-26 15:00:07.449  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,08-26 15:00:07.449  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.449  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.449  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.449  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:00:07.459  6997  6997 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:00:07.459  7022  7022 E Zygote  : MountEmulatedStorage()
,08-26 15:00:07.459  7022  7022 E Zygote  : v2
08-26 15:00:07.459  7022  7022 I libpersona: KNOX_SDCARD checking this for 10139
08-26 15:00:07.459  7022  7022 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:07.459  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:07.469  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7022 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
08-26 15:00:07.469  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:00:07.469  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:07.479   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-26 15:00:07.479  7012  7012 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:07.489  7012  7012 D ActivityThread: Added TimaKeyStore provider
08-26 15:00:07.489  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 15:00:07.489  1018  3337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.489  1018  3337 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1508, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight,
08-26 15:00:07.489  1018  3337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.489  1018  3337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-26 15:00:07.489  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:07.489  7022  7022 D ActivityThread: Added TimaKeyStore provider
08-26 15:00:07.489  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 15:00:07.489  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.489  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.489  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
08-26 15:00:07.489  1018  1521 D InputDispatcher: Focus entered window: 1508
,08-26 15:00:07.489  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:00:07.489  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:00:07.489  1508  1508 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-26 15:00:07.489  2636  2636 D Recents_RecreateReceiver: onReceive by home
,08-26 15:00:07.499  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.499  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{130a44cd token=android.os.BinderProxy@e52e0ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-26 15:00:07.499  1018  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.499  1018  1511 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-26 15:00:07.499  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
08-26 15:00:07.499  1508  1508 D Launcher.HomeView: onStop
,08-26 15:00:07.509  1018  1521 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:00:07.509  1018  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.509  1018  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.509  1018  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.509  1018  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.509  1018  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:07.509  1018  1521 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6701 uid 10170,
,08-26 15:00:07.519  7012  7012 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:00:07.519  7012  7012 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 15:00:07.519  1178  1178 D PanelView: There is/are notification(s) 
08-26 15:00:07.529  1018  1511 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7044 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-26 15:00:07.529  1980  1980 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 15:00:07.529  7044  7044 E Zygote  : MountEmulatedStorage()
08-26 15:00:07.529  7044  7044 I libpersona: KNOX_SDCARD checking this for 10084
08-26 15:00:07.529  7044  7044 E Zygote  : v2
08-26 15:00:07.529  7044  7044 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:07.539  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:00:07.539  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:07.539  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 15:00:07.549  1508  1508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e52e0ac time:118446
,08-26 15:00:07.559  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:00:07.559  7044  7044 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:07.569  7022  7022 V TaskCloserActivity: TaskCloserActivity enter()
,08-26 15:00:07.569  1018  1048 W ActivityManager: mDVFSHelper.release()
08-26 15:00:07.569  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{712f9c1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:118469
,08-26 15:00:07.579  7022  7022 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-26 15:00:07.579  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.579  1018  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.579  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
08-26 15:00:07.579  7044  7044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:00:07.589  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.589  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.589  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-26 15:00:07.589  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,08-26 15:00:07.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:07.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:07.609  7064  7064 E Zygote  : MountEmulatedStorage(),
,08-26 15:00:07.609  7064  7064 E Zygote  : v2
,08-26 15:00:07.609  7064  7064 I libpersona: KNOX_SDCARD checking this for 10135
08-26 15:00:07.609  7064  7064 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:07.609  7064  7064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:00:07.619  1018  1031 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7064 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-26 15:00:07.619  7064  7064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:00:07.619  1018  1031 I ActivityManager: Killing 6653:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-26 15:00:07.619  7064  7064 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:07.629  1018  1321 I ActivityManager: Killing 6682:com.wsomacp/u0a23 (adj 15): empty #21
,08-26 15:00:07.629  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-26 15:00:07.639  7064  7064 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:07.639  6997  6997 D NearbySource: Nearby Source Create!
08-26 15:00:07.639  6997  6997 D NearbyContext: Nearby Context Create!
,08-26 15:00:07.639  7064  7064 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:07.659  7064  7064 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-26 15:00:07.659  7064  7064 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:00:07.659  7064  7064 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-26 15:00:07.659  7064  7064 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-26 15:00:07.659  7064  7064 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:00:07.679   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-26 15:00:07.679   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:00:07.679  6997  6997 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-26 15:00:07.679  6997  6997 D SLinkSource: Samsung link source created
,08-26 15:00:07.689  1018  1511 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:00:07.699  1018  3340 I ActivityManager: Killing 6732:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-26 15:00:07.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:07.739  1018  3340 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:00:07.739  6997  7079 D ContactProvider: getAllContactInfoList Start
,08-26 15:00:07.749  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:00:07.749  6997  6997 D GalleryCacheReady: Receive : home resume
,08-26 15:00:07.749  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:07.749  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.749  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-26 15:00:07.759  6407  6407 D Mms/UIEventReceiver: ui event
,08-26 15:00:07.759  1018  3340 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-26 15:00:07.759  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:07.759  1018  3340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:07.759  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-26 15:00:07.759  7022  7022 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-26 15:00:07.769  1018  3340 I ActivityManager: Killing 6219:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 15:00:07.779  6997  7079 D ContactProvider: getAllContactInfoList End
,08-26 15:00:07.789  6997  7079 I syncContacts: thread: 1288, sync time = 57
,08-26 15:00:07.989   295   295 E SMD     : DCD OFF
,08-26 15:00:08.719   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 15:00:10.999   295   295 E SMD     : DCD OFF
,08-26 15:00:13.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:13.999   295   295 E SMD     : DCD OFF
,08-26 15:00:14.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:15.149  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:15.149  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4305, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:00:15.149  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:00:15.149  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:00:15.149  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:00:15.149  1018  1521 D BatteryService: stay LED for charging
08-26 15:00:15.149  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:15.149  1018  1018 I MotionRecognitionService: Plugged
08-26 15:00:15.149  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:00:15.159  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:00:15.159  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:15.169  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:15.169  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:15.179  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:15.179  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:15.179  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:15.179  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:00:15.179  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:15.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:16.549  1018  1050 I PowerManagerService: [PWL] Off : 50s ago,
,08-26 15:00:16.559  1018  2884 D SSRM:n  : SIOP:: AP = 340,
,08-26 15:00:16.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:16.999   295   295 E SMD     : DCD OFF
,08-26 15:00:17.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:18.719   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:00:19.999   295   295 E SMD     : DCD OFF
,08-26 15:00:22.999   295   295 E SMD     : DCD OFF
,08-26 15:00:24.739  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:00:25.199  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:00:25.199  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4313, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:00:25.199  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-26 15:00:25.199  1018  1031 D BatteryService: stay LED for charging
08-26 15:00:25.199  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:25.199  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:25.199  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:00:25.209  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:00:25.209  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:00:25.209  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:00:25.209  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:25.219  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:25.219  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:25.229  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:00:25.229  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:25.229  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:25.229  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:00:25.229  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:26.009   295   295 E SMD     : DCD OFF
,08-26 15:00:26.579  1018  2884 D SSRM:n  : SIOP:: AP = 320,
,08-26 15:00:27.079  1018  1329 E Watchdog: !@Sync 4
,08-26 15:00:28.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:29.009   295   295 E SMD     : DCD OFF
,08-26 15:00:29.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:30.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:31.279  1018  2023 V SAMP_SPCM_test: CSC File load.. 
,08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings,
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 15:00:31.289  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time,
,08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time,
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn,
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction,
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:00:31.319  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-26 15:00:31.329  1018  2023 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-26 15:00:31.349  1018  2023 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 15:00:31.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:32.009   295   295 E SMD     : DCD OFF,
,08-26 15:00:32.719   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:33.719   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:00:35.009   295   295 E SMD     : DCD OFF
,08-26 15:00:35.249  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:35.249  1018  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4312, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:00:35.249  1018  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:00:35.249  1018  1424 D BatteryService: stay LED for charging
08-26 15:00:35.259  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:00:35.249  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:00:35.259  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:00:35.259  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:00:35.259  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,08-26 15:00:35.259  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:00:35.259  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:00:35.269  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:35.269  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:35.279  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:35.279  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:35.279  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:35.279  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:00:35.279  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:36.599  1018  2884 D SSRM:n  : SIOP:: AP = 310
,08-26 15:00:38.009   295   295 E SMD     : DCD OFF
,08-26 15:00:41.009   295   295 E SMD     : DCD OFF,
,08-26 15:00:41.559  1018  1050 I PowerManagerService: [PWL] Off : 75s ago
,08-26 15:00:44.019   295   295 E SMD     : DCD OFF
,08-26 15:00:44.739  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:45.299  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:45.299  1018  3337 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4316, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:00:45.299  1018  3337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:00:45.299  1018  3337 D BatteryService: stay LED for charging
08-26 15:00:45.299  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:45.309  1018  1018 I MotionRecognitionService: Plugged
08-26 15:00:45.309  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:00:45.309  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:45.309  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:45.309  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:00:45.309  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:45.319  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:45.319  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:45.329  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:45.339  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:45.339  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:45.339  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:00:45.339  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:46.619  1018  2884 D SSRM:n  : SIOP:: AP = 310,
,08-26 15:00:47.019   295   295 E SMD     : DCD OFF,
,08-26 15:00:48.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:49.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:50.019   295   295 E SMD     : DCD OFF
,08-26 15:00:50.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:51.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:52.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:53.019   295   295 E SMD     : DCD OFF
,08-26 15:00:53.729   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-26 15:00:55.349  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:55.349  1018  1506 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:00:55.349  1018  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:00:55.349  1018  1506 D BatteryService: stay LED for charging
08-26 15:00:55.349  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:55.359  1018  1018 I MotionRecognitionService: Plugged
08-26 15:00:55.359  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:00:55.359  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:55.359  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:55.359  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:00:55.359  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:55.369  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:55.369  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:55.379  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:55.389  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:55.389  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:55.389  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:00:55.389  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:00:56.019   295   295 E SMD     : DCD OFF
,08-26 15:00:56.649  1018  2884 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:00:57.079  1018  1329 E Watchdog: !@Sync 5
,08-26 15:00:58.049  1724  2723 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-26 15:00:59.029   295   295 E SMD     : DCD OFF
,08-26 15:01:02.029   295   295 E SMD     : DCD OFF
,08-26 15:01:04.739  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:01:05.029   295   295 E SMD     : DCD OFF
,08-26 15:01:05.399  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:06.679  1018  2884 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:01:08.029   295   295 E SMD     : DCD OFF
,08-26 15:01:11.029   295   295 E SMD     : DCD OFF
,08-26 15:01:11.579  1018  1050 I PowerManagerService: [PWL] Off : 105s ago,
,08-26 15:01:13.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:14.029   295   295 E SMD     : DCD OFF
,08-26 15:01:14.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:15.449  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:15.449  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4322, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:01:15.449  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:01:15.449  1018  1030 D BatteryService: stay LED for charging
08-26 15:01:15.449  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:15.459  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:01:15.459  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:01:15.459  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:01:15.459  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:01:15.469  1018  1018 I MotionRecognitionService: Plugged
08-26 15:01:15.469  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:01:15.469  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:15.469  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:01:15.479  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:15.489  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:15.489  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:15.489  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:01:15.489  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:01:15.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:16.699  1018  2884 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:01:16.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:17.039   295   295 E SMD     : DCD OFF
,08-26 15:01:17.729   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:18.729   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:01:20.039   295   295 E SMD     : DCD OFF
,08-26 15:01:23.039   295   295 E SMD     : DCD OFF
,08-26 15:01:24.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:25.499  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:25.499  1018  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:01:25.499  1018  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:01:25.499  1018  1424 D BatteryService: stay LED for charging
08-26 15:01:25.499  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:25.509  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:01:25.509  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:25.509  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:01:25.509  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:01:25.519  1018  1018 I MotionRecognitionService: Plugged
08-26 15:01:25.519  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,08-26 15:01:25.519  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:25.519  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:01:25.529  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:25.529  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:25.539  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:25.539  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:01:25.539  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:01:26.039   295   295 E SMD     : DCD OFF
,08-26 15:01:26.719  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:01:27.079  1018  1329 E Watchdog: !@Sync 6
,08-26 15:01:29.039   295   295 E SMD     : DCD OFF
,08-26 15:01:32.039   295   295 E SMD     : DCD OFF
,08-26 15:01:35.049   295   295 E SMD     : DCD OFF
,08-26 15:01:35.549  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:36.759  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:01:38.049   295   295 E SMD     : DCD OFF
,08-26 15:01:41.049   295   295 E SMD     : DCD OFF
,08-26 15:01:43.729   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:01:43.729   336   336 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:01:44.049   295   295 E SMD     : DCD OFF
,08-26 15:01:44.719  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 15:01:44.729  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 15:01:44.729  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>
08-26 15:01:44.729  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 15:01:44.739  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:01:44.739  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:01:44.739  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 15:01:44.739  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:44.749  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:01:44.759  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 15:01:44.759  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 15:01:44.759  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:01:44.799  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:44.809  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:44.809  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:44.819  1018  3337 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 15:01:44.819  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-26 15:01:44.819  1018  3337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 15:01:44.819  1018  3337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:44.819  1018  3337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:44.819  1018  3337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:44.839  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:44.879  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 15:01:44.879  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,08-26 15:01:44.879  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:01:44.879  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:44.879  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:44.909  1018  3340 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 15:01:44.909  1018  3340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-26 15:01:44.909  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:01:44.909  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:44.909  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:44.919  1689  7121 I VacuumService: Vacuum at: now=1472216504928 tag=VacuumService
,08-26 15:01:44.939  1018  1521 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:44.939  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:44.939  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:44.939  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:44.959  1018  1458 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:44.969  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:44.969  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:44.969  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:44.999  1018  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.009  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.009  1018  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.009  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.009  1018  1424 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.009  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.009  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.019  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.039  1689  7122 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-26 15:01:45.049  1018  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.049  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:01:45.049  1689  7122 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-26 15:01:45.049  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:01:45.049  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.079  1018  1424 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.079  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.079  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.079  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.089  1018  3337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.089  1018  3337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:01:45.089  1018  3337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.089  1018  3337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.099  1018  3340 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,08-26 15:01:45.099  1018  3340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-26 15:01:45.099  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.099  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.099  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.109  1689  7122 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 15:01:45.109  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:01:45.109  1689  7122 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 15:01:45.109  1689  7122 I System.out: (HTTPLog)-Thread-203-643233129: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-26 15:01:45.109  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:01:45.109   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:01:45.109   279  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:01:45.159  1689  7122 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:01:45.159  1689  7122 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:45.209  1689  7122 I qtaguid : Tagging socket 67 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:45.399  1689  7122 W Uploader:  no longer exists, so no auth token.
,08-26 15:01:45.409  1018  1424 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.409  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.409  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.409  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.419  1018  1521 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.419  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:01:45.419  1689  7122 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:45.419  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:01:45.419  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:01:45.419  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.499  1018  3340 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.499  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.499  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:01:45.499  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.509  1018  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.509  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.509  1018  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.509  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.519  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:01:45.519  1689  7122 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:45.609  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:45.609  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:01:45.609  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:01:45.619  1018  1321 D BatteryService: stay LED for charging
08-26 15:01:45.619  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:45.619  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:01:45.619  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:01:45.619  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:45.619  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:45.629  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:01:45.629  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:01:45.639  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:01:45.639  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:01:45.639  1018  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.639  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.639  1018  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.639  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:45.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:45.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:45.649  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:01:45.649  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:01:45.649  1018  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.649  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.649  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.649  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.659  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:01:45.659  1689  7122 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:45.729  1018  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.729  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.729  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:01:45.729  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.739  1018  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:45.739  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:45.739  1018  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:45.739  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:45.749  1689  7122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:01:45.749  1689  7122 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} for uid -1, pid: 1689, getuid(): 10011
,08-26 15:01:46.259  1018  3337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:01:46.269  1018  3337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:01:46.269  1018  3337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:01:46.269  1018  3337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:01:46.579  1018  1050 I PowerManagerService: [PWL] Off : 140s ago
,08-26 15:01:46.779  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:01:47.049   295   295 E SMD     : DCD OFF
,08-26 15:01:50.059   295   295 E SMD     : DCD OFF,
,08-26 15:01:53.059   295   295 E SMD     : DCD OFF
,08-26 15:01:53.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:54.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:55.659  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:55.669  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4326, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:01:55.669  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:01:55.669  1018  1321 D BatteryService: stay LED for charging
,08-26 15:01:55.669  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:55.669  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:55.669  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:55.679  1018  1018 I MotionRecognitionService: Plugged
08-26 15:01:55.679  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:01:55.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:01:55.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
08-26 15:01:55.679  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:55.679  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:55.679  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:01:55.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:01:55.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:01:55.699  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:01:55.699  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:01:55.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:56.059   295   295 E SMD     : DCD OFF
,08-26 15:01:56.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:56.799  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:01:57.079  1018  1329 E Watchdog: !@Sync 7
,08-26 15:01:57.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:58.739   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 15:01:59.059   295   295 E SMD     : DCD OFF
,08-26 15:01:59.989  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:02:02.059   295   295 E SMD     : DCD OFF
,08-26 15:02:03.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:04.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:04.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:05.059   295   295 E SMD     : DCD OFF
,08-26 15:02:05.709  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:05.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:06.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:06.829  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:07.739   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:08.069   295   295 E SMD     : DCD OFF
,08-26 15:02:08.749   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 15:02:11.069   295   295 E SMD     : DCD OFF
,08-26 15:02:14.069   295   295 E SMD     : DCD OFF
,08-26 15:02:15.759  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:02:15.759  1018  3337 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:15.759  1018  3337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:15.759  1018  3337 D BatteryService: stay LED for charging
08-26 15:02:15.759  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:15.769  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:15.769  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:15.769  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:02:15.769  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:15.779  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:02:15.779  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:02:15.779  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:02:15.779  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:15.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:02:15.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:15.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:02:15.799  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:02:15.799  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:02:16.849  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:17.069   295   295 E SMD     : DCD OFF
,08-26 15:02:18.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:19.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:20.069   295   295 E SMD     : DCD OFF
,08-26 15:02:20.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:21.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:22.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:23.069   295   295 E SMD     : DCD OFF
,08-26 15:02:23.749   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-26 15:02:24.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:25.809  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:02:25.809  1018  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:25.809  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:25.809  1018  1497 D BatteryService: stay LED for charging
08-26 15:02:25.809  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:25.819  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:02:25.819  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:25.819  1018  1018 I MotionRecognitionService: Plugged
08-26 15:02:25.819  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:02:25.819  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:02:25.819  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:25.819  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:02:25.829  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:25.839  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:02:25.839  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:25.839  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:25.839  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:02:25.839  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:02:26.079   295   295 E SMD     : DCD OFF
,08-26 15:02:26.579  1018  1050 I PowerManagerService: [PWL] Off : 180s ago,
,08-26 15:02:26.869  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:27.079  1018  1329 E Watchdog: !@Sync 8
,08-26 15:02:29.079   295   295 E SMD     : DCD OFF
,08-26 15:02:32.079   295   295 E SMD     : DCD OFF
,08-26 15:02:35.079   295   295 E SMD     : DCD OFF
,08-26 15:02:35.859  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:36.899  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:02:38.079   295   295 E SMD     : DCD OFF
,08-26 15:02:38.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:39.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:40.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:41.079   295   295 E SMD     : DCD OFF
,08-26 15:02:41.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:42.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:43.749   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-26 15:02:44.089   295   295 E SMD     : DCD OFF
,08-26 15:02:44.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:45.909  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:45.909  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4326, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:45.909  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:45.909  1018  1544 D BatteryService: stay LED for charging
08-26 15:02:45.909  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:02:45.909  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:02:45.919  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:02:45.919  1018  1018 I MotionRecognitionService: Plugged
08-26 15:02:45.919  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:02:45.919  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:02:45.919  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:45.919  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:02:45.919  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:45.939  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:45.939  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:45.939  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:45.939  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:02:45.939  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:02:46.919  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:47.089   295   295 E SMD     : DCD OFF
,08-26 15:02:50.089   295   295 E SMD     : DCD OFF
,08-26 15:02:53.089   295   295 E SMD     : DCD OFF
,08-26 15:02:55.969  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:02:55.969  1018  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:55.969  1018  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:55.969  1018  1424 D BatteryService: stay LED for charging
08-26 15:02:55.969  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:02:55.969  1018  1018 I MotionRecognitionService: Plugged
08-26 15:02:55.969  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:02:55.969  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:02:55.969  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:02:55.969  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:02:55.969  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:55.979  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:02:55.979  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:55.989  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:55.989  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:55.989  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:02:55.989  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:02:55.989  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:02:56.089   295   295 E SMD     : DCD OFF
,08-26 15:02:56.939  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:02:57.079  1018  1329 E Watchdog: !@Sync 9
,08-26 15:02:59.099   295   295 E SMD     : DCD OFF,
,08-26 15:03:02.099   295   295 E SMD     : DCD OFF
,08-26 15:03:03.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:04.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:04.749   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:05.099   295   295 E SMD     : DCD OFF
,08-26 15:03:05.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:06.019  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:06.019  1018  1458 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:06.019  1018  1458 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:06.019  1018  1458 D BatteryService: stay LED for charging
08-26 15:03:06.019  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:06.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:03:06.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:06.029  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:06.039  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:03:06.039  1018  1018 I MotionRecognitionService: Plugged
08-26 15:03:06.039  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:03:06.039  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:03:06.039  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:06.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:06.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:06.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:06.039  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:03:06.039  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:06.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:06.959  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:07.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:08.099   295   295 E SMD     : DCD OFF,
,08-26 15:03:08.759   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:03:11.099   295   295 E SMD     : DCD OFF,
,08-26 15:03:11.589  1018  1050 I PowerManagerService: [PWL] Off : 225s ago,
,08-26 15:03:14.099   295   295 E SMD     : DCD OFF,
,08-26 15:03:16.069  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:16.069  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:16.069  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:16.069  1018  1544 D BatteryService: stay LED for charging
,08-26 15:03:16.069  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:16.079  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:16.079  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:16.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:03:16.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:03:16.079  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:03:16.079  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:16.089  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:16.089  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:16.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:16.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:16.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:16.099  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:03:16.099  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:16.979  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:03:17.099   295   295 E SMD     : DCD OFF,
,08-26 15:03:20.109   295   295 E SMD     : DCD OFF,
,08-26 15:03:23.109   295   295 E SMD     : DCD OFF,
,08-26 15:03:24.049  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:03:24.049  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:03:24.049  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,08-26 15:03:24.049  1018  1087 I TLC_TIMA_PKM_initialize: initializing...
08-26 15:03:24.049  1018  1087 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-26 15:03:24.049  1018  1087 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-26 15:03:24.049  1018  1087 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-26 15:03:24.049  1018  1087 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-26 15:03:24.049  1018  1087 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
08-26 15:03:24.049  1018  1087 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-26 15:03:24.049  1018  1087 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-26 15:03:24.049  1018  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
08-26 15:03:24.049  1018  1087 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:03:24.079  1018  1087 D QSEECOMAPI: : Loaded image: APP id = 12
,08-26 15:03:24.089  1018  1087 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,08-26 15:03:24.099  1018  1087 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-26 15:03:24.749  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:26.049  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3,
08-26 15:03:26.049  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:03:26.049  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
08-26 15:03:26.049  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:03:26.109   295   295 E SMD     : DCD OFF,
,08-26 15:03:26.119  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:26.119  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:26.119  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:03:26.119  1018  1521 D BatteryService: stay LED for charging
08-26 15:03:26.119  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:26.129  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:03:26.129  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:26.129  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:03:26.129  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:03:26.129  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:03:26.129  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:26.139  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:26.139  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:26.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:03:26.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:26.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:26.149  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:03:26.149  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:26.999  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:03:27.079  1018  1329 E Watchdog: !@Sync 10,
,08-26 15:03:29.109   295   295 E SMD     : DCD OFF,
,08-26 15:03:32.109   295   295 E SMD     : DCD OFF
,08-26 15:03:33.759   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:03:33.759   336   336 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:03:35.119   295   295 E SMD     : DCD OFF
,08-26 15:03:36.169  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:03:36.169  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:36.169  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:36.169  1018  1321 D BatteryService: stay LED for charging
,08-26 15:03:36.169  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:03:36.169  1018  1018 I MotionRecognitionService: Plugged
08-26 15:03:36.169  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:36.179  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:36.179  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:36.179  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:03:36.179  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:36.189  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:36.189  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:36.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:36.209  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:36.209  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:36.209  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:03:36.209  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:37.019  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:03:38.119   295   295 E SMD     : DCD OFF
,08-26 15:03:41.119   295   295 E SMD     : DCD OFF
,08-26 15:03:44.119   295   295 E SMD     : DCD OFF
,08-26 15:03:44.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:03:46.219  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:46.219  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:46.219  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:46.219  1018  1031 D BatteryService: stay LED for charging
,08-26 15:03:46.219  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:46.229  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:03:46.229  1018  1018 I MotionRecognitionService: Plugged
08-26 15:03:46.229  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:03:46.229  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:46.229  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:03:46.229  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:46.229  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:46.239  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:46.239  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:46.249  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:46.249  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:46.249  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:03:46.249  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:47.029  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:03:47.119   295   295 E SMD     : DCD OFF
,08-26 15:03:48.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:49.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:50.119   295   295 E SMD     : DCD OFF
,08-26 15:03:50.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:51.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:52.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:53.119   295   295 E SMD     : DCD OFF
,08-26 15:03:53.759   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:03:56.129   295   295 E SMD     : DCD OFF
,08-26 15:03:56.269  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:56.269  1018  1506 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:56.269  1018  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:56.269  1018  1506 D BatteryService: stay LED for charging
,08-26 15:03:56.269  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:56.279  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:56.279  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:56.279  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:03:56.279  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:56.289  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:56.289  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:56.299  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:03:56.299  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:56.299  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:56.309  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:03:56.309  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:03:56.309  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:03:56.309  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:03:57.049  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:57.079  1018  1329 E Watchdog: !@Sync 11
,08-26 15:03:58.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:03:59.129   295   295 E SMD     : DCD OFF
,08-26 15:03:59.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:00.759   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:01.589  1018  1050 I PowerManagerService: [PWL] Off : 275s ago,
,08-26 15:04:01.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:02.129   295   295 E SMD     : DCD OFF
,08-26 15:04:02.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:03.769   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 15:04:04.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:05.129   295   295 E SMD     : DCD OFF
,08-26 15:04:06.319  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:04:06.319  1018  3340 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:04:06.319  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:06.319  1018  3340 D BatteryService: stay LED for charging
08-26 15:04:06.319  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:04:06.319  1018  1018 I MotionRecognitionService: Plugged
08-26 15:04:06.319  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:04:06.319  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:04:06.319  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:04:06.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:06.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:06.329  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:04:06.339  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:06.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:04:06.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:04:06.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:04:06.349  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:04:06.349  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:04:07.069  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:08.139   295   295 E SMD     : DCD OFF
,08-26 15:04:11.139   295   295 E SMD     : DCD OFF
,08-26 15:04:13.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:14.139   295   295 E SMD     : DCD OFF
,08-26 15:04:14.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:15.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:16.369  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:16.369  1018  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:04:16.369  1018  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:16.369  1018  1424 D BatteryService: stay LED for charging
,08-26 15:04:16.369  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:16.379  1018  1018 I MotionRecognitionService: Plugged
08-26 15:04:16.379  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:04:16.379  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:16.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:16.379  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:04:16.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:16.379  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:16.379  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:16.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:04:16.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:04:16.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:04:16.399  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:04:16.399  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:04:16.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:17.089  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:17.139   295   295 E SMD     : DCD OFF
,08-26 15:04:17.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:18.769   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:04:20.139   295   295 E SMD     : DCD OFF
,08-26 15:04:23.139   295   295 E SMD     : DCD OFF
,08-26 15:04:24.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:25.849  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:04:25.849  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:04:25.849  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:04:25.859  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:04:25.859  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:04:25.869  1018  1018 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,08-26 15:04:25.869  1018  1018 V SAMP_GCMKill: GCM kill size 0. just return
,08-26 15:04:25.879  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:04:25.879  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 15:04:25.879  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:04:25.889  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:04:25.899  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:04:25.899  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:04:25.919  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 15:04:25.929  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:04:26.149   295   295 E SMD     : DCD OFF
,08-26 15:04:26.419  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:27.089  1018  1329 E Watchdog: !@Sync 12
,08-26 15:04:27.119  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:29.149   295   295 E SMD     : DCD OFF
,08-26 15:04:32.149   295   295 E SMD     : DCD OFF
,08-26 15:04:33.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:34.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:35.149   295   295 E SMD     : DCD OFF
,08-26 15:04:35.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:36.469  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:04:36.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:37.159  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:37.769   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:38.149   295   295 E SMD     : DCD OFF,
,08-26 15:04:38.779   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:04:41.149   295   295 E SMD     : DCD OFF,
,08-26 15:04:44.159   295   295 E SMD     : DCD OFF,
,08-26 15:04:44.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:04:46.519  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:04:47.159   295   295 E SMD     : DCD OFF,
,08-26 15:04:47.199  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:50.159   295   295 E SMD     : DCD OFF,
,08-26 15:04:53.159   295   295 E SMD     : DCD OFF,
,08-26 15:04:56.159   295   295 E SMD     : DCD OFF,
,08-26 15:04:56.569  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:56.569  1018  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 15:04:56.569  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:56.569  1018  1497 D BatteryService: stay LED for charging
08-26 15:04:56.569  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:04:56.569  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:56.569  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:56.579  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:04:56.579  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:04:56.579  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:04:56.579  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:04:56.579  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:56.579  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:56.589  1018  1050 I PowerManagerService: [PWL] Off : 330s ago
,08-26 15:04:56.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:04:56.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:04:56.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:04:56.599  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:04:56.599  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:04:57.089  1018  1329 E Watchdog: !@Sync 13,
,08-26 15:04:57.209  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:58.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:59.169   295   295 E SMD     : DCD OFF,
,08-26 15:04:59.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:59.989  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:05:00.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:01.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:02.169   295   295 E SMD     : DCD OFF
,08-26 15:05:02.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:05:03.779   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:05:04.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:05:05.169   295   295 E SMD     : DCD OFF
,08-26 15:05:06.609  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:05:07.249  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:08.169   295   295 E SMD     : DCD OFF,
,08-26 15:05:11.169   295   295 E SMD     : DCD OFF,
,08-26 15:05:14.169   295   295 E SMD     : DCD OFF
,08-26 15:05:16.659  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:05:17.179   295   295 E SMD     : DCD OFF,
,08-26 15:05:17.289  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:05:20.179   295   295 E SMD     : DCD OFF
,08-26 15:05:23.179   295   295 E SMD     : DCD OFF,
,08-26 15:05:24.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:05:26.179   295   295 E SMD     : DCD OFF,
,08-26 15:05:26.709  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:05:27.089  1018  1329 E Watchdog: !@Sync 14,
,08-26 15:05:27.329  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:28.779   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 15:05:28.779   336   336 I Atfwd_Daemon: result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:05:29.179   295   295 E SMD     : DCD OFF
,08-26 15:05:32.189   295   295 E SMD     : DCD OFF
,08-26 15:05:35.189   295   295 E SMD     : DCD OFF
,08-26 15:05:36.759  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:37.369  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:05:38.189   295   295 E SMD     : DCD OFF,
,08-26 15:05:41.189   295   295 E SMD     : DCD OFF,
,08-26 15:05:44.189   295   295 E SMD     : DCD OFF
,08-26 15:05:44.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:05:46.809  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:05:47.199   295   295 E SMD     : DCD OFF,
,08-26 15:05:47.409  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:48.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:05:49.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:05:50.199   295   295 E SMD     : DCD OFF
,08-26 15:05:50.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:51.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:52.779   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:53.199   295   295 E SMD     : DCD OFF,
,08-26 15:05:53.779   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:05:56.199   295   295 E SMD     : DCD OFF,
,08-26 15:05:56.649  1018  1050 I PowerManagerService: [PWL] Off : 390s ago,
,08-26 15:05:56.869  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:05:57.089  1018  1329 E Watchdog: !@Sync 15,
,08-26 15:05:57.449  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:05:58.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:59.199   295   295 E SMD     : DCD OFF,
,08-26 15:05:59.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:06:00.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:01.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:02.209   295   295 E SMD     : DCD OFF,
,08-26 15:06:02.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:03.789   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 15:06:04.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:06:05.209   295   295 E SMD     : DCD OFF
,08-26 15:06:06.919  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:06.919  1018  1458 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:06:06.919  1018  1458 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:06:06.919  1018  1458 D BatteryService: stay LED for charging
08-26 15:06:06.919  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:06.929  1018  1018 I MotionRecognitionService: Plugged
08-26 15:06:06.929  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:06:06.929  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:06.929  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:06:06.929  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:06:06.929  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:06:06.939  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:06.939  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:06:06.949  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:06:06.949  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:06.949  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:06.949  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:06:06.949  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:06:07.459  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:08.209   295   295 E SMD     : DCD OFF,
,08-26 15:06:11.209   295   295 E SMD     : DCD OFF,
,08-26 15:06:13.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:14.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:14.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:15.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:16.179   333   333 I bootchecker: bootchecker wake up!!
,08-26 15:06:16.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:16.969  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:06:16.969  1018  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:06:16.969  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:06:16.969  1018  1497 D BatteryService: stay LED for charging
08-26 15:06:16.969  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:16.979  1018  1018 I MotionRecognitionService: Plugged
08-26 15:06:16.979  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:06:16.979  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:06:16.979  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:06:16.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:06:16.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:06:16.989  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:16.999  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:06:17.009  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:06:17.009  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:06:17.009  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:17.009  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:06:17.009  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:06:17.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:17.479  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:17.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:06:18.789   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-26 15:06:20.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:23.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:24.759  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:06:26.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:27.019  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:06:27.019  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:06:27.019  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:06:27.019  1018  1137 D BatteryService: stay LED for charging
08-26 15:06:27.019  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:27.029  1018  1018 I MotionRecognitionService: Plugged
08-26 15:06:27.029  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:06:27.029  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:27.029  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:06:27.039  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:06:27.039  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:06:27.039  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:27.049  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:06:27.059  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:06:27.059  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:27.059  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:06:27.059  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:06:27.059  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:06:27.089  1018  1329 E Watchdog: !@Sync 16,
,08-26 15:06:27.499  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:29.219   295   295 E SMD     : DCD OFF,
,08-26 15:06:32.229   295   295 E SMD     : DCD OFF,
,08-26 15:06:33.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:34.789   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:35.229   295   295 E SMD     : DCD OFF,
,08-26 15:06:35.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:36.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:37.069  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:37.069  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:06:37.069  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:06:37.079  1018  1030 D BatteryService: stay LED for charging
08-26 15:06:37.079  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:37.079  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:06:37.079  1018  1018 I MotionRecognitionService: Plugged
08-26 15:06:37.079  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:06:37.079  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:06:37.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:06:37.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:06:37.099  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:37.099  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:06:37.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:06:37.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:37.109  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:06:37.109  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:06:37.109  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:06:37.509  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:37.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:38.229   295   295 E SMD     : DCD OFF,
,08-26 15:06:38.799   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:06:41.229   295   295 E SMD     : DCD OFF,
,08-26 15:06:44.229   295   295 E SMD     : DCD OFF
,08-26 15:06:44.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:06:47.129  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:47.239   295   295 E SMD     : DCD OFF,
,08-26 15:06:47.549  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:50.239   295   295 E SMD     : DCD OFF
,08-26 15:06:53.239   295   295 E SMD     : DCD OFF,
,08-26 15:06:56.239   295   295 E SMD     : DCD OFF,
,08-26 15:06:57.089  1018  1329 E Watchdog: !@Sync 17,
,08-26 15:06:57.179  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:06:57.589  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:58.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:06:59.239   295   295 E SMD     : DCD OFF,
,08-26 15:06:59.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:07:00.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:07:01.679  1018  1050 I PowerManagerService: [PWL] Off : 455s ago,
,08-26 15:07:01.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:07:02.249   295   295 E SMD     : DCD OFF,
,08-26 15:07:02.799   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:07:03.799   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:07:04.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:07:05.249   295   295 E SMD     : DCD OFF
,08-26 15:07:07.229  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:07:07.229  1018  1511 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:07.229  1018  1511 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:07.229  1018  1511 D BatteryService: stay LED for charging
,08-26 15:07:07.229  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:07:07.229  1018  1018 I MotionRecognitionService: Plugged
08-26 15:07:07.229  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,08-26 15:07:07.229  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:07:07.239  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:07:07.239  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:07:07.239  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:07.249  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:07.249  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:07.259  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:07.259  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:07:07.259  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:07:07.259  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:07:07.259  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:07:07.619  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:08.249   295   295 E SMD     : DCD OFF
,08-26 15:07:11.249   295   295 E SMD     : DCD OFF
,08-26 15:07:14.249   295   295 E SMD     : DCD OFF,
,08-26 15:07:17.249   295   295 E SMD     : DCD OFF
,08-26 15:07:17.279  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:07:17.659  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:20.259   295   295 E SMD     : DCD OFF
,08-26 15:07:23.259   295   295 E SMD     : DCD OFF,
,08-26 15:07:24.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:07:26.259   295   295 E SMD     : DCD OFF,
,08-26 15:07:27.089  1018  1329 E Watchdog: !@Sync 18,
,08-26 15:07:27.319  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:07:27.319  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:27.319  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:27.319  1018  1544 D BatteryService: stay LED for charging
08-26 15:07:27.319  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:27.329  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:07:27.329  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:07:27.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:07:27.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:27.339  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:07:27.339  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:07:27.339  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:27.339  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:27.359  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:27.359  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:07:27.359  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:27.359  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:07:27.359  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:07:27.669  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:07:28.799   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 15:07:28.799   336   336 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:07:29.259   295   295 E SMD     : DCD OFF,
,08-26 15:07:32.259   295   295 E SMD     : DCD OFF,
,08-26 15:07:35.259   295   295 E SMD     : DCD OFF,
,08-26 15:07:37.379  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:37.379  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:37.379  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:37.379  1018  1321 D BatteryService: stay LED for charging
,08-26 15:07:37.379  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:37.379  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:07:37.379  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:07:37.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:07:37.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:07:37.389  1018  1018 I MotionRecognitionService: Plugged
08-26 15:07:37.389  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:07:37.399  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:37.399  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:37.409  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:37.409  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:07:37.409  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:37.409  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:07:37.409  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:07:37.689  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:07:38.269   295   295 E SMD     : DCD OFF,
,08-26 15:07:41.269   295   295 E SMD     : DCD OFF,
,08-26 15:07:44.269   295   295 E SMD     : DCD OFF,
,08-26 15:07:44.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:07:47.269   295   295 E SMD     : DCD OFF,
,08-26 15:07:47.419  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:07:47.729  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:50.279   295   295 E SMD     : DCD OFF
,08-26 15:07:53.279   295   295 E SMD     : DCD OFF,
,08-26 15:07:53.799   336   336 I Atfwd_Daemon: Stop the daemon....,
,08-26 15:07:56.279   295   295 E SMD     : DCD OFF,
,08-26 15:07:57.089  1018  1329 E Watchdog: !@Sync 19,
,08-26 15:07:57.479  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:57.479  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:57.479  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:57.479  1018  1137 D BatteryService: stay LED for charging
08-26 15:07:57.479  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:57.479  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:07:57.479  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:07:57.489  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:07:57.489  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:57.489  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:07:57.489  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:07:57.499  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:57.499  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:57.509  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:57.519  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:57.519  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:07:57.519  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:07:57.519  1178  1213 I art     : Background sticky concurrent mark sweep GC freed 17346(703KB) AllocSpace objects, 0(0B) LOS objects, 3% free, 23MB/24MB, paused 12.048ms total 37.807ms
08-26 15:07:57.519  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:07:57.739  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:07:59.279   295   295 E SMD     : DCD OFF,
,08-26 15:08:02.279   295   295 E SMD     : DCD OFF,
,08-26 15:08:04.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:05.279   295   295 E SMD     : DCD OFF
,08-26 15:08:07.519  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:08:07.519  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:08:07.519  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:08:07.519  1018  1030 D BatteryService: stay LED for charging,
08-26 15:08:07.519  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:08:07.529  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:08:07.529  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:08:07.529  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:08:07.529  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:08:07.539  1018  1018 I MotionRecognitionService: Plugged
08-26 15:08:07.539  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:08:07.539  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:08:07.539  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:08:07.549  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:08:07.549  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:08:07.549  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:08:07.549  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:08:07.549  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:08:07.759  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:08.289   295   295 E SMD     : DCD OFF
,08-26 15:08:11.289   295   295 E SMD     : DCD OFF,
,08-26 15:08:11.679  1018  1050 I PowerManagerService: [PWL] Off : 525s ago,
,08-26 15:08:14.289   295   295 E SMD     : DCD OFF,
,08-26 15:08:17.289   295   295 E SMD     : DCD OFF,
,08-26 15:08:17.569  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:08:17.799  1018  2884 D SSRM:n  : SIOP:: AP = 280
,08-26 15:08:20.289   295   295 E SMD     : DCD OFF,
,08-26 15:08:23.299   295   295 E SMD     : DCD OFF,
,08-26 15:08:24.049  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
08-26 15:08:24.049  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-26 15:08:24.049  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:08:24.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:24.889  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:08:24.889  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:08:24.889  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:24.889  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:26.299   295   295 E SMD     : DCD OFF,
,08-26 15:08:27.089  1018  1329 E Watchdog: !@Sync 20,
,08-26 15:08:27.619  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:08:27.619  1018  3337 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:08:27.619  1018  3337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:08:27.619  1018  3337 D BatteryService: stay LED for charging
08-26 15:08:27.619  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:08:27.629  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:08:27.629  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:08:27.629  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:08:27.629  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:08:27.629  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:08:27.629  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:08:27.639  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:08:27.639  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:08:27.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:08:27.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:08:27.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:08:27.649  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:08:27.649  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:08:27.809  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:29.299   295   295 E SMD     : DCD OFF,
,08-26 15:08:32.299   295   295 E SMD     : DCD OFF,
,08-26 15:08:35.299   295   295 E SMD     : DCD OFF,
,08-26 15:08:37.669  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:37.669  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:08:37.669  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:08:37.669  1018  1544 D BatteryService: stay LED for charging
08-26 15:08:37.669  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:08:37.669  1018  1018 I MotionRecognitionService: Plugged
08-26 15:08:37.669  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:08:37.679  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:08:37.679  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:08:37.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:08:37.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:08:37.689  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:08:37.689  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:08:37.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:08:37.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:08:37.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:08:37.699  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:08:37.699  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:08:37.829  1018  2884 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:38.299   295   295 E SMD     : DCD OFF
,08-26 15:08:41.309   295   295 E SMD     : DCD OFF,
,08-26 15:08:44.309   295   295 E SMD     : DCD OFF
,08-26 15:08:44.769  1018  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:08:47.309   295   295 E SMD     : DCD OFF,
,08-26 15:08:47.719  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:47.869  1018  2884 D SSRM:n  : SIOP:: AP = 280,
,08-26 15:08:50.309   295   295 E SMD     : DCD OFF,
,08-26 15:08:53.309   295   295 E SMD     : DCD OFF,
,08-26 15:08:56.319   295   295 E SMD     : DCD OFF,
,08-26 15:08:57.089  1018  1329 E Watchdog: !@Sync 21,
,08-26 15:08:57.769  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:57.909  1018  2884 D SSRM:n  : SIOP:: AP = 280,
,08-26 15:08:59.319   295   295 E SMD     : DCD OFF,
,08-26 15:09:02.319   295   295 E SMD     : DCD OFF,
,08-26 15:09:05.319   295   295 E SMD     : DCD OFF
,08-26 15:09:07.819  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:09:07.949  1018  2884 D SSRM:n  : SIOP:: AP = 280,
,08-26 15:09:08.329   295   295 E SMD     : DCD OFF,
,08-26 15:09:11.329   295   295 E SMD     : DCD OFF,
,08-26 15:09:14.329   295   295 E SMD     : DCD OFF
,08-26 15:09:17.329   295   295 E SMD     : DCD OFF,
,08-26 15:09:17.869  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:17.979  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:09:20.329   295   295 E SMD     : DCD OFF,
,08-26 15:09:23.339   295   295 E SMD     : DCD OFF,
,08-26 15:09:25.879  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:09:26.339   295   295 E SMD     : DCD OFF,
,08-26 15:09:26.729  1018  1050 I PowerManagerService: [PWL] Off : 600s ago,
,08-26 15:09:27.089  1018  1329 E Watchdog: !@Sync 22,
,08-26 15:09:27.909  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:09:28.019  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:09:29.339   295   295 E SMD     : DCD OFF,
,08-26 15:09:32.339   295   295 E SMD     : DCD OFF
,08-26 15:09:35.339   295   295 E SMD     : DCD OFF,
,08-26 15:09:37.959  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:09:38.059  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:09:38.349   295   295 E SMD     : DCD OFF,
,08-26 15:09:41.349   295   295 E SMD     : DCD OFF,
,08-26 15:09:44.349   295   295 E SMD     : DCD OFF
,08-26 15:09:47.349   295   295 E SMD     : DCD OFF,
,08-26 15:09:48.009  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:09:48.009  1018  3337 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:09:48.009  1018  3337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:09:48.009  1018  3337 D BatteryService: stay LED for charging
08-26 15:09:48.009  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:09:48.019  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:09:48.019  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:09:48.019  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:09:48.019  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:09:48.019  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:09:48.019  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:09:48.029  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:09:48.029  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:09:48.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:09:48.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:09:48.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:09:48.049  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:09:48.049  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:09:48.069  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:09:50.349   295   295 E SMD     : DCD OFF,
,08-26 15:09:53.349   295   295 E SMD     : DCD OFF,
,08-26 15:09:56.359   295   295 E SMD     : DCD OFF,
,08-26 15:09:57.089  1018  1329 E Watchdog: !@Sync 23,
,08-26 15:09:58.059  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:58.059  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:09:58.059  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:09:58.059  1018  1544 D BatteryService: stay LED for charging
08-26 15:09:58.059  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:09:58.069  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:09:58.069  1018  1018 I MotionRecognitionService: Plugged
08-26 15:09:58.069  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:09:58.069  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:09:58.069  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:09:58.069  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:09:58.079  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:09:58.079  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:09:58.089  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:09:58.089  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:09:58.089  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:09:58.089  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:09:58.089  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:09:58.099  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:09:59.359   295   295 E SMD     : DCD OFF,
,08-26 15:10:02.359   295   295 E SMD     : DCD OFF,
,08-26 15:10:05.359   295   295 E SMD     : DCD OFF,
,08-26 15:10:08.109  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:10:08.109  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:08.109  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:08.109  1018  1321 D BatteryService: stay LED for charging
08-26 15:10:08.109  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-26 15:10:08.119  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:10:08.119  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:08.119  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:10:08.119  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:08.119  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:08.119  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:08.129  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:08.129  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:08.139  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:10:08.139  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:08.139  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:08.139  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:08.139  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:10:08.139  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:10:08.359   295   295 E SMD     : DCD OFF,
,08-26 15:10:11.369   295   295 E SMD     : DCD OFF,
,08-26 15:10:14.369   295   295 E SMD     : DCD OFF,
,08-26 15:10:17.369   295   295 E SMD     : DCD OFF,
,08-26 15:10:18.159  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:10:18.159  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:18.159  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:18.159  1018  1031 D BatteryService: stay LED for charging
08-26 15:10:18.159  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:18.169  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:10:18.169  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:10:18.169  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:18.169  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:18.169  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:10:18.169  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:18.179  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:18.179  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:18.189  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:10:18.189  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:18.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:18.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:18.199  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-26 15:10:18.199  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:10:20.369   295   295 E SMD     : DCD OFF,
,08-26 15:10:23.379   295   295 E SMD     : DCD OFF,
,08-26 15:10:26.379   295   295 E SMD     : DCD OFF,
,08-26 15:10:27.099  1018  1329 E Watchdog: !@Sync 24,
,08-26 15:10:28.209  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:10:28.209  1018  1424 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:28.209  1018  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:28.209  1018  1424 D BatteryService: stay LED for charging
08-26 15:10:28.209  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:28.219  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:28.219  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:28.219  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:28.219  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:28.229  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:10:28.229  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:10:28.229  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:28.229  1018  1018 I MotionRecognitionService: Plugged
08-26 15:10:28.229  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:28.249  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:28.249  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:28.249  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:28.249  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:10:28.249  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:10:29.379   295   295 E SMD     : DCD OFF,
,08-26 15:10:32.379   295   295 E SMD     : DCD OFF,
,08-26 15:10:35.379   295   295 E SMD     : DCD OFF,
,08-26 15:10:38.259  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:10:38.259  1018  1458 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:38.259  1018  1458 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:38.259  1018  1458 D BatteryService: stay LED for charging
08-26 15:10:38.259  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:38.259  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:10:38.259  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:38.269  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:38.269  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:10:38.269  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:38.269  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:38.269  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:10:38.279  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:38.279  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:38.289  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:38.289  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:38.299  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:38.299  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:10:38.299  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:10:38.379   295   295 E SMD     : DCD OFF
,08-26 15:10:41.389   295   295 E SMD     : DCD OFF,
,08-26 15:10:44.389   295   295 E SMD     : DCD OFF,
,08-26 15:10:46.739  1018  1050 I PowerManagerService: [PWL] Off : 680s ago
,08-26 15:10:47.389   295   295 E SMD     : DCD OFF,
,08-26 15:10:48.299  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:10:48.319  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:48.319  1018  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:48.319  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:10:48.319  1018  1497 D BatteryService: stay LED for charging
08-26 15:10:48.319  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:10:48.329  1018  1018 I MotionRecognitionService: Plugged
08-26 15:10:48.329  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,08-26 15:10:48.329  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:48.329  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:48.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:48.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:48.339  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:48.339  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:48.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:10:48.359  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:48.359  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:10:48.359  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:10:48.359  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:10:50.389   295   295 E SMD     : DCD OFF,
,08-26 15:10:53.389   295   295 E SMD     : DCD OFF,
,08-26 15:10:56.399   295   295 E SMD     : DCD OFF,
,08-26 15:10:57.099  1018  1329 E Watchdog: !@Sync 25,
,08-26 15:10:58.339  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:10:58.369  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:59.399   295   295 E SMD     : DCD OFF,
,08-26 15:11:02.399   295   295 E SMD     : DCD OFF,
,08-26 15:11:05.399   295   295 E SMD     : DCD OFF
,08-26 15:11:08.379  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:11:08.399   295   295 E SMD     : DCD OFF,
,08-26 15:11:08.419  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:11:08.419  1018  3340 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:11:08.419  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:11:08.419  1018  3340 D BatteryService: stay LED for charging
08-26 15:11:08.419  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:11:08.429  1018  1018 I MotionRecognitionService: Plugged
08-26 15:11:08.429  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:11:08.429  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:11:08.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:11:08.429  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:11:08.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:11:08.439  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:11:08.439  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:11:08.439  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:11:08.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:11:08.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:11:08.459  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:11:08.459  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:11:11.409   295   295 E SMD     : DCD OFF
,08-26 15:11:14.409   295   295 E SMD     : DCD OFF,
,08-26 15:11:17.409   295   295 E SMD     : DCD OFF,
,08-26 15:11:18.419  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:11:18.469  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:18.469  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:11:18.469  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:11:18.469  1018  1521 D BatteryService: stay LED for charging
08-26 15:11:18.469  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:11:18.479  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:11:18.479  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:11:18.479  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:11:18.479  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:11:18.479  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:11:18.479  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:11:18.479  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:11:18.489  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:11:18.489  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:11:18.489  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:11:18.499  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:11:18.499  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:11:18.499  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:11:20.409   295   295 E SMD     : DCD OFF,
,08-26 15:11:23.409   295   295 E SMD     : DCD OFF,
,08-26 15:11:26.419   295   295 E SMD     : DCD OFF,
,08-26 15:11:27.099  1018  1329 E Watchdog: !@Sync 26,
,08-26 15:11:28.459  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:11:28.519  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:11:29.419   295   295 E SMD     : DCD OFF
,08-26 15:11:32.419   295   295 E SMD     : DCD OFF,
,08-26 15:11:35.419   295   295 E SMD     : DCD OFF,
,08-26 15:11:38.419   295   295 E SMD     : DCD OFF,
,08-26 15:11:38.499  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:11:38.569  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:41.419   295   295 E SMD     : DCD OFF
,08-26 15:11:44.429   295   295 E SMD     : DCD OFF,
,08-26 15:11:47.429   295   295 E SMD     : DCD OFF,
,08-26 15:11:48.539  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:11:48.629  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:50.429   295   295 E SMD     : DCD OFF
,08-26 15:11:53.429   295   295 E SMD     : DCD OFF
,08-26 15:11:56.439   295   295 E SMD     : DCD OFF
,08-26 15:11:57.099  1018  1329 E Watchdog: !@Sync 27
,08-26 15:11:58.579  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:58.679  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:11:59.439   295   295 E SMD     : DCD OFF
,08-26 15:12:02.439   295   295 E SMD     : DCD OFF
,08-26 15:12:05.439   295   295 E SMD     : DCD OFF
,08-26 15:12:08.439   295   295 E SMD     : DCD OFF
,08-26 15:12:08.619  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:12:08.719  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:08.729  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:12:08.729  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:12:08.729  1018  1030 D BatteryService: stay LED for charging
08-26 15:12:08.729  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:08.729  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:12:08.729  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:12:08.729  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:12:08.729  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:12:08.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:12:08.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:12:08.739  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:08.739  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:12:08.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:08.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:08.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:08.749  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:12:08.759  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:12:11.439   295   295 E SMD     : DCD OFF,
,08-26 15:12:11.739  1018  1050 I PowerManagerService: [PWL] Off : 765s ago
,08-26 15:12:14.449   295   295 E SMD     : DCD OFF,
,08-26 15:12:17.449   295   295 E SMD     : DCD OFF,
,08-26 15:12:18.659  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:12:18.779  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:18.779  1018  1511 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:12:18.779  1018  1511 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:12:18.779  1018  1511 D BatteryService: stay LED for charging
08-26 15:12:18.779  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:18.779  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:12:18.779  1018  1018 I MotionRecognitionService: Plugged
08-26 15:12:18.779  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:12:18.779  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:12:18.779  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:12:18.789  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:12:18.789  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:18.789  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:12:18.809  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:12:18.809  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:18.809  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:18.809  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:12:18.809  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:12:20.449   295   295 E SMD     : DCD OFF,
,08-26 15:12:23.449   295   295 E SMD     : DCD OFF,
,08-26 15:12:26.449   295   295 E SMD     : DCD OFF,
,08-26 15:12:27.099  1018  1329 E Watchdog: !@Sync 28,
,08-26 15:12:28.699  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:12:28.829  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:29.449   295   295 E SMD     : DCD OFF
,08-26 15:12:32.459   295   295 E SMD     : DCD OFF,
,08-26 15:12:35.459   295   295 E SMD     : DCD OFF,
,08-26 15:12:38.459   295   295 E SMD     : DCD OFF,
,08-26 15:12:38.749  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:12:38.869  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:12:41.459   295   295 E SMD     : DCD OFF
,08-26 15:12:44.459   295   295 E SMD     : DCD OFF,
,08-26 15:12:47.459   295   295 E SMD     : DCD OFF
,08-26 15:12:48.789  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:12:48.919  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:12:50.469   295   295 E SMD     : DCD OFF
,08-26 15:12:53.469   295   295 E SMD     : DCD OFF,
,08-26 15:12:56.469   295   295 E SMD     : DCD OFF
,08-26 15:12:57.099  1018  1329 E Watchdog: !@Sync 29,
,08-26 15:12:58.819  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:12:58.969  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:12:58.969  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:12:58.969  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:12:58.969  1018  1544 D BatteryService: stay LED for charging
,08-26 15:12:58.969  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:58.979  1018  1018 I MotionRecognitionService: Plugged
08-26 15:12:58.979  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:12:58.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:12:58.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:12:58.979  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:12:58.979  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:12:58.989  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:12:58.989  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:12:58.989  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:58.989  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:12:58.999  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:12:58.999  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:12:58.999  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:12:59.469   295   295 E SMD     : DCD OFF
,08-26 15:13:02.469   295   295 E SMD     : DCD OFF,
,08-26 15:13:05.469   295   295 E SMD     : DCD OFF,
,08-26 15:13:08.479   295   295 E SMD     : DCD OFF,
,08-26 15:13:08.859  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:09.019  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:09.019  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:13:09.019  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:13:09.019  1018  1137 D BatteryService: stay LED for charging
08-26 15:13:09.019  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:09.029  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:13:09.029  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:13:09.029  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:13:09.029  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:13:09.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:13:09.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:13:09.029  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:13:09.029  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:13:09.029  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:09.029  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:13:09.029  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:13:09.049  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:13:09.049  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:13:11.479   295   295 E SMD     : DCD OFF,
,08-26 15:13:14.479   295   295 E SMD     : DCD OFF,
,08-26 15:13:17.479   295   295 E SMD     : DCD OFF,
,08-26 15:13:18.899  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:19.069  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:13:19.069  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 15:13:19.069  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:13:19.069  1018  1030 D BatteryService: stay LED for charging,
08-26 15:13:19.069  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:19.079  1018  1018 I MotionRecognitionService: Plugged
08-26 15:13:19.079  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:13:19.079  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:13:19.079  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:19.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:13:19.079  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:13:19.089  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:13:19.089  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:13:19.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:19.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:19.099  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:19.099  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:13:19.099  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:13:20.489   295   295 E SMD     : DCD OFF
,08-26 15:13:23.489   295   295 E SMD     : DCD OFF
,08-26 15:13:24.049  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:13:24.049  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:13:24.049  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:13:25.999  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:13:25.999  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:13:26.009  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:26.009  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:26.489   295   295 E SMD     : DCD OFF
,08-26 15:13:27.099  1018  1329 E Watchdog: !@Sync 30
,08-26 15:13:28.939  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:29.119  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:29.119  1018  1511 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:13:29.119  1018  1511 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:13:29.119  1018  1511 D BatteryService: stay LED for charging
08-26 15:13:29.119  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:29.119  1018  1018 I MotionRecognitionService: Plugged
08-26 15:13:29.119  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:13:29.119  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:13:29.119  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:29.129  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:13:29.129  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:13:29.129  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:29.129  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:13:29.129  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:13:29.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:13:29.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:13:29.149  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-26 15:13:29.149  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:13:29.489   295   295 E SMD     : DCD OFF,
,08-26 15:13:32.489   295   295 E SMD     : DCD OFF,
,08-26 15:13:35.489   295   295 E SMD     : DCD OFF,
,08-26 15:13:38.499   295   295 E SMD     : DCD OFF,
,08-26 15:13:38.979  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:39.169  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:41.499   295   295 E SMD     : DCD OFF,
,08-26 15:13:41.759  1018  1050 I PowerManagerService: [PWL] Off : 855s ago
,08-26 15:13:44.499   295   295 E SMD     : DCD OFF,
,08-26 15:13:47.499   295   295 E SMD     : DCD OFF
,08-26 15:13:49.019  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:49.229  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:13:50.499   295   295 E SMD     : DCD OFF
,08-26 15:13:53.499   295   295 E SMD     : DCD OFF,
,08-26 15:13:56.509   295   295 E SMD     : DCD OFF
,08-26 15:13:57.099  1018  1329 E Watchdog: !@Sync 31,
,08-26 15:13:59.059  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:13:59.269  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:13:59.509   295   295 E SMD     : DCD OFF
,08-26 15:14:02.509   295   295 E SMD     : DCD OFF
,08-26 15:14:05.509   295   295 E SMD     : DCD OFF,
,08-26 15:14:08.509   295   295 E SMD     : DCD OFF,
,08-26 15:14:09.099  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:09.319  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:09.319  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:09.319  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:09.319  1018  1544 D BatteryService: stay LED for charging
08-26 15:14:09.319  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:14:09.329  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:14:09.329  1018  1018 I MotionRecognitionService: Plugged
08-26 15:14:09.329  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:14:09.329  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:14:09.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:09.329  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:14:09.329  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:14:09.329  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:09.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:09.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:09.349  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:09.349  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:14:09.349  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:14:11.509   295   295 E SMD     : DCD OFF,
,08-26 15:14:14.519   295   295 E SMD     : DCD OFF,
,08-26 15:14:17.519   295   295 E SMD     : DCD OFF,
,08-26 15:14:19.139  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:19.369  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:14:19.369  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:19.369  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:19.369  1018  1137 D BatteryService: stay LED for charging
,08-26 15:14:19.369  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:14:19.379  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:14:19.379  1018  1018 I MotionRecognitionService: Plugged
08-26 15:14:19.379  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:14:19.379  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:14:19.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:19.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:14:19.389  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:19.389  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:19.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:19.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:19.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:19.399  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:14:19.399  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:14:20.519   295   295 E SMD     : DCD OFF
,08-26 15:14:23.519   295   295 E SMD     : DCD OFF
,08-26 15:14:26.529   295   295 E SMD     : DCD OFF,
,08-26 15:14:27.099  1018  1329 E Watchdog: !@Sync 32,
,08-26 15:14:29.179  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:29.419  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:14:29.419  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:29.419  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:29.419  1018  1030 D BatteryService: stay LED for charging
,08-26 15:14:29.419  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:14:29.419  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:14:29.419  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:14:29.429  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:14:29.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:29.429  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:14:29.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:14:29.439  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:29.439  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:29.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:29.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:29.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:29.449  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:14:29.449  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:14:29.529   295   295 E SMD     : DCD OFF
,08-26 15:14:32.529   295   295 E SMD     : DCD OFF
,08-26 15:14:35.529   295   295 E SMD     : DCD OFF,
,08-26 15:14:38.529   295   295 E SMD     : DCD OFF,
,08-26 15:14:39.229  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:39.469  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:14:39.469  1018  3340 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:39.469  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:39.469  1018  3340 D BatteryService: stay LED for charging
,08-26 15:14:39.469  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:14:39.469  1018  1018 I MotionRecognitionService: Plugged
08-26 15:14:39.469  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:14:39.469  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:14:39.469  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:14:39.479  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:14:39.479  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:14:39.489  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:39.489  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:39.499  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:39.499  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:39.499  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:39.499  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:14:39.499  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:14:41.539   295   295 E SMD     : DCD OFF
,08-26 15:14:44.539   295   295 E SMD     : DCD OFF
,08-26 15:14:47.539   295   295 E SMD     : DCD OFF,
,08-26 15:14:49.269  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:49.519  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:50.539   295   295 E SMD     : DCD OFF
,08-26 15:14:53.539   295   295 E SMD     : DCD OFF,
,08-26 15:14:56.539   295   295 E SMD     : DCD OFF
,08-26 15:14:57.099  1018  1329 E Watchdog: !@Sync 33,
,08-26 15:14:59.309  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:14:59.539   295   295 E SMD     : DCD OFF
,08-26 15:14:59.569  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:14:59.569  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:59.569  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:59.569  1018  1544 D BatteryService: stay LED for charging,
08-26 15:14:59.569  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:14:59.569  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:14:59.569  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:59.569  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:14:59.569  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:14:59.579  1018  1018 I MotionRecognitionService: Plugged
08-26 15:14:59.579  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:14:59.579  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:14:59.579  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:59.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:59.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:14:59.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:14:59.599  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:14:59.599  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:15:02.549   295   295 E SMD     : DCD OFF,
,08-26 15:15:05.549   295   295 E SMD     : DCD OFF
,08-26 15:15:08.549   295   295 E SMD     : DCD OFF,
,08-26 15:15:09.349  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:09.619  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:15:09.619  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:15:09.619  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:15:09.619  1018  1137 D BatteryService: stay LED for charging
08-26 15:15:09.619  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:15:09.619  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:15:09.619  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:15:09.619  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:15:09.619  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:15:09.619  1018  1018 I MotionRecognitionService: Plugged
08-26 15:15:09.619  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:15:09.629  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:09.629  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:15:09.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:15:09.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:15:09.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:15:09.649  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:15:09.649  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:15:11.549   295   295 E SMD     : DCD OFF,
,08-26 15:15:14.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:16.769  1018  1050 I PowerManagerService: [PWL] Off : 950s ago,
,08-26 15:15:17.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:19.389  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:19.669  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:19.669  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:15:19.669  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:15:19.669  1018  1030 D BatteryService: stay LED for charging
,08-26 15:15:19.669  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:15:19.669  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:15:19.669  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:15:19.679  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:15:19.679  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:15:19.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:15:19.679  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:15:19.679  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:19.679  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:15:19.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:15:19.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:15:19.699  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:15:19.699  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:15:19.699  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:15:20.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:23.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:26.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:27.099  1018  1329 E Watchdog: !@Sync 34,
,08-26 15:15:29.429  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:29.559   295   295 E SMD     : DCD OFF,
,08-26 15:15:29.719  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:15:32.569   295   295 E SMD     : DCD OFF
,08-26 15:15:35.569   295   295 E SMD     : DCD OFF,
,08-26 15:15:38.569   295   295 E SMD     : DCD OFF,
,08-26 15:15:39.469  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:39.769  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:41.569   295   295 E SMD     : DCD OFF
,08-26 15:15:44.579   295   295 E SMD     : DCD OFF,
,08-26 15:15:47.579   295   295 E SMD     : DCD OFF
,08-26 15:15:49.509  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:49.819  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:15:50.579   295   295 E SMD     : DCD OFF,
,08-26 15:15:53.579   295   295 E SMD     : DCD OFF,
,08-26 15:15:56.589   295   295 E SMD     : DCD OFF,
,08-26 15:15:57.099  1018  1329 E Watchdog: !@Sync 35,
,08-26 15:15:59.559  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:15:59.589   295   295 E SMD     : DCD OFF,
,08-26 15:15:59.869  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:02.589   295   295 E SMD     : DCD OFF
,08-26 15:16:05.589   295   295 E SMD     : DCD OFF,
,08-26 15:16:08.589   295   295 E SMD     : DCD OFF,
,08-26 15:16:09.599  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:16:09.919  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:16:11.589   295   295 E SMD     : DCD OFF,
,08-26 15:16:14.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:17.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:19.639  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:16:19.969  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:19.969  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:19.969  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:19.969  1018  1030 D BatteryService: stay LED for charging
,08-26 15:16:19.969  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:19.969  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:19.969  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:16:19.969  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:16:19.979  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:16:19.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:19.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:19.979  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:19.989  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:19.999  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:16:19.999  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:16:19.999  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:16:19.999  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:16:19.999  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:16:20.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:23.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:26.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:27.099  1018  1329 E Watchdog: !@Sync 36,
,08-26 15:16:29.599   295   295 E SMD     : DCD OFF,
,08-26 15:16:29.679  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:16:30.019  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:16:30.019  1018  1511 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:30.019  1018  1511 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:30.019  1018  1511 D BatteryService: stay LED for charging
08-26 15:16:30.019  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:30.019  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:30.019  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:30.019  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:16:30.019  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:16:30.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:16:30.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:30.029  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:30.029  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:30.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:16:30.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:16:30.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:16:30.049  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:16:30.049  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:16:32.609   295   295 E SMD     : DCD OFF,
,08-26 15:16:35.609   295   295 E SMD     : DCD OFF,
,08-26 15:16:38.609   295   295 E SMD     : DCD OFF,
,08-26 15:16:39.729  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:16:40.069  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:16:41.609   295   295 E SMD     : DCD OFF,
,08-26 15:16:44.609   295   295 E SMD     : DCD OFF,
,08-26 15:16:47.619   295   295 E SMD     : DCD OFF
,08-26 15:16:49.769  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:16:50.119  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:16:50.119  1018  3340 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:50.119  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:50.119  1018  3340 D BatteryService: stay LED for charging
08-26 15:16:50.119  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:50.119  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:16:50.119  1018  1018 I MotionRecognitionService: Plugged
08-26 15:16:50.119  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:50.119  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:16:50.119  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:50.119  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:50.129  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:16:50.129  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:50.139  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:16:50.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:16:50.149  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:16:50.149  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:16:50.149  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:16:50.619   295   295 E SMD     : DCD OFF,
,08-26 15:16:53.619   295   295 E SMD     : DCD OFF,
,08-26 15:16:56.619   295   295 E SMD     : DCD OFF,
,08-26 15:16:56.769  1018  1050 I PowerManagerService: [PWL] Off : 1050s ago,
,08-26 15:16:57.099  1018  1329 E Watchdog: !@Sync 37,
,08-26 15:16:59.619   295   295 E SMD     : DCD OFF,
,08-26 15:16:59.809  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:17:00.169  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:00.169  1018  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:00.169  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:00.169  1018  1321 D BatteryService: stay LED for charging
08-26 15:17:00.169  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:00.169  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:17:00.169  1018  1018 I MotionRecognitionService: Plugged
08-26 15:17:00.169  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:17:00.169  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:17:00.169  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:00.169  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:17:00.179  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:00.179  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:00.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:00.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:17:00.199  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:00.199  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:17:00.199  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:17:02.619   295   295 E SMD     : DCD OFF,
,08-26 15:17:05.629   295   295 E SMD     : DCD OFF,
,08-26 15:17:08.629   295   295 E SMD     : DCD OFF,
,08-26 15:17:09.859  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:17:10.219  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:11.629   295   295 E SMD     : DCD OFF,
,08-26 15:17:14.629   295   295 E SMD     : DCD OFF,
,08-26 15:17:17.639   295   295 E SMD     : DCD OFF
,08-26 15:17:19.899  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:17:20.269  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:20.269  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:20.269  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:17:20.269  1018  1521 D BatteryService: stay LED for charging
08-26 15:17:20.269  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:20.269  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:17:20.269  1018  1018 I MotionRecognitionService: Plugged,
08-26 15:17:20.269  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:17:20.269  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:17:20.269  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:20.269  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
08-26 15:17:20.279  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:20.279  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:20.279  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:20.289  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:20.299  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:20.299  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:17:20.299  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:17:20.639   295   295 E SMD     : DCD OFF,
,08-26 15:17:23.639   295   295 E SMD     : DCD OFF,
,08-26 15:17:26.639   295   295 E SMD     : DCD OFF,
,08-26 15:17:27.099  1018  1329 E Watchdog: !@Sync 38,
,08-26 15:17:29.639   295   295 E SMD     : DCD OFF,
,08-26 15:17:29.939  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:17:30.319  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:32.639   295   295 E SMD     : DCD OFF
,08-26 15:17:35.649   295   295 E SMD     : DCD OFF,
,08-26 15:17:36.619  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-26 15:17:36.639  1018  1018 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,08-26 15:17:36.639  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:17:36.639  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:17:36.649  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:17:36.649  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:17:36.649  1018  1018 V SAMP_GCMKill: GCM kill size 0. just return
,08-26 15:17:36.659  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:17:36.669  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-26 15:17:36.669  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:17:36.699  1018  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:17:36.699  1018  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,08-26 15:17:36.699  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:17:36.699  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:17:36.699  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:17:36.709  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:17:36.709  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:17:36.719  1018  1458 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:17:36.719  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:17:36.719  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:17:36.719  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:17:36.719  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:17:36.729  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 15:17:36.739  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:17:36.759  1857  7517 I EventLogService: Aggregate from 1472215656546 (log), 1472215656546 (data)
,08-26 15:17:38.649   295   295 E SMD     : DCD OFF
,08-26 15:17:39.959  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:17:40.369  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:40.369  1018  1511 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:17:40.369  1018  1511 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:40.369  1018  1511 D BatteryService: stay LED for charging
,08-26 15:17:40.369  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:40.379  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:17:40.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:40.379  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:17:40.379  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:17:40.379  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:17:40.379  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:17:40.379  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:40.379  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:40.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:40.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:40.399  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:40.399  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:17:40.399  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:17:41.649   295   295 E SMD     : DCD OFF,
,08-26 15:17:44.649   295   295 E SMD     : DCD OFF,
,08-26 15:17:47.659   295   295 E SMD     : DCD OFF,
,08-26 15:17:49.999  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:17:50.419  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:17:50.419  1018  3340 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:50.419  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:50.419  1018  3340 D BatteryService: stay LED for charging
08-26 15:17:50.419  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:50.419  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:17:50.419  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-26 15:17:50.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:17:50.429  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:17:50.429  1018  1018 I MotionRecognitionService: Plugged
08-26 15:17:50.429  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:17:50.429  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:50.439  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:50.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:50.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:50.449  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:17:50.449  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:17:50.449  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:17:50.659   295   295 E SMD     : DCD OFF
,08-26 15:17:53.659   295   295 E SMD     : DCD OFF,
,08-26 15:17:56.659   295   295 E SMD     : DCD OFF,
,08-26 15:17:57.099  1018  1329 E Watchdog: !@Sync 39,
,08-26 15:17:59.659   295   295 E SMD     : DCD OFF,
,08-26 15:17:59.999  1018  1096 V AlarmManager: waitForAlarm result :8,
,08-26 15:18:00.039  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:18:00.469  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:02.659   295   295 E SMD     : DCD OFF,
,08-26 15:18:05.669   295   295 E SMD     : DCD OFF,
,08-26 15:18:08.669   295   295 E SMD     : DCD OFF
,08-26 15:18:10.049  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:18:10.519  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:18:11.669   295   295 E SMD     : DCD OFF
,08-26 15:18:14.669   295   295 E SMD     : DCD OFF,
,08-26 15:18:17.669   295   295 E SMD     : DCD OFF
,08-26 15:18:20.099  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:18:20.569  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:18:20.569  1018  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:20.569  1018  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:20.569  1018  1544 D BatteryService: stay LED for charging
08-26 15:18:20.569  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:20.569  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:18:20.569  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:18:20.569  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:18:20.569  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:18:20.579  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:18:20.579  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:18:20.589  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:18:20.589  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:20.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:18:20.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:18:20.599  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:18:20.599  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:18:20.599  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:18:20.669   295   295 E SMD     : DCD OFF
,08-26 15:18:23.679   295   295 E SMD     : DCD OFF,
,08-26 15:18:24.049  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:18:24.049  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:18:24.049  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:18:24.689  1018  1042 I UsageStatsService: User[0] Flushing usage stats to disk
,08-26 15:18:24.719  1018  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,08-26 15:18:24.719  1018  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1472217504726
,08-26 15:18:24.719  1018  1103 I ApplicationPolicy: updateDataUsageMap
,08-26 15:18:24.889  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:18:24.889  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:18:24.889  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:24.889  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:25.069  1018  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,08-26 15:18:25.079  1018  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,08-26 15:18:25.099  1018  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1472217505106
,08-26 15:18:26.679   295   295 E SMD     : DCD OFF
,08-26 15:18:27.109  1018  1329 E Watchdog: !@Sync 40
,08-26 15:18:29.679   295   295 E SMD     : DCD OFF,
,08-26 15:18:30.119  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:18:30.619  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:32.679   295   295 E SMD     : DCD OFF,
,08-26 15:18:35.679   295   295 E SMD     : DCD OFF,
,08-26 15:18:38.689   295   295 E SMD     : DCD OFF,
,08-26 15:18:40.129  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:18:40.669  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:41.689   295   295 E SMD     : DCD OFF,
,08-26 15:18:41.789  1018  1050 I PowerManagerService: [PWL] Off : 1155s ago
,08-26 15:18:44.689   295   295 E SMD     : DCD OFF,
,08-26 15:18:47.689   295   295 E SMD     : DCD OFF,
,08-26 15:18:50.179  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:18:50.689   295   295 E SMD     : DCD OFF
,08-26 15:18:50.719  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:50.719  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:50.719  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:50.719  1018  1031 D BatteryService: stay LED for charging
08-26 15:18:50.719  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:50.719  1018  1018 I MotionRecognitionService: Plugged
08-26 15:18:50.719  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:18:50.729  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:18:50.729  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:18:50.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:50.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:18:50.739  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:18:50.739  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:50.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:18:50.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:18:50.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:18:50.749  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:18:50.749  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:18:53.699   295   295 E SMD     : DCD OFF
,08-26 15:18:56.699   295   295 E SMD     : DCD OFF
,08-26 15:18:57.109  1018  1329 E Watchdog: !@Sync 41,
,08-26 15:18:59.699   295   295 E SMD     : DCD OFF,
,08-26 15:19:00.219  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:00.769  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:00.769  1018  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:19:00.769  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:19:00.769  1018  1521 D BatteryService: stay LED for charging
08-26 15:19:00.769  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:19:00.769  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:19:00.769  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:19:00.779  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:19:00.779  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:19:00.779  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:19:00.789  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:19:00.789  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:19:00.789  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:19:00.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:19:00.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:19:00.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:19:00.799  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:19:00.799  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:19:02.699   295   295 E SMD     : DCD OFF
,08-26 15:19:05.699   295   295 E SMD     : DCD OFF,
,08-26 15:19:08.709   295   295 E SMD     : DCD OFF,
,08-26 15:19:10.239  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:10.819  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:11.709   295   295 E SMD     : DCD OFF
,08-26 15:19:14.709   295   295 E SMD     : DCD OFF
,08-26 15:19:17.709   295   295 E SMD     : DCD OFF
,08-26 15:19:20.279  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:20.709   295   295 E SMD     : DCD OFF,
,08-26 15:19:20.869  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:23.709   295   295 E SMD     : DCD OFF
,08-26 15:19:26.719   295   295 E SMD     : DCD OFF,
,08-26 15:19:27.109  1018  1329 E Watchdog: !@Sync 42,
,08-26 15:19:29.719   295   295 E SMD     : DCD OFF,
,08-26 15:19:30.329  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:30.919  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:32.719   295   295 E SMD     : DCD OFF
,08-26 15:19:35.719   295   295 E SMD     : DCD OFF
,08-26 15:19:38.729   295   295 E SMD     : DCD OFF,
,08-26 15:19:40.339  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:40.979  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:41.729   295   295 E SMD     : DCD OFF
,08-26 15:19:44.729   295   295 E SMD     : DCD OFF
,08-26 15:19:47.729   295   295 E SMD     : DCD OFF
,08-26 15:19:50.379  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:19:50.729   295   295 E SMD     : DCD OFF,
,08-26 15:19:51.019  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:53.729   295   295 E SMD     : DCD OFF
,08-26 15:19:56.739   295   295 E SMD     : DCD OFF
,08-26 15:19:57.109  1018  1329 E Watchdog: !@Sync 43,
,08-26 15:19:59.739   295   295 E SMD     : DCD OFF,
,08-26 15:20:00.429  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:20:01.069  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:02.739   295   295 E SMD     : DCD OFF
,08-26 15:20:05.739   295   295 E SMD     : DCD OFF
,08-26 15:20:08.739   295   295 E SMD     : DCD OFF
,08-26 15:20:10.449  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:20:11.119  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:11.739   295   295 E SMD     : DCD OFF
,08-26 15:20:14.749   295   295 E SMD     : DCD OFF
,08-26 15:20:17.749   295   295 E SMD     : DCD OFF
,08-26 15:20:20.469  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:20:20.749   295   295 E SMD     : DCD OFF,
,08-26 15:20:21.169  1018  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:23.749   295   295 E SMD     : DCD OFF
,08-26 15:20:26.759   295   295 E SMD     : DCD OFF
,08-26 15:20:27.109  1018  1329 E Watchdog: !@Sync 44
,08-26 15:20:29.759   295   295 E SMD     : DCD OFF
,08-26 15:20:30.519  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:20:31.219  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:31.869  1018  1050 I PowerManagerService: [PWL] Off : 1266s ago
,08-26 15:20:32.759   295   295 E SMD     : DCD OFF
,08-26 15:20:35.759   295   295 E SMD     : DCD OFF
,08-26 15:20:38.759   295   295 E SMD     : DCD OFF,
,08-26 15:20:40.539  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:20:41.269  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:41.759   295   295 E SMD     : DCD OFF
,08-26 15:20:44.769   295   295 E SMD     : DCD OFF
,08-26 15:20:47.769   295   295 E SMD     : DCD OFF
,08-26 15:20:50.579  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:20:50.769   295   295 E SMD     : DCD OFF,
,08-26 15:20:51.319  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:53.769   295   295 E SMD     : DCD OFF
,08-26 15:20:56.769   295   295 E SMD     : DCD OFF
,08-26 15:20:57.109  1018  1329 E Watchdog: !@Sync 45
,08-26 15:20:59.769   295   295 E SMD     : DCD OFF,
,08-26 15:21:00.629  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:21:01.369  1018  3337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:21:02.779   295   295 E SMD     : DCD OFF
,08-26 15:21:05.779   295   295 E SMD     : DCD OFF
,08-26 15:21:08.779   295   295 E SMD     : DCD OFF,
,08-26 15:21:10.649  1018  2884 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:11.409  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:11.779   295   295 E SMD     : DCD OFF
,08-26 15:21:14.789   295   295 E SMD     : DCD OFF
,08-26 15:21:17.789   295   295 E SMD     : DCD OFF,
,08-26 15:21:20.699  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:21:20.789   295   295 E SMD     : DCD OFF,
,08-26 15:21:21.459  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:23.789   295   295 E SMD     : DCD OFF
,08-26 15:21:26.789   295   295 E SMD     : DCD OFF
,08-26 15:21:27.109  1018  1329 E Watchdog: !@Sync 46
,08-26 15:21:29.799   295   295 E SMD     : DCD OFF,
,08-26 15:21:30.739  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:21:31.509  1018  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:32.799   295   295 E SMD     : DCD OFF
,08-26 15:21:35.799   295   295 E SMD     : DCD OFF
,08-26 15:21:38.799   295   295 E SMD     : DCD OFF,
,08-26 15:21:40.759  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:21:41.569  1018  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:41.799   295   295 E SMD     : DCD OFF
,08-26 15:21:44.799   295   295 E SMD     : DCD OFF
,08-26 15:21:47.799   295   295 E SMD     : DCD OFF
,08-26 15:21:50.809   295   295 E SMD     : DCD OFF
,08-26 15:21:50.809  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:21:51.619  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:53.809   295   295 E SMD     : DCD OFF
,08-26 15:21:56.809   295   295 E SMD     : DCD OFF
,08-26 15:21:57.109  1018  1329 E Watchdog: !@Sync 47,
,08-26 15:21:59.809   295   295 E SMD     : DCD OFF,
,08-26 15:22:00.849  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:22:01.669  1018  1511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:02.819   295   295 E SMD     : DCD OFF
,08-26 15:22:05.819   295   295 E SMD     : DCD OFF
,08-26 15:22:08.819   295   295 E SMD     : DCD OFF,
,08-26 15:22:10.869  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:22:11.719  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:11.719  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:11.719  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:11.719  1018  1030 D BatteryService: stay LED for charging
08-26 15:22:11.719  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:11.719  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:22:11.719  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:22:11.729  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:22:11.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:22:11.729  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:22:11.729  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:11.729  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:22:11.729  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:11.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-26 15:22:11.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:22:11.749  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:22:11.749  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:22:11.749  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:22:11.819   295   295 E SMD     : DCD OFF
,08-26 15:22:14.819   295   295 E SMD     : DCD OFF
,08-26 15:22:17.819   295   295 E SMD     : DCD OFF,
,08-26 15:22:20.829   295   295 E SMD     : DCD OFF,
,08-26 15:22:20.929  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:22:21.769  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:21.769  1018  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:21.769  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:21.769  1018  1497 D BatteryService: stay LED for charging
08-26 15:22:21.769  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:21.769  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:22:21.769  1018  1018 I MotionRecognitionService: Plugged
08-26 15:22:21.769  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:22:21.769  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:22:21.779  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:22:21.779  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:21.779  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:21.779  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:21.779  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:21.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:21.799  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:22:21.799  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:22:21.799  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:22:23.829   295   295 E SMD     : DCD OFF
,08-26 15:22:26.829   295   295 E SMD     : DCD OFF
,08-26 15:22:26.869  1018  1050 I PowerManagerService: [PWL] Off : 1381s ago,
,08-26 15:22:27.109  1018  1329 E Watchdog: !@Sync 48,
,08-26 15:22:29.829   295   295 E SMD     : DCD OFF,
,08-26 15:22:30.969  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:22:31.819  1018  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:31.819  1018  1506 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:31.819  1018  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:31.819  1018  1506 D BatteryService: stay LED for charging
,08-26 15:22:31.819  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:31.819  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:22:31.819  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:22:31.819  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:31.829  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:22:31.829  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:22:31.829  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:31.829  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:31.829  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:31.849  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:31.849  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:31.849  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:22:31.849  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:22:31.849  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:22:32.839   295   295 E SMD     : DCD OFF
,08-26 15:22:35.839   295   295 E SMD     : DCD OFF
,08-26 15:22:36.659  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:22:38.839   295   295 E SMD     : DCD OFF,
,08-26 15:22:40.989  1018  2884 D SSRM:n  : SIOP:: AP = 270
,08-26 15:22:41.839   295   295 E SMD     : DCD OFF
,08-26 15:22:41.869  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:41.869  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:41.869  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:41.869  1018  1030 D BatteryService: stay LED for charging
08-26 15:22:41.869  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:41.869  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:22:41.869  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:22:41.869  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:22:41.869  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:22:41.879  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:22:41.879  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:41.879  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:41.879  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:41.899  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:41.899  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:22:41.899  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:22:41.899  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:22:41.899  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:22:44.839   295   295 E SMD     : DCD OFF
,08-26 15:22:47.839   295   295 E SMD     : DCD OFF
,08-26 15:22:50.839   295   295 E SMD     : DCD OFF,
,08-26 15:22:51.029  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:22:51.919  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:53.849   295   295 E SMD     : DCD OFF
,08-26 15:22:56.849   295   295 E SMD     : DCD OFF
,08-26 15:22:57.109  1018  1329 E Watchdog: !@Sync 49,
,08-26 15:22:59.849   295   295 E SMD     : DCD OFF,
,08-26 15:23:01.079  1018  2884 D SSRM:n  : SIOP:: AP = 270,
,08-26 15:23:01.959  1018  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:23:01.969  1018  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:23:01.969  1018  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:23:01.969  1018  1521 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,08-26 15:23:01.969  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:23:01.969  1018  1078 E lights  : write_int failed to open -1
08-26 15:23:01.969  1018  1521 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
08-26 15:23:01.969  1018  1018 I MotionRecognitionService: Plugged
08-26 15:23:01.969  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:23:01.969  1018  1521 D BatteryService: turn on LED for fully charged
08-26 15:23:01.969  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-26 15:23:01.969  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,08-26 15:23:01.969  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:23:01.969  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:23:01.979  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
08-26 15:23:01.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:23:01.979  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:23:01.979  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:23:01.979  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:23:01.989  1018  1506 D SecContentProvider2: uri = 14 selection = getSealedState,
08-26 15:23:01.989  1018  1506 D SecContentProvider2: mCursor = null
,08-26 15:23:02.009  1018  1137 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,08-26 15:23:02.009  1018  1137 V ApplicationPolicy: isApplicationStateBlocked userId -1 pkgname com.android.systemui
,08-26 15:23:02.009  1018  1018 I ValidateNoPeople: skipping global notification
,08-26 15:23:02.009  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,08-26 15:23:02.019  1018  1506 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1178
,08-26 15:23:02.019  1018  1506 I PowerManagerService: !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
08-26 15:23:02.019  1018  1506 I PowerManagerService: Waking up from sleep (uid 10049)...
,08-26 15:23:02.039  1018  1506 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,08-26 15:23:02.039  1018  1157 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@3301ec09)
,08-26 15:23:02.039  1178  1209 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
,08-26 15:23:02.039  1178  1209 D KeyguardViewMediator: notifyScreenOnLocked
,08-26 15:23:02.039  1508  1508 D Launcher: onRestart, Launcher: 673396263
,08-26 15:23:02.049  1018  1506 D PowerManagerService: [s] UserActivityState : 0 -> 1
08-26 15:23:02.049  1018  1506 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-26 15:23:02.049  1018  1046 D WindowOrientationListener: sensor enabled
08-26 15:23:02.049  1018  1050 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
08-26 15:23:02.049  1018  1046 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
08-26 15:23:02.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:23:02.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:23:02.049  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:23:02.049  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:23:02.049  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 15:23:02.049  1018  1055 I libsuspend: !@autosuspend_wakeup_count_disable,
08-26 15:23:02.049  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
08-26 15:23:02.049  1018  1055 I libsuspend: !@autosuspend_wakeup_count_disable done
08-26 15:23:02.049  1018  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
08-26 15:23:02.049  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
08-26 15:23:02.049  1018  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
08-26 15:23:02.049  1018  1055 D DisplayManagerService: !@display_state: OFF -> ON
,08-26 15:23:02.059   258   258 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb82e2690
08-26 15:23:02.059   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-26 15:23:02.059  1018  1046 D SensorService: [SO] changed settle time [0]
08-26 15:23:02.059  1018  1046 D SensorService: [SO] setDelay [200000000]
08-26 15:23:02.059  1018  1046 D SensorService: [SO] activate (ident=0xb8d479a0, enabled=1)
08-26 15:23:02.059  1018  1046 D SensorService: [SO] AR_init
08-26 15:23:02.059  1018  1046 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
08-26 15:23:02.059   258   258 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
08-26 15:23:02.059   258   258 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,08-26 15:23:02.059  1018  1048 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-26 15:23:02.059  1018  1018 V ActivityManager: Display changed displayId=0
,08-26 15:23:02.069  1018  1046 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,08-26 15:23:02.099  1018  1157 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:23:02.119  1508  1508 D Launcher: onStart, Launcher: 673396263
,08-26 15:23:02.119  1508  1508 D Launcher.HomeView: onStart
,08-26 15:23:02.129  1508  1508 D Launcher: onResume, Launcher: 673396263
,08-26 15:23:02.129  1018  1458 D SettingsProvider: name = kids_home_mode
08-26 15:23:02.129  1018  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:23:02.129  1018  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:23:02.129  1018  1458 D SettingsProvider: selectionArgs: false
08-26 15:23:02.129  1018  1458 D SettingsProvider: selectionArgs: 10006
08-26 15:23:02.129  1018  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:23:02.129  1018  1458 D SettingsProvider: ret = -1
,08-26 15:23:02.129  1178  1178 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,08-26 15:23:02.129  1508  1508 D Launcher.HomeView: onResume
,08-26 15:23:02.139  1018  3337 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,08-26 15:23:02.139  1468  1620 D NfcService: call the applyRouting
,08-26 15:23:02.149  1980  1980 D SamsungIME: showDlgMsgBox : false true true
,08-26 15:23:02.149  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:23:02.149  1178  1178 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
08-26 15:23:02.149  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.149  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
08-26 15:23:02.149  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,08-26 15:23:02.159  1178  1178 D PersonaManager: PersonaID is invalid or persona doesn't exists. : -1
,08-26 15:23:02.159  1508  1508 D MenuAppsGridFragment: onResume
,08-26 15:23:02.169  1018  1506 D ActivityManager: handle home activity for 0
08-26 15:23:02.169  1018  1506 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 15:23:02.169  1018  1506 D KnoxTimeoutHandler: post home show event for user 0
08-26 15:23:02.169  1018  1506 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:23:02.169  1018  1506 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:23:02.169  1018  1506 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:23:02.169  1018  1018 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
08-26 15:23:02.169  1018  1018 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
08-26 15:23:02.169  1018  1018 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
08-26 15:23:02.169  1018  1018 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
08-26 15:23:02.169  1018  1018 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
08-26 15:23:02.169  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,08-26 15:23:02.169  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
08-26 15:23:02.169  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-26 15:23:02.169  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
08-26 15:23:02.169  1018  2884 D SSRM:a  : DeviceInfo:: 000000000000
08-26 15:23:02.169  1018  2884 D SSRM:a  : SettingsAirViewInfo:: 000000000
,08-26 15:23:02.179  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:23:02.179  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.179  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,08-26 15:23:02.179  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:02.179  1178  1178 I PhoneStatusBar: Icon Only
08-26 15:23:02.179  1178  1178 I StatusBar: Icon Only
,08-26 15:23:02.179  1178  1178 D PanelView: There is/are notification(s) 
08-26 15:23:02.179  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
08-26 15:23:02.179  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
08-26 15:23:02.179  1508  1508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e52e0ac time:1493077
,08-26 15:23:02.189  1468  1620 D SecNfcJni: RoutingManager::commitRouting
,08-26 15:23:02.189  1468  2123 D SecNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
08-26 15:23:02.189  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:02.189  1178  1178 I PhoneStatusBar: Icon Only
08-26 15:23:02.189  1178  1178 I StatusBar: Icon Only
08-26 15:23:02.189  1178  1178 D PanelView: There is/are notification(s) 
08-26 15:23:02.189  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-26 15:23:02.189  1178  1178 D KeyguardViewMediator: handleNotifyScreenOn
08-26 15:23:02.189  1178  1178 D StatusBarKeyguardViewManager: onScreenTurnedOn()
,08-26 15:23:02.189  1178  1178 D SecKeyguardClockSingleView: onScreenTurnedOn
08-26 15:23:02.189  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 15:23:02.199  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 15:23:02.199  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
08-26 15:23:02.199  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-26 15:23:02.199  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 15:23:02.199  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
08-26 15:23:02.199  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:23:02.199  1018  1018 D BatteryService: turn off LED
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:02.199  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.system,ui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:02.199  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.199  1018  3337 V KeyguardServiceDelegate: **** SHOWN CALLED ****
08-26 15:23:02.199  1178  1178 D StatusBarKeyguardViewManager: callback.onShown()
08-26 15:23:02.199  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-26 15:23:02.199  1018  1046 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1050 I DisplayPowerController: Unblocked screen on after 151 ms
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1050 D DisplayPowerState: !@ ColorFade exit
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1092 E SmartFaceService: onReceive: android.intent.action.SCREEN_ON
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1078 E lights  : write_led_info failed to open -1
08-26 15:23:02.199  1018  1092 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
08-26 15:23:02.199  1018  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-26 15:23:02.199  1018  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:23:02.199  1018  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:23:02.199  1018  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
08-26 15:23:02.199  1018  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
08-26 15:23:02.199  1018  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
08-26 15:23:02.199  1018  1092 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-26 15:23:02.199  1018  1092 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:23:02.199  1018  1092 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:23:02.199  1018  1092 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:23:02.209  1018  1092 E SmartFaceService: fail to set sysfs 1
08-26 15:23:02.199  1018  1092 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:23:02.209  1018  1092 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
08-26 15:23:02.209  1018  1092 W System.err: 	at libcore.io.Posix.open(Native Method)
08-26 15:23:02.209  1018  1092 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:23:02.209  1018  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:23:02.209  1018  1092 W System.err: 	... 10 more
08-26 15:23:02.209  1468  1620 D NfcService: index : 0
08-26 15:23:02.209  1468  1620 D NfcService: index : 1
08-26 15:23:02.209   258  1976 I SurfaceFlinger: id=11 Removed DolorFade (8/8)
08-26 15:23:02.209   258  1098 I SurfaceFlinger: id=11 Removed DolorFade (-2/8)
08-26 15:23:02.219  1018  1050 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-26 15:23:02.219  1018  1050 D PowerManagerService: Excessive delay in ColorFade : dismiss: 14ms
08-26 15:23:02.219  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
08-26 15:23:02.219  1018  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
08-26 15:23:02.219  1018  1161 D lights  : lcd : 255 +
08-26 15:23:02.219  1018  1161 D lights  : lcd : 255 -
08-26 15:23:02.219  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
08-26 15:23:02.219  1018  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
08-26 15:23:02.219  1018  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-26 15:23:02.219  1018  1050 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
08-26 15:23:02.219  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.219  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
08-26 15:23:02.219  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
08-26 15:23:02.229  1178  1178 D BatteryMeterView: onDraw batteryColor : -1
08-26 15:23:02.229  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:23:02.229  1724  1724 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
08-26 15:23:02.239  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 15:23:02.239  1018  1018 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
08-26 15:23:02.239  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
08-26 15:23:02.239  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.239  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.239  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
08-26 15:23:02.239  1018  1458 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 15:23:02.249  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 15:23:02.249  1018  1458 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.249  1018  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:02.249  1018  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:23:02.249  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 15:23:02.249  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
08-26 15:23:02.259  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
08-26 15:23:02.259  1018  1104 E MotionRecognitionService:  handler : SCREEN_ON end
08-26 15:23:02.259  1018  1018 D NotificationService: ACTION_SCREEN_ON
08-26 15:23:02.259  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
08-26 15:23:02.269  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
08-26 15:23:02.269  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-26 15:23:02.269  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
08-26 15:23:02.269  1178  1178 I StatusBar: Icon Only
08-26 15:23:02.269  1178  1178 D PanelView: There is/are notification(s) 
08-26 15:23:02.269  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
08-26 15:23:02.269  1018  1040 D SensorService: [SO] currT = 1493161075991, prevT = 76620104865, diff = 1416540971126, [-0.153 0.172 9.960]
08-26 15:23:02.269  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
08-26 15:23:02.269  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
08-26 15:23:02.269  1018  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 15:23:02.269  1018  1127 E WifiNative-wlan0: do suspend false
,08-26 15:23:02.269  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.269  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:02.279  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:23:02.279   258   526 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-26 15:23:02.279   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-26 15:23:02.279  1018  1055 D SurfaceControl: Excessive delay in setPowerMode(): 230ms
08-26 15:23:02.279  1018  1055 D PowerManagerService: Excessive delay in !@display_state: ON: 230ms
08-26 15:23:02.279   258   526 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
08-26 15:23:02.279   258   526 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,08-26 15:23:02.289  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.289  1018  3340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.289  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.sm
08-26 15:23:02.289  1018  7659 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 1
,08-26 15:23:02.289  1018  7658 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,08-26 15:23:02.299  1347  1347 I wpa_supplicant: reset timer : RESET_TIMER 1
08-26 15:23:02.299  1347  1347 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 15:23:02.299  1347  1347 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 15:23:02.299  1347  1347 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 15:23:02.299  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:02.299  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:02.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:02.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:02.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:02.299   287   287 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-26 15:23:02.299   287   287 V voice   : voice_set_parameters: enter: screen_state=on
08-26 15:23:02.299   287   287 V voice   : voice_set_parameters: exit with code(-2)
08-26 15:23:02.299   287   287 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-26 15:23:02.299   287   287 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:23:02.299   287   287 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:23:02.299   287   287 V audio_hw_primary: adev_set_parameters: exit
,08-26 15:23:02.319  1018  1048 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,08-26 15:23:02.319  1018  1048 D IpRemoteDisplayController: Bridge Server is not available
,08-26 15:23:02.319  1018  1018 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,08-26 15:23:02.329  1018  1018 V SAMP_GCMKill: GCM kill size 0. just return
,08-26 15:23:02.329  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.329  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.329  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-26 15:23:02.329  1018  3340 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-26 15:23:02.339  1018  3340 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-26 15:23:02.339  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.339  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.339  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-26 15:23:02.339  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.339  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.339  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-26 15:23:02.349  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.349  1018  3340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.349  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-26 15:23:02.349  6997  6997 D GalleryCacheReady: Receive : home resume
,08-26 15:23:02.349  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.349  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.349  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-26 15:23:02.349  7022  7022 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-26 15:23:02.359  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.359  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.359  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-26 15:23:02.359  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.359  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.359  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-26 15:23:02.369  6407  6407 D Mms/UIEventReceiver: ui event
,08-26 15:23:02.369  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:02.369  1018  1506 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1508, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-26 15:23:02.369  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.369  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-26 15:23:02.369  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.369  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.369  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-26 15:23:02.379  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.379  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.379  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-26 15:23:02.379  2636  2636 D Recents_RecreateReceiver: onReceive by home
,08-26 15:23:02.389  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:23:02.399  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:02.399  1018  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:02.399  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-26 15:23:02.399  1018  7659 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,08-26 15:23:02.409  1018  1030 I splitIntent: Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 15:23:02.419  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:23:02.439  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:23:02.449  1018  7658 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
08-26 15:23:02.449  1018  1055 D PowerManagerService: Excessive delay in nativeSetInteractive(true): 164ms
08-26 15:23:02.449  1018  1055 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
08-26 15:23:02.449  1018  1055 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 396ms
08-26 15:23:02.449  1018  1055 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
08-26 15:23:02.449  1018  1055 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 162ms
08-26 15:23:02.449  1018  1055 I QCOM PowerHAL: Got set_interactive hint
08-26 15:23:02.449  1018  1158 D lights  : button : 1 +
,08-26 15:23:02.469  1018  1040 D SensorService: [SO] currT = 1493360129845, prevT = 76620104865, diff = 1416740024980, [-0.153 0.153 9.922]
,08-26 15:23:02.469  1018  1040 D SensorService: [SO] -0.153 0.153 9.922
,08-26 15:23:02.469  1018  1040 D SensorService: [SO] [100 -> 255]
,08-26 15:23:02.479  1018  1158 D lights  : button : 1 -
,08-26 15:23:02.499  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 15:23:02.559  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:23:02.849   295   295 E SMD     : DCD OFF
,08-26 15:23:03.279  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:03.279  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:03.279  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:03.279  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:03.279  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:03.289  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:03.369  1347  1347 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
,08-26 15:23:03.369  1018  1126 D WifiP2pService: InactiveState{ what=147461 }
,08-26 15:23:03.369  1018  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-26 15:23:03.369  1018  1126 D WifiP2pService: DefaultState{ what=147461 }
,08-26 15:23:03.669  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-26 15:23:03.669  1018  1018 D PersonaManagerService: ACTION_SCREEN_ON onReceive
08-26 15:23:03.669  1018  1062 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,08-26 15:23:03.669  1018  1321 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,08-26 15:23:03.679  1468  1468 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,08-26 15:23:03.679  1468  2225 D NfcService: call the applyRouting
,08-26 15:23:03.679  1468  2225 D NfcService: Discovery configuration equal, not updating.
08-26 15:23:03.679  1468  2225 D NfcService: index : 0
08-26 15:23:03.679  1468  2225 D NfcService: index : 1
,08-26 15:23:03.679  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,08-26 15:23:03.679  1793  1793 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON,
08-26 15:23:03.679  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
08-26 15:23:03.679  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
08-26 15:23:03.679  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
08-26 15:23:03.689  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,08-26 15:23:03.689  1793  1793 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 23
,08-26 15:23:03.699  1018  1497 D ActivityManager: startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,08-26 15:23:03.699  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,08-26 15:23:03.699  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:03.699  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:23:03.699  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,08-26 15:23:03.709  1018  1018 E SAMP_GCMKill: got SCREEN_ON
,08-26 15:23:03.719  1018  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:23:03.719  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:23:03.719  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:03.719  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionNETWORK_SET_TIMEZONE
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,08-26 15:23:03.729  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,08-26 15:23:03.739  1980  1980 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,08-26 15:23:03.739  1793  1793 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 23
,08-26 15:23:03.739  1508  1841 W OpenGLRenderer: SFEffectCache::get: create texture(0xa033e724): name, size, mSize = 35, 83980, 297352
,08-26 15:23:03.759  1018  1157 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,08-26 15:23:03.769  1018  2884 D SSRM:n  : SIOP:: AP = 300
,08-26 15:23:03.779  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 15:23:03.779  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 15:23:03.789  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:23:03.789  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:23:03.789  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,08-26 15:23:03.799  2691  2691 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:23:03.799  2691  2691 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-26 15:23:03.799  2691  2691 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:23:03.799  2691  2691 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1472237880000
08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1472217783808
,08-26 15:23:03.799  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:23:03.809  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-26 15:23:03.809  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 15:23:03.809  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 15:23:03.809  2691  2691 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-26 15:23:03.809  2691  2691 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:23:03.819  2691  2691 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-26 15:23:03.859  1018  7665 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,08-26 15:23:03.869  1018  7665 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:23:03.889  1018  7665 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Screen bin #0: time=16 power=7.733333333333333E-5
,08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Screen bin #4: time=1113 power=0.0484155
08-26 15:23:03.919  1018  7665 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,08-26 15:23:03.949  1018  1158 D lights  : button : 0 +
,08-26 15:23:03.979  1018  1158 D lights  : button : 0 -
,08-26 15:23:04.059  1018  7665 I BatteryStatsDumper: Writing to database completed
,08-26 15:23:04.289  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:23:04.289  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:04.289  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:04.289  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:04.289  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:04.289  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:04.559  1018  2884 D SSRM:a  : DeviceInfo:: 000000000000
,08-26 15:23:04.559  1018  2884 D SSRM:a  : SettingsAirViewInfo:: 000000000
,08-26 15:23:05.299  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:23:05.309  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 15:23:05.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:23:05.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:05.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:05.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:05.849   295   295 E SMD     : DCD OFF
,08-26 15:23:08.299  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:23:08.299  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:08.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:08.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:23:08.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:08.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:08.859   295   295 E SMD     : DCD OFF,
,08-26 15:23:09.299  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:23:09.299  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:09.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:09.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:09.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:09.299  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:11.309  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:23:11.309  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:11.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:11.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:11.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:11.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:11.859   295   295 E SMD     : DCD OFF,
,08-26 15:23:12.019  1018  3340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:23:12.019  1018  3340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:23:12.019  1018  3340 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:23:12.019  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:23:12.029  1018  1018 I MotionRecognitionService: Plugged
,08-26 15:23:12.029  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:23:12.029  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:23:12.029  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:23:12.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:23:12.029  1437  1437 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:23:12.039  2812  2812 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:23:12.039  2812  3068 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:23:12.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:23:12.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:23:12.039  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:23:12.039  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:23:12.049  1178  1178 D SViewCoverView: level :100 plugged : 2,
,08-26 15:23:12.309  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:23:12.309  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:12.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:12.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:12.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:12.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:13.809  1018  2884 D SSRM:n  : SIOP:: AP = 300
,08-26 15:23:14.309  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:23:14.309  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:14.309  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:14.319  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:14.319  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:14.319  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:23:14.859   295   295 E SMD     : DCD OFF,
,TIME-OUT KILL (timeout was 1400000ms),08-26 15:23:17.859   295   295 E SMD     : DCD OFF
08-26 15:23:18.319  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:18.319  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:18.319  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:18.329  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:18.329  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:18.329  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:18.909  7670  7670 D AndroidRuntime: 
08-26 15:23:18.909  7670  7670 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:23:18.909  7670  7670 D AndroidRuntime: CheckJNI is OFF
08-26 15:23:18.909  7670  7670 D AndroidRuntime: readGMSProperty: start
08-26 15:23:18.909  7670  7670 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:23:18.909  7670  7670 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:23:18.909  7670  7670 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:23:18.909  7670  7670 D AndroidRuntime: readGMSProperty: end
08-26 15:23:18.909  7670  7670 D AndroidRuntime: addProductProperty: start
08-26 15:23:19.029  7670  7670 E AffinityControl: AffinityControl: registerfunction enter
08-26 15:23:19.059  7670  7670 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 15:23:19.069  1018  1458 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-26 15:23:19.069  1018  1458 D PackageManager: START PACKAGE DELETE: observer{95993404}
08-26 15:23:19.069  1018  1458 D PackageManager: pkg{<packageName>}
08-26 15:23:19.069  1018  1458 D PackageManager: user{0}
08-26 15:23:19.069  1018  1458 D PackageManager: caller{2000}
08-26 15:23:19.069  1018  1458 D PackageManager: flags{2}
08-26 15:23:19.069  1018  1458 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 15:23:19.069  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 15:23:19.069  1018  1458 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 15:23:19.069  1018  1458 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:23:19.069  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
08-26 15:23:19.069  1018  1458 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:23:19.069  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 15:23:19.079  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-26 15:23:19.069  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 15:23:19.069  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 15:23:19.069  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-26 15:23:19.209  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
08-26 15:23:19.229  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-26 15:23:19.259  6141  6141 I art     : Explicit concurrent mark sweep GC freed 1979(114KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 782us total 36.752ms
08-26 15:23:19.259  6278  6278 I art     : Explicit concurrent mark sweep GC freed 959(70KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 4MB/6MB, paused 2.602ms total 46.812ms
08-26 15:23:19.269  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 15:23:19.269  1724  1915 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 15:23:19.279  5838  5838 I art     : Explicit concurrent mark sweep GC freed 58(14KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 925us total 42.300ms
08-26 15:23:19.279  1980  1980 E SamsungIME: mOCRHelper is null
08-26 15:23:19.279  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 15:23:19.279  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 15:23:19.279  1018  1042 W TextServicesManagerService: no available spell checker services found
08-26 15:23:19.289  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.319  2941  2941 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:23:19 GMT+02:00 2016
08-26 15:23:19.329  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-26 15:23:19.329  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:19.329  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
08-26 15:23:19.329  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:23:19.329  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:23:19.339  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-26 15:23:19.339  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:19.339  1018  1544 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 15:23:19.339  1018  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-26 15:23:19.339  1018  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.339  1018  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:19.339  1018  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-26 15:23:19.349  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:19.349  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.349  1468  1468 D RegisteredServicesCache: empty dynamic service
08-26 15:23:19.359  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.359  2941  2941 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-26 15:23:19.369  1018  3337 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-26 15:23:19.369  1018  3337 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-26 15:23:19.389  2941  2941 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 15:23:19.389  2941  2941 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-26 15:23:19.389  6860  6860 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-26 15:23:19.389  1018  1424 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-26 15:23:19.389  1018  1424 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-26 15:23:19.389  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.399  1018  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:19.399  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-26 15:23:19.399  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:19.399  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:19.399  6860  6860 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-26 15:23:19.399  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-26 15:23:19.399  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.399  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.399  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.399  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.409  6860  6860 D elm:15121: ElmAgentService : onCreate()
08-26 15:23:19.409  2941  2941 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 15:23:19.409  6860  7684 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-26 15:23:19.409  6860  7684 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-26 15:23:19.409  6860  7684 D elm:15121: MDMBridge.getInstance()
08-26 15:23:19.409  6860  7684 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-26 15:23:19.419  7685  7685 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.419  7685  7685 E Zygote  : v2
08-26 15:23:19.419  7685  7685 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:23:19.419  7685  7685 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.419  6860  7684 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-26 15:23:19.419  7685  7685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.419  1018  1043 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7685 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:23:19.429  1018  1018 I art     : Explicit concurrent mark sweep GC freed 63622(4MB) AllocSpace objects, 33(720KB) LOS objects, 33% free, 23MB/35MB, paused 5.413ms total 205.806ms
08-26 15:23:19.429  7685  7685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.429  1018  1058 I art     : WaitForGcToComplete blocked for 108.806ms for cause Explicit
08-26 15:23:19.429  7685  7685 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 15:23:19.429  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 15:23:19.449  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-26 15:23:19.459  1018  1521 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 15:23:19.459  1018  1521 D SecContentProvider2: mCursor = null
08-26 15:23:19.459  7685  7685 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.459  7685  7685 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.459  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-26 15:23:19.469  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-26 15:23:19.469  1468  1468 D RegisteredComponentCache: Collect Tech packages for Knox
08-26 15:23:19.479  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-26 15:23:19.479  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.479  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.479  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.479  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.489  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-26 15:23:19.499  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7700 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-26 15:23:19.499  7700  7700 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.499  7700  7700 I libpersona: KNOX_SDCARD checking this for 10052
08-26 15:23:19.499  7700  7700 E Zygote  : v2
08-26 15:23:19.499  7700  7700 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.499  7700  7700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.499  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-26 15:23:19.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.519  7700  7700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.519  7700  7700 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:23:19.529  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.529  7707  7707 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.529  7707  7707 I libpersona: KNOX_SDCARD checking this for 10098
08-26 15:23:19.529  7707  7707 E Zygote  : v2
08-26 15:23:19.529  7707  7707 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.529  7707  7707 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.529  7707  7707 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.529  7707  7707 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:19.539  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7707 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 15:23:19.539  1018  1018 D RCPManagerService: PackageReceiver onReceive()
08-26 15:23:19.539  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-26 15:23:19.539  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:19.539  6860  6860 D elm:15121: ElmAgentService : onDestroy().
08-26 15:23:19.539  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 15:23:19.539  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 15:23:19.539  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
08-26 15:23:19.539  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.559  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
08-26 15:23:19.559  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-26 15:23:19.559  7700  7700 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.559  7700  7700 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.579  7707  7707 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.579  7707  7707 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.589  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-26 15:23:19.609  2941  7683 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-26 15:23:19.619  2941  7683 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-26 15:23:19.619  7685  7730 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-26 15:23:19.629  7685  7730 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-26 15:23:19.639  7685  7730 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:23:19.639  7685  7730 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:23:19.639  7685  7730 D SPPClientService: ============PushLog. stop!
08-26 15:23:19.639  2941  2941 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-26 15:23:19.639  1018  3337 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-26 15:23:19.639  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.649  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.649  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.649  1018  3337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.659  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:23:19.659  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:23:19.659  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-26 15:23:19.669  7732  7732 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.669  7732  7732 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:23:19.669  7732  7732 E Zygote  : v2
08-26 15:23:19.669  7732  7732 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.669  7732  7732 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 15:23:19.669  7732  7732 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:23:19.669  7732  7732 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 15:23:19.669  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:23:19.679  1018  3337 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7732 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:23:19.679  1018  3337 I ActivityManager: Killing 5838:com.android.vending/u0a26 (adj 15): empty #21
08-26 15:23:19.679  1018  1458 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-26 15:23:19.689  7732  7732 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.689  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.689  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.689  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.689  1018  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.689  7732  7732 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.699   322   322 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 23.010ms
08-26 15:23:19.709  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:23:19.709  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:23:19.709  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:23:19.709  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.719  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.719   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.807ms
08-26 15:23:19.719  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.719  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.719  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:23:19.729  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.729  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.729  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:23:19.739   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.702ms
08-26 15:23:19.739  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.739  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:23:19.739  1018  1058 I art     : Explicit concurrent mark sweep GC freed 14803(813KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 5.846ms total 313.708ms
08-26 15:23:19.739  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:23:19.749  7747  7747 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.749  7747  7747 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:19.749  7747  7747 E Zygote  : v2
08-26 15:23:19.749  7747  7747 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.749  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.749  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.749  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:19.749  1018  1458 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7747 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:19.759  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:23:19.759  1018  2884 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 15:23:19.759  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:23:19.779  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:23:19.779  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:23:19.779  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:19.779  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:19.779  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:19.779  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:23:19.779  1018  1030 I ActivityManager: Killing 6791:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-26 15:23:19.789  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.789  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-26 15:23:19.789  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-26 15:23:19.789  7747  7747 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.799  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-26 15:23:19.809  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-26 15:23:19.809  1018  1511 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-26 15:23:19.809  1018  1511 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-26 15:23:19.809  1018  1511 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.809  1018  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:19.809  1018  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-26 15:23:19.819  1018  3337 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-26 15:23:19.819  1018  3337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-26 15:23:19.829  1018  3337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.829  1018  3337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:19.829  1018  3337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-26 15:23:19.839  1018  3340 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-26 15:23:19.839  1689  1689 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-26 15:23:19.839  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.839  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.839  1689  1689 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-26 15:23:19.839  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.839  1018  3340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.849  7764  7764 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.849  7764  7764 E Zygote  : v2
08-26 15:23:19.849  7764  7764 I libpersona: KNOX_SDCARD checking this for 10055
08-26 15:23:19.849  7764  7764 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.859  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.859  1018  1058 D PackageManager: delete codoeFile: 
08-26 15:23:19.859  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.859  1018  3340 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7764 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 15:23:19.869  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
08-26 15:23:19.869  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-26 15:23:19.869  1018  1058 D PackageManager: result of delete: 1{95993404}
08-26 15:23:19.869  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:19.879  1018  1544 I ActivityManager: Killing 6810:com.osp.app.signin/u0a36 (adj 15): empty #21
08-26 15:23:19.879  1018  3340 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 15:23:19.879  1018  3340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-26 15:23:19.899  7670  7670 D AndroidRuntime: Shutting down VM
08-26 15:23:19.909  7732  7768 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-26 15:23:19.909  7732  7768 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-26 15:23:19.909  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.909  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:19.909  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-26 15:23:19.909  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
08-26 15:23:19.919  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.919  1857  7781 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 15:23:19.919  7764  7764 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.919  1857  7781 D AccountUtils: Clearing selected account for com.test.thalitest
08-26 15:23:19.919  7732  7768 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:23:19.919  7732  7768 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:23:19.919  7732  7768 D SPPClientService: ============PushLog. stop!
08-26 15:23:19.919  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.919  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.919  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.919  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.929  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 15:23:19.929  1018  1058 D PackageManager: userId{-1}
08-26 15:23:19.929  1018  1058 D PackageManager: andCode{true}
08-26 15:23:19.939  7783  7783 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.939  7783  7783 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:19.939  7783  7783 E Zygote  : v2
08-26 15:23:19.939  7783  7783 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.939  7783  7783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.939  7783  7783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.939  1018  1137 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:19.939  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-26 15:23:19.939  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-26 15:23:19.949  7783  7783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:19.949  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:19.949  1018  1030 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-26 15:23:19.949  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:19.949  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
08-26 15:23:19.949  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
08-26 15:23:19.959  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 15:23:19.969  7783  7783 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:19.969  7783  7783 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:19.979  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.979  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.979  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.979  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:19.989  7764  7764 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-26 15:23:19.989  7800  7800 E Zygote  : MountEmulatedStorage()
08-26 15:23:19.999  7800  7800 E Zygote  : v2
08-26 15:23:19.999  7800  7800 I libpersona: KNOX_SDCARD checking this for 10003
08-26 15:23:19.999  7800  7800 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:19.999  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:19.999  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:19.999  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:19.999  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7800 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 15:23:19.999  1018  3340 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 15:23:20.009  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:20.009  1018  3340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:20.009  1018  3340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:23:20.019  1018  1424 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:23:20.019  1018  1424 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
08-26 15:23:20.019  1018  1424 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:20.019  1018  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:23:20.019  1018  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:23:20.029  1857  7781 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-26 15:23:20.029  7764  7764 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-26 15:23:20.029  7764  7764 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 15:23:20.029  7764  7764 D UserAnalysis: Create SecureDbHelper
08-26 15:23:20.039  1018  3340 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 15:23:20.039  1018  3340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
08-26 15:23:20.039  1018  3340 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:20.039  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable

```
