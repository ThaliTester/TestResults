#### Test 80598852b8a90be_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-16 18:14:57.617  6502  6707 D Mms/Conversation: [start]    init() consume time = 58.826979
08-16 18:14:57.617  6502  6502 D Mms/MmsApp: [end]    onCreate() consume time = 3.287239
08-16 18:14:57.627  1479  2137 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-16 18:14:57.627  1479  2137 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-16 18:14:57.627  1479  2137 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-16 18:14:57.627  1479  2137 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-16 18:14:57.627  6502  6502 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-16 18:14:57.627  6502  6502 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-16 18:14:57.637  1479  2137 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-16 18:14:57.637  1479  2137 D TP/MmsSmsProvider: need read changed broadcast:false
08-16 18:14:57.637  6502  6601 D Mms/ArtClassLoader: init [DONE] art
08-16 18:14:57.637  6502  6707 D Mms/Conversation: [end]    init consume time = 14.2625
08-16 18:14:57.637  3785  6569 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3785, getuid(): 10011
08-16 18:14:57.637  6502  6502 D Mms/MethodReflector: getSubId is called
08-16 18:14:57.637  6502  6502 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-16 18:14:57.637  6502  6502 D Mms/MethodReflector: getTelephonyProperty is called
08-16 18:14:57.637  6502  6502 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-16 18:14:57.637  6502  6502 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-16 18:14:57.637  6502  6502 D Mms/DownloadManager: auto download without roaming -> true
08-16 18:14:57.637  6502  6502 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-16 18:14:57.637  6502  6502 D Mms/DownloadManager: mAutoDownload ------> true
08-16 18:14:57.637  6502  6707 D Mms/MessagingNotification: [start]    init() consume time = 3.026719
08-16 18:14:57.637  6502  6707 D Mms/MessagingNotification: [end]    init consume time = 2.12375
08-16 18:14:57.637  6502  6502 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-16 18:14:57.647  1479  1764 D TP/MmsSmsProvider: query,matched:0, calling pid = 6502
08-16 18:14:57.647  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:14:57.647  1479  1764 V TP/MmsSmsProvider: getSimpleConversations entered.
08-16 18:14:57.647  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:14:57.647  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-16 18:14:57.647  1479  1764 D TP/MmsSmsProvider: match 0:Elapsed time : 1.181 ms
--------- beginning of system
08-16 18:14:57.647  1017  1029 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-16 18:14:57.647  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-16 18:14:57.647  1017  4215 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-16 18:14:57.647  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.647  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.647  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.647  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.657  6502  6710 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 12.672813
08-16 18:14:57.657  6502  6711 D Mms/Synchronizer: [start]    doSync consume time = 1.699895
08-16 18:14:57.667  6712  6712 E Zygote  : MountEmulatedStorage()
08-16 18:14:57.667  6712  6712 E Zygote  : v2
08-16 18:14:57.667  6712  6712 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:57.667  6712  6712 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:57.667  6712  6712 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-16 18:14:57.667  6712  6712 I libpersona: KNOX_SDCARD checking this for 10042
08-16 18:14:57.667  6712  6712 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:57.667  1017  4215 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6712 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-16 18:14:57.677  1479  1492 D TP/MmsSmsProvider: update, matched:300, calling pid = 6502
08-16 18:14:57.677  1479  1492 V TP/MmsSmsProvider: syncDBData start
08-16 18:14:57.677  1479  1492 V TP/MmsSmsProvider: syncDBData sms end
08-16 18:14:57.677  1479  1764 D TP/MmsSmsProvider: query,matched:400, calling pid = 6502
08-16 18:14:57.677  1479  1492 V TP/MmsSmsProvider: syncDBData mms end
08-16 18:14:57.677  1479  1492 V TP/MmsSmsProvider: syncDBData end
08-16 18:14:57.677  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-16 18:14:57.687  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.687  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.687  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.687  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.697  6729  6729 E Zygote  : MountEmulatedStorage()
08-16 18:14:57.697  6729  6729 E Zygote  : v2
08-16 18:14:57.697  6729  6729 I libpersona: KNOX_SDCARD checking this for 10068
08-16 18:14:57.697  6729  6729 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:57.697  6729  6729 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:57.697  6729  6729 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:57.707  6712  6712 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:57.707  1017  1029 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6729 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-16 18:14:57.707  6729  6729 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 18:14:57.707  6712  6712 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:57.707  6502  6711 D Mms/Synchronizer: [end]    doSync consume time = 49.409792
,08-16 18:14:57.717  6502  6710 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 8.168906
08-16 18:14:57.717  6502  6731 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-16 18:14:57.717  6502  6731 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-16 18:14:57.717  1017  1485 I ActivityManager: Killing 6270:com.android.calendar/u0a131 (adj 15): empty #21
08-16 18:14:57.727  6712  6712 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:14:57.727  6712  6712 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 18:14:57.727  6712  6712 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 18:14:57.727  6729  6729 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:57.727  6729  6729 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:57.737  1017  4214 I ActivityManager: Killing 6380:com.android.defcontainer/u0a3 (adj 15): empty #21
08-16 18:14:57.757  6729  6729 D BadgeProvider: onCreate
08-16 18:14:57.767  6729  6729 D BadgeProvider: DatabaseHelper
08-16 18:14:57.777  6502  6707 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-16 18:14:57.787  1479  1764 D TP/SmsProvider: query,matched:26, calling pid = 6502
08-16 18:14:57.787  1479  1764 D TP/SmsProvider: match 26:Elapsed time : 1.497 ms
08-16 18:14:57.797  1479  1490 D TP/MmsSmsProvider: query,matched:6, calling pid = 6502
08-16 18:14:57.797  1479  1490 D TP/MmsSmsProvider: match 6:Elapsed time : 1.641 ms
08-16 18:14:57.817  1017  4215 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-16 18:14:57.827  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.827  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.827  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.827  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.837  1017  4215 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6747 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-16 18:14:57.837  6747  6747 E Zygote  : MountEmulatedStorage()
08-16 18:14:57.837  6747  6747 E Zygote  : v2
08-16 18:14:57.837  6747  6747 I libpersona: KNOX_SDCARD checking this for 10023
08-16 18:14:57.837  6747  6747 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:57.837  6747  6747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:57.847  6747  6747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:57.847  6747  6747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:14:57.867  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:57.867  6747  6747 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:57.877  1017  1321 I ActivityManager: Killing 6146:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-16 18:14:57.887  6712  6712 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-16 18:14:57.887  1017  1478 I ActivityManager: Killing 6422:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-16 18:14:57.897  1017  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-16 18:14:57.897  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-16 18:14:57.897  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.897  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.897  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.897  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:57.907  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6762 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 18:14:57.917  6762  6762 E Zygote  : MountEmulatedStorage()
08-16 18:14:57.917  6762  6762 I libpersona: KNOX_SDCARD checking this for 10003
08-16 18:14:57.917  6762  6762 E Zygote  : v2
08-16 18:14:57.917  6762  6762 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:57.917  6762  6762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:57.917  6762  6762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:57.917  6762  6762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:14:57.957  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:57.957  6762  6762 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:57.987  6745  6745 D AndroidRuntime: 
08-16 18:14:57.987  6745  6745 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 18:14:57.987  6745  6745 D AndroidRuntime: CheckJNI is OFF
08-16 18:14:57.987  6745  6745 D AndroidRuntime: readGMSProperty: start
08-16 18:14:57.987  6745  6745 D AndroidRuntime: readGMSProperty: already setted!!
08-16 18:14:57.987  6745  6745 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 18:14:57.987  6745  6745 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 18:14:57.987  6745  6745 D AndroidRuntime: readGMSProperty: end
08-16 18:14:57.987  6745  6745 D AndroidRuntime: addProductProperty: start
08-16 18:14:58.087  3785  6569 I qtaguid : Untagging socket 97
08-16 18:14:58.107  3785  3785 I ConfigFetchService: fetch service done; releasing wakelock
08-16 18:14:58.137  1017  4214 I art     : Explicit concurrent mark sweep GC freed 130626(7MB) AllocSpace objects, 2(1624KB) LOS objects, 33% free, 23MB/34MB, paused 2.595ms total 179.033ms
08-16 18:14:58.137  6745  6745 E AffinityControl: AffinityControl: registerfunction enter
08-16 18:14:58.147  3785  3785 I ConfigFetchService: stopping self
08-16 18:14:58.157  1017  1506 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 18:14:58.167  6745  6745 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 18:14:58.177  1017  1135 E PersonaManagerService: inState():  stateMachine is null !!
08-16 18:14:58.177  1017  1135 I PersonaManagerService: PersonaId don't exist
08-16 18:14:58.177  1017  1135 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 18:14:58.177  6747  6747 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-16 18:14:58.187   283   283 E installd: system dir 0 : /system/app/
08-16 18:14:58.187   283   283 E installd: system dir 1 : /system/priv-app/
08-16 18:14:58.187   283   283 E installd: system dir 2 : /vendor/app/
08-16 18:14:58.187   283   283 E installd: system dir 3 : /oem/app/
08-16 18:14:58.187  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 18:14:58.197  6502  6707 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-16 18:14:58.197  1017  1135 W ActivityManager: mDVFSHelper.acquire()
08-16 18:14:58.197  1017  1135 D FocusedStackFrame: Set to : 0
08-16 18:14:58.207  1017  1050 I PowerManagerService: [PWL] Off : 30s ago
08-16 18:14:58.207  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 18:14:58.207  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 18:14:58.207  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=3785, ws=null) (elapsedTime=49971)
08-16 18:14:58.207  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=3785, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1398)
08-16 18:14:58.207  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.207  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.207  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.207  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.207  1017  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-16 18:14:58.217  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 18:14:58.217  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 18:14:58.227  1017  1135 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6788 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 18:14:58.227  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-16 18:14:58.227  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-16 18:14:58.227  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 18:14:58.227  1017  1135 D InputDispatcher: Focused application set to: xxxx
08-16 18:14:58.227  1017  1135 D InputDispatcher: Focus left window: 1507
08-16 18:14:58.227  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-16 18:14:58.227  6788  6788 E Zygote  : MountEmulatedStorage()
08-16 18:14:58.227  6788  6788 E Zygote  : v2
08-16 18:14:58.227  6788  6788 I libpersona: KNOX_SDCARD checking this for 10170
08-16 18:14:58.227  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-16 18:14:58.227  6788  6788 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:58.237  6745  6745 D AndroidRuntime: Shutting down VM
08-16 18:14:58.237  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 18:14:58.237  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 18:14:58.237  6788  6788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:58.237  1017  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 18:14:58.237  6788  6788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:58.237  6788  6788 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 18:14:58.237   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-16 18:14:58.247  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-16 18:14:58.247  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-16 18:14:58.247  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-16 18:14:58.267  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-16 18:14:58.267  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-16 18:14:58.267  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-16 18:14:58.267  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:58.267  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-16 18:14:58.267  6788  6788 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:58.267  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-16 18:14:58.277  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:14:58.277  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 18:14:58.277  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-16 18:14:58.277  6747  6747 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-16 18:14:58.277  1017  4211 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-16 18:14:58.287  1017  1017 V ActivityManager: Display changed displayId=0
08-16 18:14:58.287  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 18:14:58.317  1017  4211 D PersonaManager: isKioskContainerExistOnDevice
08-16 18:14:58.327   257  6315 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-16 18:14:58.327   257  6315 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-16 18:14:58.337  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-16 18:14:58.337  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{14b476ef token=android.os.BinderProxy@14fb56b9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-16 18:14:58.347  1507  1507 D Launcher: onTrimMemory. Level: 20
08-16 18:14:58.347  3785  6588 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 131.376ms
08-16 18:14:58.357  1017  3327 D SSRM:n  : SIOP:: AP = 400
08-16 18:14:58.367  3785  4216 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-16 18:14:58.417  6552  6679 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-16 18:14:58.417  6552  6679 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 18:14:58.417  6552  6679 I GAv4    :   adb logcat -s GAv4
08-16 18:14:58.447  6745  6745 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 18:14:58.467  6788  6788 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-16 18:14:58.477  6552  6679 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-16 18:14:58.477  1017  1749 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 18:14:58.477  3785  4216 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-16 18:14:58.527  6788  6788 I cr.library_loader: Time to load native libraries: 27 ms (timestamps 3048-3075)
08-16 18:14:58.527  6788  6788 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 18:14:58.547  6788  6788 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8c3d741}
08-16 18:14:58.557  6552  6679 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-16 18:14:58.557  6788  6788 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 18:14:58.557  6788  6788 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 18:14:58.587  6552  6679 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-16 18:14:58.587  1017  1096 V AlarmManager: waitForAlarm result :4
08-16 18:14:58.597  3785  4216 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-16 18:14:58.617  6788  6788 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-16 18:14:58.617  6788  6788 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:14:58.617  6552  6812 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-16 18:14:58.627  6788  6788 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 18:14:58.637  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-16 18:14:58.647  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:14:58.647  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:14:58.647  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 18:14:58.657  6788  6788 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:14:58.657  6788  6788 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:14:58.657  6788  6788 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:14:58.657  6788  6788 I Adreno-EGL: Local Branch: 
08-16 18:14:58.657  6788  6788 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:14:58.657  6788  6788 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:14:58.657  6788  6788 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 18:14:58.767  6788  6788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 18:14:58.777  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-16 18:14:58.787  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.787  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.787  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.787  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.797  6833  6833 E Zygote  : MountEmulatedStorage()
08-16 18:14:58.797  6833  6833 E Zygote  : v2
08-16 18:14:58.797  6833  6833 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:14:58.797  6833  6833 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:58.797  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:14:58.797  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 18:14:58.797  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:14:58.807  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 18:14:58.807  1017  1485 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:14:58.807  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:14:58.807  1017  1485 I ActivityManager: Killing 5008:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-16 18:14:58.807  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 18:14:58.807  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 18:14:58.827  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{3e2d6f41 u0 com.test.thalitest/.MainActivity t163}
08-16 18:14:58.857  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:58.857  6833  6833 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:58.867  6552  6830 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 18:14:58.867  6552  6830 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 18:14:58.897  6552  6830 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-16 18:14:58.897  6833  6833 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-16 18:14:58.897  6833  6833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-16 18:14:58.897  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-16 18:14:58.897  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-16 18:14:58.907  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:14:58.907  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:14:58.907  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-16 18:14:58.917  1017  1505 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-16 18:14:58.927  6833  6833 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-16 18:14:58.937  6523  6567 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-16 18:14:58.937  6552  6565 W art     : Suspending all threads took: 5.031ms
08-16 18:14:58.947  6833  6850 E FilterInstaller: installFilters
08-16 18:14:58.947  6833  6850 E FilterInstaller: There is no requred permission
08-16 18:14:58.947  6523  6567 I AcmsKeyStoreHelper: Key Store exist
08-16 18:14:58.947  6523  6567 I AcmsKeyStoreHelper: Hence loading the keystore file
08-16 18:14:58.947  1017  4215 I ActivityManager: Killing 6451:com.sec.spp.push/u0a32 (adj 15): empty #21
08-16 18:14:58.957  6552  6830 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 18:14:58.957  6552  6830 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30fc44bf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-16 18:14:58.957  6552  6830 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 18:14:58.987  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-16 18:14:58.987  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-16 18:14:58.987  6788  6788 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:14:58.987  1017  1393 D NtpTrustedTime: forceRefresh() from cache miss
08-16 18:14:58.987   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 18:14:58.987   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-16 18:14:58.997  1017  1017 I BackgroundCompactionService: onStart. jobID=801
08-16 18:14:58.997  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
08-16 18:14:58.997  1017  6854 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-16 18:14:58.997  1017  6854 I BackgroundCompactionService: compact_memory command done
08-16 18:14:59.017  6523  6567 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-16 18:14:59.017  6523  6567 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-16 18:14:59.017  6523  6567 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-16 18:14:59.017  6523  6567 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 18:14:59.017  6523  6567 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-16 18:14:59.017  6523  6567 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-16 18:14:59.017  6523  6567 D AcmsCore: This is NOT a valid MirrorLink app
08-16 18:14:59.017  6523  6567 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-16 18:14:59.017  6523  6567 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 18:14:59.017  6523  6567 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-16 18:14:59.017  6523  6567 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-16 18:14:59.017  6523  6523 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-16 18:14:59.017  6523  6523 D AcmsService: Enter onDestroy
08-16 18:14:59.017  6523  6523 I AcmsService: cleanUp(): inside service clean up
08-16 18:14:59.017  6523  6523 D AcmsCore: AcmsCore: inside DeInit
08-16 18:14:59.017  6523  6523 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-16 18:14:59.017  6523  6523 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-16 18:14:59.017  6523  6523 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-16 18:14:59.017  6523  6523 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-16 18:14:59.017  6523  6523 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-16 18:14:59.017  6523  6523 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-16 18:14:59.017  6523  6523 D AcmsService: killing acms process
08-16 18:14:59.017  6523  6523 I Process : Sending signal. PID: 6523 SIG: 9
08-16 18:14:59.037  6788  6788 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 18:14:59.057  6788  6788 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 18:14:59.057  6788  6788 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-16 18:14:59.067  6788  6788 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-16 18:14:59.077  6788  6788 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:14:59.077  6788  6788 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 18:14:59.117  6788  6857 D OpenGLRenderer: Render dirty regions requested: true
08-16 18:14:59.117  1017  4213 I ActivityManager: Process ACMS.Process (pid 6523)(adj 0) has died(45,766)
08-16 18:14:59.127  1017  1516 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 18:14:59.127  1017  1516 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 18:14:59.127  1017  1516 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 18:14:59.127  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 18:14:59.127  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 18:14:59.137  6788  6824 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-16 18:14:59.137  6788  6788 V ActivityThread: updateVisibility : ActivityRecord{2b22f088 token=android.os.BinderProxy@c2ea47a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 18:14:59.137  6788  6788 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 18:14:59.137  6788  6788 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 18:14:59.157   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-16 18:14:59.167  1017  1485 D InputDispatcher: Focus entered window: 6788,
08-16 18:14:59.167  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:14:59.167  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 18:14:59.167  6788  6788 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 18:14:59.167  6788  6857 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 18:14:59.177  6788  6857 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-16 18:14:59.177  6788  6857 D OpenGLRenderer: Enabling debug mode 0
,08-16 18:14:59.197  1017  1749 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 18:14:59.197  1174  1174 D PanelView: There is/are notification(s) 
,08-16 18:14:59.207  1017  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:14:59.217  1017  1048 I ActivityManager: Displayed Component not be shown by security: +889ms (total +1s8ms)
,08-16 18:14:59.217  1017  1048 W ActivityManager: mDVFSHelper.release()
,08-16 18:14:59.217  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e2d6f41 u0 com.test.thalitest/.MainActivity t163} time:93764
,08-16 18:14:59.217  6788  6788 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 18:14:59.217  6788  6788 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c2ea47a time:93769
,08-16 18:14:59.227   257   434 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-16 18:14:59.227   257  1039 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-16 18:14:59.227  1017  4214 I ActivityManager: Killing 6437:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-16 18:14:59.277  1854  1854 I SamsungIME: getCurrentCandidateView
,08-16 18:14:59.367  6788  6788 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6788
,08-16 18:14:59.397  1854  1854 D SamsungIME: Dismiss ExpandCandiate
,08-16 18:14:59.547  6788  6788 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 18:14:59.557  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 18:14:59.597  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 18:14:59.607  1854  1854 I SamsungIME: KeybaordView init() : load resources
,08-16 18:14:59.627  6502  6502 I Mms/MmsApp:  start initViewCache mms
,08-16 18:14:59.627  6502  6502 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1910.892916
,08-16 18:14:59.627  6502  6502 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-16 18:14:59.627  1854  1854 I SamsungIME: getCurrentKeyboard
08-16 18:14:59.627  1854  1854 I SamsungIME: getTextKeyboard
,08-16 18:14:59.637  6788  6865 D jxcore_app_log: JniHelper::setJavaVM(0xb794e2b0), pthread_self() = -1209162232
,08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 18:14:59.647  6788  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f5e00ff added. We now have 1 listener(s)
,08-16 18:14:59.647  1854  1854 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 18:14:59.657  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-16 18:14:59.657  6788  6865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:14:59.657  6788  6865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:14:59.657  6788  6865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 18:14:59.667  6788  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b9202a added. We now have 1 listener(s)
,08-16 18:14:59.667  6788  6865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:14:59.667  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:14:59.667  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 18:14:59.667  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 18:14:59.667  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 18:14:59.667  6788  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 18:14:59.677  6788  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:14:59.677  6788  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-16 18:14:59.687  6788  6865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:14:59.687  6788  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:14:59.687  6788  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 18:14:59.687  6788  6865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:14:59.687  6788  6865 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:14:59.687  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:14:59.687  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:14:59.727  6788  6788 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,08-16 18:14:59.777  6502  6502 D AbsListView: Get MotionRecognitionManager
,08-16 18:14:59.777  1017  1504 D MotionRecognitionService:  ssp status : false
,08-16 18:14:59.787  6502  6502 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 159.654636
,08-16 18:14:59.867  6502  6502 D Mms/BubbleViewCache: fillCache bubble = 1
,08-16 18:14:59.987  1017  1096 V AlarmManager: waitForAlarm result :8
,08-16 18:15:00.207  6788  6873 W jxcore-log: Initializing JXcore engine
08-16 18:15:00.207  6788  6873 W jxcore-log: JXcore engine is ready
,08-16 18:15:00.267  1954  1954 E audit   : type=1400 msg=audit(1471364100.267:205): avc:  denied  { ioctl } for  pid=6873 comm="Thread-1271" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 18:15:00.267  1954  1954 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:00.267  1954  1954 E audit   : type=1300 msg=audit(1471364100.267:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9de168f8 items=0 ppid=304 ppcomm=main pid=6873 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1271" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 18:15:00.267  1954  1954 E audit   : type=1320 msg=audit(1471364100.267:205): 
,08-16 18:15:00.297  6788  6873 W jxcore-log: Starting JXcore engine
,08-16 18:15:00.407  6788  6873 W jxcore-log: Platform android
08-16 18:15:00.407  6788  6873 W jxcore-log: 
08-16 18:15:00.407  6788  6873 W jxcore-log: Process ARCH arm
08-16 18:15:00.407  6788  6873 W jxcore-log: 
,08-16 18:15:00.497   287   287 E SMD     : DCD OFF
,08-16 18:15:00.597  6788  6873 I jxcore-log: JXcore Cordova bridge is ready!
08-16 18:15:00.597  6788  6873 I jxcore-log: 
,08-16 18:15:00.597  6788  6873 W jxcore-log: JXcore engine is started
,08-16 18:15:00.607  6788  6865 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 18:15:00.607  6788  6788 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 18:15:00.857  1017  1393 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1471364100468 mCachedNtpElapsedRealtime : 95406 mCachedNtpCertainty : 20,
08-16 18:15:00.857  1017  1393 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:00.857  1017  1393 D AlarmManagerService: Setting time of day to sec=1471364100
08-16 18:15:00.857  1017  1393 D AlarmManagerService: Trying to open a file
,08-16 18:15:00.468  1017  1096 V AlarmManager: waitForAlarm result :65536,
08-16 18:15:00.877  1017  1393 D AlarmManagerService: File Open Success
08-16 18:15:00.468  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=95427 batch.start=107324
08-16 18:15:00.877  1017  1393 D AlarmManagerService: File Close Success
08-16 18:15:00.877  1017  1393 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-16 18:15:00.468  1017  1393 W AlarmManagerService: Unable to set rtc to 1471364100: Invalid argument
,08-16 18:15:00.468  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1471364100479
,08-16 18:15:00.468  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-16 18:15:00.468  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 18:15:00.477  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-16 18:15:00.477  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 18:15:00.477  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 18:15:00.487  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,08-16 18:15:00.487  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 18:15:00.487  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-16 18:15:00.487  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-16 18:15:00.487  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:00.507  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:00.507  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:00.507  1017  1017 I DrmEventService:  no response from SecureClock 
,08-16 18:15:00.507  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:00.507  1017  1017 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-16 18:15:00.507  1017  1017 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-16 18:15:00.507  1017  1017 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-16 18:15:00.507  1017  1017 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-16 18:15:00.507  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:00.517  1017  4214 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-16 18:15:00.517  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-16 18:15:00.517  1017  4214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:00.517  1017  4214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:00.517  1017  4214 D SettingsProvider: selectionArgs: false
08-16 18:15:00.517  1017  4214 D SettingsProvider: selectionArgs: 10049
08-16 18:15:00.517  1017  4214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:00.517  1017  4214 D SettingsProvider: ret = -1
,08-16 18:15:00.517  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.517  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.517  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.517  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.517  1017  4214 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049,
08-16 18:15:00.517  1174  1174 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,08-16 18:15:00.527  1174  1174 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-16 18:15:00.527  1174  1174 I GeometricMosaic_Keyguard: update
,08-16 18:15:00.527  1174  1174 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-16 18:15:00.527  6876  6876 E Zygote  : MountEmulatedStorage()
08-16 18:15:00.527  6876  6876 I libpersona: KNOX_SDCARD checking this for 10008,
08-16 18:15:00.527  6876  6876 E Zygote  : v2
08-16 18:15:00.527  6876  6876 I libpersona: KNOX_SDCARD not a persona,
,08-16 18:15:00.537  6876  6876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:00.537  6876  6876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:00.537  6876  6876 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 18:15:00.537  1017  1017 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6876 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:00.577  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:00.577  6876  6876 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:00.607  1174  1174 I KeyguardEffectViewUtil: set current wallpaper info
,08-16 18:15:00.607  1017  1478 D SettingsProvider: name = keyguard_current_wallpaper_type
,08-16 18:15:00.607  1017  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:00.607  1017  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:00.607  1017  1478 D SettingsProvider: selectionArgs: false
,08-16 18:15:00.607  1017  1478 D SettingsProvider: selectionArgs: 10049
08-16 18:15:00.607  1017  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 18:15:00.607  1017  1478 D SettingsProvider: ret = -1
,08-16 18:15:00.607  1017  1135 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,08-16 18:15:00.607  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:00.607  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 18:15:00.607  1017  1135 D SettingsProvider: selectionArgs: false
08-16 18:15:00.607  1017  1135 D SettingsProvider: selectionArgs: 10049
08-16 18:15:00.607  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:00.607  1017  1135 D SettingsProvider: ret = -1
,08-16 18:15:00.607  1017  1029 D SettingsProvider: name = keyguard_current_wallpaper_res_id
,08-16 18:15:00.607  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:00.617  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:00.617  1017  1029 D SettingsProvider: selectionArgs: false
08-16 18:15:00.617  1017  1029 D SettingsProvider: selectionArgs: 10049
08-16 18:15:00.617  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:00.617  1017  1029 D SettingsProvider: ret = -1
,08-16 18:15:00.637  6876  6876 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-16 18:15:00.657  6876  6876 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-16 18:15:00.677  1017  4213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:00.677  1017  4213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-16 18:15:00.677  1017  4213 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:00.677  1017  4213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:00.677  1017  4213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:00.687  1174  1607 D TEST    : run!!!
,08-16 18:15:00.697  1174  1607 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-16 18:15:00.707  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 18:15:00.707  1174  1174 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-16 18:15:00.727  1017  1135 I ActivityManager: Killing 5981:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-16 18:15:00.737  1017  4214 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:00.737  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-16 18:15:00.737  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:00.737  1017  4214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:00.737  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:00.757  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Aug 16 18:15:00 GMT+02:00 2016
,08-16 18:15:00.757  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 18:15:00.757  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:00.757  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:00.757  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:00.757  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:00.767  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 18:15:00.767  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-16 18:15:00.777  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:00.777  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:00.777  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:00.777  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.787  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 18:15:00.787  2802  2802 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:00.787  6894  6894 E Zygote  : MountEmulatedStorage()
08-16 18:15:00.787  6894  6894 I libpersona: KNOX_SDCARD checking this for 10036
08-16 18:15:00.787  6894  6894 E Zygote  : v2
08-16 18:15:00.787  6894  6894 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:00.787  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:00.787  1017  1135 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6894 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:00.787  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:00.787  2802  2802 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:00.787  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-16 18:15:00.797  2802  6893 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-16 18:15:00.797  2802  6893 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-16 18:15:00.797  2802  6893 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Aug 16 18:15:00 GMT+02:00 2016
,08-16 18:15:00.817  2802  6893 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-16 18:15:00.817  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 18:15:00.827  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:00.827  6894  6894 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:00.877  6894  6894 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@21a33009
,08-16 18:15:00.887  6894  6894 I SA      : [SSP] onCreated
,08-16 18:15:00.907  6894  6894 I SA      : [TPM] There is no property file
,08-16 18:15:00.907  6894  6894 I SA      : [SCU] isHaveSA() - false
,08-16 18:15:00.907  6894  6894 I SA      : [TPM] getModelProperty : null
08-16 18:15:00.907  6894  6894 I SA      : [TPM] getCSCProperty : null
,08-16 18:15:00.907  6894  6894 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-16 18:15:00.907  6894  6894 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-16 18:15:00.907  6894  6894 I SA      : [DM] TFT FEATURE: false
,08-16 18:15:00.917  1017  4214 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:00.917  1017  4214 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 18:15:00.917  1017  4214 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 18:15:00.917  1017  4214 D BatteryService: stay LED for charging
08-16 18:15:00.917  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:00.927  1017  1017 I MotionRecognitionService: Plugged
,08-16 18:15:00.927  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:00.927  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 18:15:00.927  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:00.927  1438  1438 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 18:15:00.927  1438  1438 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 18:15:00.937  6894  6894 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-16 18:15:00.937  6894  6894 I SA      : [DM] init START
,08-16 18:15:00.937  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 18:15:00.937  3181  3305 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:00.937  6894  6894 I SA      : [DM] This device is not a Vodafone
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 18:15:00.947  6894  6894 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-16 18:15:00.947  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-16 18:15:00.947  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-16 18:15:00.957  6894  6894 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:15:00.957  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:00.957  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-16 18:15:00.957  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 18:15:00.957  6894  6894 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-16 18:15:00.967  6894  6894 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75),
,08-16 18:15:00.967  6894  6894 I SA      : [SCU] isHaveSA() - false
08-16 18:15:00.967  6894  6894 I SA      : support phone number id : false
08-16 18:15:00.967  6894  6894 I SA      : [DM] Supports Ref Jpn : true
,08-16 18:15:00.967  6894  6894 I SA      : [DM] init END
,08-16 18:15:00.997  1017  1749 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-16 18:15:00.997  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.997  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:00.997  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:00.997  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.017  6913  6913 E Zygote  : MountEmulatedStorage()
08-16 18:15:01.017  6913  6913 E Zygote  : v2
08-16 18:15:01.017  6913  6913 I libpersona: KNOX_SDCARD checking this for 10058
08-16 18:15:01.017  6913  6913 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.017  1017  1749 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6913 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 18:15:01.017  1017  1749 I ActivityManager: Killing 6470:com.samsung.helphub/1000 (adj 15): empty #21
,08-16 18:15:01.017  6913  6913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:01.027  6913  6913 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:01.027  6913  6913 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:01.047  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.047  6913  6913 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.097  6913  6913 I ExternalOEMControlProvider: onCreate
,08-16 18:15:01.107  1017  1478 I ActivityManager: Killing 5487:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-16 18:15:01.117  1822  1822 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-16 18:15:01.117  1822  1822 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 18:15:01.117  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-16 18:15:01.127  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.127  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.127  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.127  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.127  6913  6929 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-16 18:15:01.137  6930  6930 E Zygote  : MountEmulatedStorage()
,08-16 18:15:01.137  6930  6930 E Zygote  : v2
,08-16 18:15:01.137  6930  6930 I libpersona: KNOX_SDCARD checking this for 10081
,08-16 18:15:01.137  6930  6930 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.137  1017  1516 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6930 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:01.147  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 18:15:01.147  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:01.147  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:01.167   304   304 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 22.868ms
,08-16 18:15:01.167  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.167  6930  6930 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.177   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 16.584ms
,08-16 18:15:01.187  6930  6930 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 18:15:01.187  6930  6930 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 18:15:01.187  6930  6930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:01.187  6930  6930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:01.187  6930  6930 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-16 18:15:01.197   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.416ms
,08-16 18:15:01.237  1017  1749 D SettingsProvider: name = next_alarm_formatted
,08-16 18:15:01.237  1017  1749 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:01.237  1017  1749 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:01.237  1017  1749 D SettingsProvider: selectionArgs: false
08-16 18:15:01.237  1017  1749 D SettingsProvider: selectionArgs: 10081
08-16 18:15:01.237  1017  1749 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:01.237  1017  1749 D SettingsProvider: ret = -1
,08-16 18:15:01.357  6930  6930 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 117.328ms
,08-16 18:15:01.457  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 18:15:01.457  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.457  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.457  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.457  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.477  6945  6945 E Zygote  : MountEmulatedStorage(),
,08-16 18:15:01.477  6945  6945 E Zygote  : v2
08-16 18:15:01.477  6945  6945 I libpersona: KNOX_SDCARD checking this for 10090
08-16 18:15:01.477  6945  6945 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:01.477  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:01.477  1017  1029 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6945 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-16 18:15:01.477  1017  1029 I ActivityManager: Killing 6492:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
08-16 18:15:01.487  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:01.487  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:01.507  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.507  6945  6945 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.537  6945  6945 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-16 18:15:01.537  6945  6945 D elm:15121: ELMEngine.ELMEngine( context ).
,08-16 18:15:01.537  6945  6945 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-16 18:15:01.547  1017  4215 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 18:15:01.547  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-16 18:15:01.547  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:01.547  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:01.547  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 18:15:01.547  6945  6945 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-16 18:15:01.547  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-16 18:15:01.547  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.547  6945  6945 D elm:15121: ElmAgentService : onCreate()
08-16 18:15:01.547  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.547  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.547  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.547  6945  6961 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-16 18:15:01.557  6945  6961 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-16 18:15:01.557  6945  6945 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-16 18:15:01.557  6945  6945 D elm:15121: ModuleBase.ModifySetAlarm()
08-16 18:15:01.557  6945  6945 D elm:15121: MDMBridge.getInstance()
08-16 18:15:01.557  6945  6945 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 18:15:01.567  6963  6963 E Zygote  : MountEmulatedStorage()
08-16 18:15:01.567  6963  6963 I libpersona: KNOX_SDCARD checking this for 10130
08-16 18:15:01.567  6963  6963 E Zygote  : v2
08-16 18:15:01.567  6963  6963 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.567  6963  6963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:01.567  1017  1478 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6963 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-16 18:15:01.567  6963  6963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:01.567  6945  6945 D elm:15121: ElmAgentService : onDestroy().,
08-16 18:15:01.567  1017  1506 I ActivityManager: Killing 6552:com.google.android.apps.docs/u0a87 (adj 15): empty #21
08-16 18:15:01.567  6963  6963 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-16 18:15:01.587  6963  6963 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.587  6963  6963 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.597  6963  6963 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:01.607  6963  6963 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-16 18:15:01.617  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-16 18:15:01.617  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.617  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.617  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.627  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.637  6978  6978 E Zygote  : MountEmulatedStorage()
08-16 18:15:01.637  6978  6978 E Zygote  : v2
08-16 18:15:01.637  6978  6978 I libpersona: KNOX_SDCARD checking this for 10131
08-16 18:15:01.637  6978  6978 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.637  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:01.637  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:01.647  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 18:15:01.647  1017  1029 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6978 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
08-16 18:15:01.647  1017  1029 I ActivityManager: Killing 6082:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-16 18:15:01.657  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.667  6978  6978 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.677  6978  6978 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 18:15:01.677  6978  6978 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:01.677  6978  6978 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:01.707  2664  5177 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-16 18:15:01.717  1017  1135 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-16 18:15:01.717  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-16 18:15:01.717  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:01.717  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:01.717  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:01.727  1017  4214 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-16 18:15:01.737  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-16 18:15:01.737  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:01.737  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:01.737  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:01.737  1017  4213 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-16 18:15:01.737  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.737  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.737  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.737  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.747  1017  4213 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6998 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:01.747  6998  6998 E Zygote  : MountEmulatedStorage()
08-16 18:15:01.747  6998  6998 E Zygote  : v2
08-16 18:15:01.757  6998  6998 I libpersona: KNOX_SDCARD checking this for 10037
08-16 18:15:01.757  6998  6998 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.757  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-16 18:15:01.757  6998  6998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:01.757  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 18:15:01.757  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.757  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.757  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.757  6998  6998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:01.757  6998  6998 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-16 18:15:01.777  7010  7010 E Zygote  : MountEmulatedStorage(),
,08-16 18:15:01.777  7010  7010 E Zygote  : v2
08-16 18:15:01.777  7010  7010 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:01.777  7010  7010 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:01.777  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 18:15:01.777  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:01.777  1017  1135 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7010 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 18:15:01.777  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:01.787  6998  6998 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:01.787  6998  6998 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.797  6998  6998 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-16 18:15:01.797  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.807  7010  7010 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.827  6998  6998 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-16 18:15:01.837  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:01.837  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:01.837  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:01.857  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-16 18:15:01.857  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.857  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.857  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.857  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.867  7031  7031 E Zygote  : MountEmulatedStorage()
,08-16 18:15:01.867  7031  7031 E Zygote  : v2
,08-16 18:15:01.867  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:01.867  7031  7031 I libpersona: KNOX_SDCARD checking this for 10153
08-16 18:15:01.867  7031  7031 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:01.867  1017  1485 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7031 uid=10153 gids={50153, 9997} abi=armeabi-v7a,
08-16 18:15:01.867  1017  1485 I ActivityManager: Killing 6572:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-16 18:15:01.877  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:01.877  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:01.897  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.897  7031  7031 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.917  7031  7031 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:01.927  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-16 18:15:01.927  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.927  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.927  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:01.927  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:01.947  7049  7049 E Zygote  : MountEmulatedStorage(),
08-16 18:15:01.947  7049  7049 E Zygote  : v2
08-16 18:15:01.947  7049  7049 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:01.947  7049  7049 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:01.947  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:01.947  1017  1504 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:01.947  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:01.947  1017  1504 I ActivityManager: Killing 6595:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-16 18:15:01.947  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:01.957  1017  1478 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-16 18:15:01.957  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-16 18:15:01.957  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:01.957  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:01.957  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-16 18:15:01.967  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:01.967  7049  7049 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:01.997  7049  7049 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471364102010
08-16 18:15:01.997  7049  7049 D         : TimeServiceNative: User Time to be set is 1471364102010
08-16 18:15:01.997  7049  7049 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-16 18:15:01.997  7049  7049 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-16 18:15:01.997  7049  7049 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471364102010
,08-16 18:15:01.997   316   559 D QC-time-services: Daemon: Connection accepted:time_genoff
08-16 18:15:01.997  7049  7049 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-16 18:15:01.997   316  7065 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471364102010
08-16 18:15:01.997   316  7065 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471364102010, operation = 0
08-16 18:15:01.997   316  7065 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/11/71 9:57:59
08-16 18:15:02.007   316  7065 D QC-time-services: Daemon:Value read from RTC seconds = 35114279000,
08-16 18:15:02.007   316  7065 D QC-time-services: Daemon:new time 1471364102010 
08-16 18:15:02.007   316  7065 D QC-time-services: Daemon: delta 1436249823010 genoff 1436249823010 
08-16 18:15:02.007   316  7065 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249823010 to memory
,08-16 18:15:02.007   316  7065 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-16 18:15:02.007   316  7065 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-16 18:15:02.017   316  7065 D QC-time-services: Updating the TOD offset
08-16 18:15:02.017   316  7065 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249823010 to memory
08-16 18:15:02.017   316  7065 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-16 18:15:02.017   316  7065 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation ,
,08-16 18:15:02.017   316  7065 E QC-time-services: Daemon:Update to modem bit set
08-16 18:15:02.017   316  7065 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-16 18:15:02.017  7049  7049 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-16 18:15:02.017   316  7065 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285023010
,08-16 18:15:02.017   316   556 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-16 18:15:02.017   316   559 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-16 18:15:02.027  1017  4214 I ActivityManager: Killing 6614:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-16 18:15:02.027  1017  1478 I ActivityManager: Killing 6630:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-16 18:15:02.037  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-16 18:15:02.037  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-16 18:15:02.037  2664  2664 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-16 18:15:02.037  2664  2664 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-16 18:15:02.037  2664  2664 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-16 18:15:02.047  2664  2664 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-16 18:15:02.047  2664  2664 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-16 18:15:02.047  2664  2664 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-16 18:15:02.047  2664  2664 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-16 18:15:02.047  2664  2664 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-16 18:15:02.047  2664  2664 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-16 18:15:02.047  2664  2664 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-16 18:15:02.047  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-16 18:15:02.057  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-16 18:15:02.057  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-16 18:15:02.057  2664  2664 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-16 18:15:02.057  2664  2664 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-16 18:15:02.067  2664  2664 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-16 18:15:02.067  2664  2664 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-16 18:15:02.067  2664  2664 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-16 18:15:02.317   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a1d7c8
08-16 18:15:02.317   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-16 18:15:02.317   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 18:15:02.317   270   354 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197352824)
,08-16 18:15:02.357   270   354 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-16 18:15:02.357   270   354 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 18:15:02.357   270   354 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197352824) wakelock released: 1, error no: 0,
08-16 18:15:02.357   270   354 I rmt_storage: 
,08-16 18:15:02.357   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8a1d7c8
,08-16 18:15:02.727  1685  1685 I ConfigService: onDestroy
,08-16 18:15:02.817  1017  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:02.967  6998  6998 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-16 18:15:02.967  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:02.967  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:02.967  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-16 18:15:02.977  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-16 18:15:02.977  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:02.977  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:02.977  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-16 18:15:02.977  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:02.977  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:02.977  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:02.987  1017  4215 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-16 18:15:02.987  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-16 18:15:02.987  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:02.987  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:02.987  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:02.997  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:02.997  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:02.997  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:02.997  1017  1321 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-16 18:15:02.997  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-16 18:15:02.997  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:02.997  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:02.997  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 18:15:03.007  1017  1478 I ActivityManager: Killing 6665:com.sec.pcw.device/1000 (adj 15): empty #21
,08-16 18:15:03.077   287   287 E SMD     : DCD OFF
,08-16 18:15:06.077   287   287 E SMD     : DCD OFF
,08-16 18:15:07.817  1017  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:07.827  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-16 18:15:07.837  1017  1057 D PackageManager: [MSG] MCS_UNBIND
,08-16 18:15:07.847  1017  1506 I ActivityManager: Killing 6032:com.android.vending/u0a26 (adj 15): empty #21
,08-16 18:15:07.967  1017  3327 D SSRM:n  : SIOP:: AP = 390
,08-16 18:15:09.077   287   287 E SMD     : DCD OFF
,08-16 18:15:10.967  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:10.967  1017  1135 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-16 18:15:10.967  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 18:15:10.967  1017  1135 D BatteryService: stay LED for charging
08-16 18:15:10.967  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:10.967  1017  1017 I MotionRecognitionService: Plugged,
08-16 18:15:10.967  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 18:15:10.967  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:10.967  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:10.977  1438  1438 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 18:15:10.977  1438  1438 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 18:15:10.987  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 18:15:10.987  3181  3305 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:10.997  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-16 18:15:10.997  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-16 18:15:11.007  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 18:15:11.007  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:11.007  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:12.077   287   287 E SMD     : DCD OFF,
,08-16 18:15:12.357  1017  1096 V AlarmManager: waitForAlarm result :4
,08-16 18:15:12.357  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,08-16 18:15:12.357  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:12.357  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:12.357  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:12.357  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:12.367  7072  7072 E Zygote  : MountEmulatedStorage()
,08-16 18:15:12.377  7072  7072 E Zygote  : v2
08-16 18:15:12.377  7072  7072 I libpersona: KNOX_SDCARD checking this for 10026
08-16 18:15:12.377  7072  7072 I libpersona: KNOX_SDCARD not a persona,
,08-16 18:15:12.377  7072  7072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:12.377  7072  7072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:12.377  1017  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7072 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:12.377  7072  7072 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-16 18:15:12.377  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-16 18:15:12.387  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-16 18:15:12.387  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-16 18:15:12.387  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-16 18:15:12.387  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 18:15:12.397  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 18:15:12.397  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 18:15:12.407  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:12.407  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-16 18:15:12.407  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-16 18:15:12.407  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-16 18:15:12.427  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:12.427  7072  7072 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:12.437  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:12.437  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,08-16 18:15:12.447  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:12.457  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 18:15:12.507  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.517  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.557  7072  7072 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 18:15:12.557  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.647  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.647  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.657  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.657  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.657  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.657  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.667  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.677  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.677  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.677  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.677  7072  7072 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 18:15:12.687  7072  7072 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 18:15:12.697  7072  7072 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 18:15:12.717  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.717  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:12.717  7072  7072 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 18:15:12.877  1017  1030 I art     : Explicit concurrent mark sweep GC freed 27191(1599KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 22MB/34MB, paused 2.482ms total 148.745ms
,08-16 18:15:12.897  7072  7072 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 18:15:12.897  7072  7109 D Ads     : Skipping gmscore version check
,08-16 18:15:12.897  1017  4214 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-16 18:15:12.897  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-16 18:15:12.907  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.907  1017  4214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.907  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-16 18:15:12.917  1017  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.917  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:12.917  1017  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.917  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.927  7072  7072 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 18:15:12.937  7072  7072 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 18:15:13.037  7072  7106 D Finsky  : [1329] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-16 18:15:13.047  7072  7072 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-16 18:15:13.047  1017  1029 I ActivityManager: Killing 6684:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-16 18:15:13.457  1017  1323 E Watchdog: !@Sync 3,
,08-16 18:15:13.557  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-16 18:15:13.557  6788  6873 I jxcore-log: 
,08-16 18:15:13.557  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-16 18:15:13.557  6788  6873 I jxcore-log: 
,08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:13.557  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:13.567  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:13.567  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 18:15:13.567  6788  6873 I jxcore-log: 
,08-16 18:15:13.567  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 18:15:13.567  6788  6873 I jxcore-log: 
,08-16 18:15:14.007  6788  6873 D ExecuteNativeTests: Running unit tests
,08-16 18:15:14.097  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:14.097  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed added. We now have 2 listener(s)
,08-16 18:15:14.097  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 18:15:14.097  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:14.097  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:14.097  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.097  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 added. We now have 2 listener(s)
08-16 18:15:14.097  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.097  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:14.107  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.107  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.107  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.107  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:14.107  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.107  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 18:15:14.107  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.107  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 18:15:14.117  6788  6873 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 18:15:14.117  6788  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.117  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.117  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.117  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.117  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.117  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.117  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:14.117  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed removed from the list
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.117  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 removed from the list
,08-16 18:15:14.117  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.117  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.117  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.117  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.117  6788  6873 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 18:15:14.117  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.117  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.117  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.117  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.117  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.117  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.117  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.117  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:15:14.117  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.117  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.127  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 18:15:14.127  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.127  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.127  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.127  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.127  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.127  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.127  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.127  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.127  6788  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:14.127  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.137  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.137  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.137  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-16 18:15:14.137  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.137  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:14.137  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.137  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.137  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:14.137  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.137  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.137  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:14.147  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:14.147  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:14.157  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 18:15:14.157  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 18:15:14.157  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 18:15:14.157  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:14.157  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:14.167  3181  3196 D BtGatt.GattService: registerClient() - UUID=704ec574-b199-454b-b8ee-358eb9f4d6dd
,08-16 18:15:14.177   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 18:15:14.177   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-16 18:15:14.207  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=704ec574-b199-454b-b8ee-358eb9f4d6dd, clientIf=6
,08-16 18:15:14.207  6788  6804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:14.207  3181  3256 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.217  3181  3304 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:14.217  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:15:14.217  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:14.217  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.217  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:14.217  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.217  3181  3304 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:14.227  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:14.227  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.227  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.237  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.237  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.237  3181  3304 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:14.237  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:14.237  3181  3304 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 18:15:14.237  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.237  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.237  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:14.237  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.247  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:14.247  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.247  6788  6873 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:15:14.247  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:14.247  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.257  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.257  6788  6873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 18:15:14.257  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.257  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 18:15:14.257  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.257  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:14.257  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 18:15:14.257  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.257  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.257  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:15:14.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:15:14.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.267  3181  3333 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:14.267  3181  3304 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:14.267  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 18:15:14.267  3181  3196 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.267  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:14.267  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.267  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:14.267  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:14.267  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:14.277  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 18:15:14.277  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.277  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:14.277  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 18:15:14.277  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.277  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.277  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.277  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.277  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.277  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.277  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.277  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.287  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.287  6788  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:14.287  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:14.287  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 18:15:14.287  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.287  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.287  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.297  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:14.297  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:14.297  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.297  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.297  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:14.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:14.297  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:14.297  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:14.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:14.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:14.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 18:15:14.307  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:14.317  3181  3196 D BtGatt.GattService: registerClient() - UUID=ba110991-5096-4ee4-b616-59a136a48adb
,08-16 18:15:14.357  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=ba110991-5096-4ee4-b616-59a136a48adb, clientIf=6
,08-16 18:15:14.357  6788  6804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:14.357  3181  3256 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.357  3181  3304 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:14.357  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:15:14.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 18:15:14.357  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:14.357  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.357  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.357  3181  3304 D BtGatt.ScanManager: allow scan with filters
,08-16 18:15:14.357  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:14.357  3181  3304 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 18:15:14.367  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.367  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.367  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:14.367  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.367  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.367  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.367  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:14.367  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:14.367  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.377  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.377  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:14.377  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.377  6788  6873 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:15:14.377  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.387  6788  6873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:15:14.387  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.387  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:14.387  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.387  3181  3333 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:14.387  3181  3304 D BtGatt.ScanManager: filter size is 1
08-16 18:15:14.387  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 18:15:14.387  3181  3196 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:14.387  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.387  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:14.387  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:14.387  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.387  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.397  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 18:15:14.397  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.397  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:15:14.397  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.397  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.397  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.397  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.397  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:14.397  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.397  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 18:15:14.397  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.397  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.397  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.397  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list,
08-16 18:15:14.397  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:14.397  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.397  6788  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 18:15:14.407  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.407  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.407  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:14.407  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:14.407  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.407  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 18:15:14.407  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.407  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.407  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:14.417  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.417  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:14.417  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.417  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:14.417  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:14.417  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:14.417  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 18:15:14.427  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:14.427  3181  3256 D BtGatt.GattService: registerClient() - UUID=5bc99f05-b21a-47d5-bc10-728fccd424ba
,08-16 18:15:14.467  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=5bc99f05-b21a-47d5-bc10-728fccd424ba, clientIf=6
,08-16 18:15:14.467  6788  6804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:14.467  3181  3333 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.467  3181  3304 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:14.467  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:14.467  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:14.467  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.467  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:14.477  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.477  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.477  3181  3304 D BtGatt.ScanManager: allow scan with filters
,08-16 18:15:14.477  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:14.477  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:14.477  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:14.477  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.477  3181  3304 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 18:15:14.477  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.487  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.487  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.487  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:14.487  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.487  6788  6873 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:15:14.487  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.487  6788  6873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:15:14.487  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.487  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:14.487  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.487  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:14.487  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.487  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.487  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.487  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:14.487  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:14.487  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.487  3181  3256 D BtGatt.GattService: stopScan() - queue size =1
08-16 18:15:14.487  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 18:15:14.487  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.487  3181  3333 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.497  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.497  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:14.497  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:14.497  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:14.497  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:14.497  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.507  3181  3304 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:14.507  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 18:15:14.507  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.507  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:14.507  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.507  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.507  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:14.507  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:14.507  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.507  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.517  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:14.517  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.517  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:14.517  6788  6873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 18:15:14.517  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.517  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:14.517  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.517  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.517  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.517  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.517  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.517  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.517  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.517  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.517  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.517  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.517  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.517  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.517  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.517  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.517  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.517  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.517  6788  6873 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 18:15:14.517  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.527  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.527  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.527  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.527  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 18:15:14.527  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.527  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.527  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.527  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.527  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.527  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.527  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.527  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.537  6788  6873 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 18:15:14.537  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.537  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.537  6788  6873 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 18:15:14.537  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.537  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:14.537  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.537  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:14.537  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.537  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.537  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.537  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.537  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.547  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.547  6788  6873 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 18:15:14.547  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 18:15:14.547  6788  6873 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:14.547  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:15:14.547  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-16 18:15:14.547  6788  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:14.547  6788  6873 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 18:15:14.547  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-16 18:15:14.547  6788  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 18:15:14.547  6788  6873 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 18:15:14.547  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.547  6788  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:14.547  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 18:15:14.547  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 18:15:14.547  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 18:15:14.547  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-16 18:15:14.557  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 18:15:14.557  6788  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.557  6788  6873 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 18:15:14.557  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.557  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.557  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 18:15:14.557  6788  7115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1335)
08-16 18:15:14.557  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
,08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.557  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.557  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6788  7116 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1335
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.557  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.557  6788  6873 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-16 18:15:14.557  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.557  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.557  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.557  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.557  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.557  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
,08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 18:15:14.567  6788  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.567  6788  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6788  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:14.567  6788  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
08-16 18:15:14.567  6788  7115 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  7115 D BluetoothSocket: connect(): myUserId = 0
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  7115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.567  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.567  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:, removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.567  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.577  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.577  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.577  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.577  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.577  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.577  3181  3256 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:14.577  6788  7115 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-16 18:15:14.577  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.577  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.577  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.577  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.577  6788  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 18:15:14.577  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.577  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 18:15:14.577  6788  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 18:15:14.577  6788  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 18:15:14.587  6788  6788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 18:15:14.587  6788  6788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  7117 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 18:15:14.587  6788  7117 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.587  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.587  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.587  6788  6788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 18:15:14.587  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.587  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.587  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.587  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.587  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.587  6788  6873 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 18:15:14.587  6788  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.587  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.587  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.587  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.587  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.587  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.597  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.597  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.597  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.597  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2cd7ed not in the list
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.597  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d305622 not in the list
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.597  6788  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:15:14.597  6788  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:15:14.597  6788  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 18:15:14.597  6788  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 18:15:14.607  6788  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 18:15:14.607  6788  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 18:15:14.607  6788  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 18:15:14.607  6788  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 18:15:14.607  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.607  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a6f5834 added. We now have 2 listener(s)
08-16 18:15:14.607  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:14.607  6788  6873 D BluetoothAdapter: enable()
,08-16 18:15:14.607  6788  6873 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 18:15:14.607  1017  1505 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 18:15:14.607  1017  1505 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 18:15:14.607  1017  1505 D SecContentProvider2: mCursor = null
08-16 18:15:14.607  1017  1505 D WifiService: setWifiEnabled: true pid=6788, uid=10170
08-16 18:15:14.607  1017  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:14.617  1017  1505 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:14.617  1017  1505 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:14.617  1017  1505 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 18:15:14.617  1017  1505 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:14.617  1017  1505 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:14.617  1017  1505 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:14.617  1017  1505 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 18:15:14.617  1017  1505 D SettingsProvider: name = wifi_on
08-16 18:15:14.617  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.617  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a80965d added. We now have 3 listener(s)
08-16 18:15:14.617  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:14.617  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.617  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f7e8bd2 added. We now have 4 listener(s)
08-16 18:15:14.617  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:14.627  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.627  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de7b4a3 added. We now have 5 listener(s)
08-16 18:15:14.627  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:14.627  1017  1516 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 18:15:14.627  1017  1516 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 18:15:14.627  1017  1516 D SecContentProvider2: mCursor = null
08-16 18:15:14.627  1017  1516 D WifiService: setWifiEnabled: false pid=6788, uid=10170
08-16 18:15:14.627  1017  1516 D SettingsProvider: name = wifi_on
08-16 18:15:14.627  1017  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 18:15:14.637  6788  6873 D BluetoothAdapter: disable()
08-16 18:15:14.637  1379  1379 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 18:15:14.637  1379  1379 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 18:15:14.637  1017  1506 D SettingsProvider: name = bluetooth_on
08-16 18:15:14.637  1379  1379 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 18:15:14.637  1379  1379 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 18:15:14.637  3181  3252 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 18:15:14.637  3181  3252 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:14.637  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:15:14.647  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.637  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:14.647  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 18:15:14.637  3181  3252 D BluetoothAdapterService: updateAdapterState state is 13
08-16 18:15:14.647  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.647  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.647  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.647  3181  3181 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 18:15:14.647  1379  1379 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-16 18:15:14.647  1379  1379 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-16 18:15:14.647  1379  1379 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-16 18:15:14.647  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:14.647  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c0152e8, channel: 19, state: LISTENING
08-16 18:15:14.647  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c0152e8, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@395419d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b432d01mSocket: android.net.LocalSocket@3316a7a6 impl:android.net.LocalSocketImpl@381e25e7 fd:FileDescriptor[80]
08-16 18:15:14.647  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3316a7a6 impl:android.net.LocalSocketImpl@381e25e7 fd:FileDescriptor[80]
,08-16 18:15:14.647  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:14.647  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 18:15:14.647  3181  3252 D BluetoothAdapterService: terminating service from this receiver,
08-16 18:15:14.647  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.657  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.657  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:14.657  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.657  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:14.657  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.657  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:14.657  3181  3252 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:15:14.657  3181  3252 D BluetoothAdapterProperties: mDiscovering is false
,08-16 18:15:14.657  1017  1135 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:14.657  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.657  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.657  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:14.657  4621  4621 D BluetoothPbap: Proxy object disconnected
,08-16 18:15:14.657  4621  4621 D PbapServerProfile: Bluetooth service disconnected
,08-16 18:15:14.657  3181  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 18:15:14.667  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:14.667  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-16 18:15:14.667  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.667  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:14.667  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.667  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:14.677  1854  1854 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:14.677  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:14.677  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:14.677  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-16 18:15:14.677  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:14.677  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:14.687  1017  1516 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:14.687  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:14.687  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:14.687  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:14.687  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:14.687  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 18:15:14.697  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.697  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.697  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:14.697  3181  3255 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:14.697  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.697  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.697  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 18:15:14.697  3181  3252 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-16 18:15:14.697  3181  3252 E bt-btif : cmd socket is not created,
08-16 18:15:14.697  6788  7115 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fb53b59, channel: -1, state: INIT
08-16 18:15:14.697  6788  7115 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fb53b59, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1815931e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b36f7ffmSocket: android.net.LocalSocket@43179cc impl:android.net.LocalSocketImpl@1bf53415 fd:FileDescriptor[106]
08-16 18:15:14.697  6788  7115 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@43179cc impl:android.net.LocalSocketImpl@1bf53415 fd:FileDescriptor[106]
08-16 18:15:14.697  6788  7115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1335)
08-16 18:15:14.697  3181  3257 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-16 18:15:14.697  3181  5267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:14.697  3181  3252 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:15:14.707  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@534983d, channel: 5, state: LISTENING
,08-16 18:15:14.707  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@534983d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f8c8dc9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39f59832mSocket: android.net.LocalSocket@2a9d3983 impl:android.net.LocalSocketImpl@ac99700 fd:FileDescriptor[82]
08-16 18:15:14.707  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a9d3983 impl:android.net.LocalSocketImpl@ac99700 fd:FileDescriptor[82]
08-16 18:15:14.707  3181  3181 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:14.707  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@dd77b39, channel: 12, state: LISTENING
08-16 18:15:14.707  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@dd77b39, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29c0540b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1361057emSocket: android.net.LocalSocket@d6feadf impl:android.net.LocalSocketImpl@19b1232c fd:FileDescriptor[86]
08-16 18:15:14.707  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d6feadf impl:android.net.LocalSocketImpl@19b1232c fd:FileDescriptor[86]
08-16 18:15:14.707  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.707  3181  5267 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 18:15:14.707  3181  3181 V BluetoothOppManager: cleanUp...
,08-16 18:15:14.707  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.707  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:14.707  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:14.707  3181  3257 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-16 18:15:14.707  3181  3257 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-16 18:15:14.707  3181  3257 W bt-btif : invalid rfc slot id: 4
08-16 18:15:14.707  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:14.707  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.707  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.707  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:14.717  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:14.717  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:14.717  3181  3257 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:15:14.727  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:14.727  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:14.727  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:14.727  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13,
,08-16 18:15:14.727  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 18:15:14.737  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-16 18:15:14.737  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 18:15:14.737  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.737  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.737  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.737  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.757  7122  7122 E Zygote  : MountEmulatedStorage()
,08-16 18:15:14.757  7122  7122 I libpersona: KNOX_SDCARD checking this for 10055
08-16 18:15:14.757  7122  7122 E Zygote  : v2
08-16 18:15:14.757  7122  7122 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:14.757  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:14.767  1017  1135 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7122 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-16 18:15:14.757  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:14.757  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:14.767   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:14.767  1685  2647 V NativeCrypto: Read error: ssl=0xb7ebb7f8: I/O error during system call, Connection timed out
,08-16 18:15:14.777  1685  2647 V NativeCrypto: SSL shutdown failed: ssl=0xb7ebb7f8: I/O error during system call, Broken pipe
08-16 18:15:14.777  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:14.777  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:14.777  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.777  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.777  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.777  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.777  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:14.777  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:14.777  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:14.777  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-16 18:15:14.777  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 18:15:14.777  1017  1030 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-16 18:15:14.777  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:14.777  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:14.777  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 18:15:14.777  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:14.777  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-16 18:15:14.777  1017  1762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 18:15:14.777  1017  1762 I qtaguid : Tagging socket 375 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-16 18:15:14.787  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-16 18:15:14.787  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 18:15:14.787  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1,
08-16 18:15:14.787  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:14.787  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 18:15:14.787  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:15:14.787  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:14.787  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:14.797  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
,08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:14.797  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:14.797  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:14.797  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.797  1017  1762 I qtaguid : Untagging socket 375
08-16 18:15:14.797  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.797  1017  1762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:14.797  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 18:15:14.797  1017  1126 D WifiP2pService: P2pDisablingState
08-16 18:15:14.807  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 18:15:14.807  1017  1126 D WifiP2pService: p2p socket connection lost
08-16 18:15:14.807  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:14.807  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 18:15:14.807  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 18:15:14.807  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:14.807  1017  1127 E WifiNative-wlan0: do suspend true
08-16 18:15:14.807  1017  1048 D WifiDisplayController: disconnect
08-16 18:15:14.807  1017  1048 D WifiDisplayController: updateConnection
08-16 18:15:14.807  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:14.807  1017  1126 D WifiP2pService: P2pDisabledState
08-16 18:15:14.807  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:14.807  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 18:15:14.807  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:14.807  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:14.807  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:14.807  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:14.807  7122  7122 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:14.817  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 18:15:14.817  1017  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:14.817  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:14.837  7122  7122 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,08-16 18:15:14.837  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 18:15:14.837  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-16 18:15:14.837  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:14.837  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:14.837  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:14.847  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.847  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.847  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.847  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.867   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-16 18:15:14.867   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 18:15:14.867   277  1016 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:14.867  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 18:15:14.867  1017  1129 V NetworkStats: updateIfacesLocked()
08-16 18:15:14.867  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.867  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:14.867  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:14.867  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:14.867  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 18:15:14.867  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 18:15:14.867  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:14.867  1017  1129 V NetworkStats: performPollLocked() took 3ms
08-16 18:15:14.867  7122  7122 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-16 18:15:14.867  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-16 18:15:14.867  7122  7122 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 18:15:14.867  7122  7122 D UserAnalysis: Create SecureDbHelper,
,08-16 18:15:14.877  1379  1379 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,08-16 18:15:14.877  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.877  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.877  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-16 18:15:14.877  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:14.877  1017  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:14.877  1174  1682 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 18:15:14.877  1479  1479 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 18:15:14.877  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 18:15:14.877  1479  1479 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:14.877  1017  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 18:15:14.877  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 18:15:14.877  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 18:15:14.877  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 18:15:14.877  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:14.877  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:14.887  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.887  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.897  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:14.907  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 18:15:14.907  3181  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:14.907  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 18:15:14.907  3181  3252 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 18:15:14.907  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-16 18:15:14.907  3181  3252 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-16 18:15:14.907  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:14.907  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:14.907  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:14.907  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 18:15:14.907  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-16 18:15:14.907  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 18:15:14.907  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:14.907  7122  7122 D IntelligenceServiceApplication: onCreate()
08-16 18:15:14.907  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:14.907  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:14.907  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.907  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:14.907  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 18:15:14.907  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.907  1017  1124 V NetworkStats: updateIfacesLocked()
08-16 18:15:14.907  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:14.907  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:14.907  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:14.917  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:14.917  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:14.917  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:14.917  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:14.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:14.917  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 18:15:14.917  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 18:15:14.917  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:14.917  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:14.917  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.917  1174  1174 D HotspotTile: onReceive : 0, 0
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.917  1017  1124 V NetworkStats: performPollLocked() took 6ms
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.917  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:14.917  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 18:15:14.917  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 18:15:14.917  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-16 18:15:14.917  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:14.917  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.917  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 18:15:14.917  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:14.917  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:14.917  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.917  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.917  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 18:15:14.917  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.917  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.917  7122  7122 D IntelligenceServiceApplication: no applications having user consent for prediction
08-16 18:15:14.927  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 18:15:14.927  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:14.927  3181  3181 D HeadsetService: Received stop request...Stopping profile...
08-16 18:15:14.927  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:14.927  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:14.927  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 18:15:14.927  1017  4213 I ActivityManager: Killing 6712:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-16 18:15:14.927  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:14.927  1017  1749 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.927  1017  1749 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.927  1017  1749 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.927  1017  1749 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.927  1017  1749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.927  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 18:15:14.927  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-16 18:15:14.927  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-16 18:15:14.927  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-16 18:15:14.927  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-16 18:15:14.927  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-16 18:15:14.937  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:14.937  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 18:15:14.937  7122  7122 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:14.937  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:14.937  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:14.937  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.937  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:14.937  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 18:15:14.937  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.937  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.937  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.937  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.937  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.937  4621  4621 D HeadsetProfile: Bluetooth service disconnected
08-16 18:15:14.937  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:14.937  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:14.947  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 18:15:14.947  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.947  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.947  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.947  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.947  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:14.947  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:14.947  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:14.947  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:14.947  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 18:15:14.947  7122  7122 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-16 18:15:14.947  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.947  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.947  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.947  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.967  7144  7144 E Zygote  : MountEmulatedStorage()
,08-16 18:15:14.967  7144  7144 E Zygote  : v2
08-16 18:15:14.967  7144  7144 I libpersona: KNOX_SDCARD checking this for 10105
08-16 18:15:14.967  7144  7144 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:14.967  7144  7144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:14.967  7144  7144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:14.967  1017  1478 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7144 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 18:15:14.967  7144  7144 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 18:15:14.967  1017  4215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.967  1017  4215 W ActivityManager: userId = 0, bbcId = -10000,
08-16 18:15:14.967  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 18:15:14.967  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.977  1017  4213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:14.967  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.977  1017  4213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 18:15:14.967  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:14.967  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:14.967  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 18:15:14.977  1379  1379 I wpa_supplicant: Blacklist: Clear (all) 
08-16 18:15:14.977  1017  4213 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.977  1017  4213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.977  1017  4213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:14.977  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 18:15:14.977  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:14.977  3181  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:14.977  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.977  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.977  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.977  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.977  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:14.977  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:14.977  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:14.977  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:14.977  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:14.977  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:14.987  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:14.987  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:14.987  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 18:15:14.987  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:14.987  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:14.987  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 18:15:14.987  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:14.987  3181  3252 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:15:14.987  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 18:15:14.987  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:14.987  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 18:15:14.987  3181  3181 D A2dpService: Received stop request...Stopping profile...
08-16 18:15:14.987  3181  3322 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:15:14.987  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:14.987  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:14.987  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 18:15:14.987  4621  4621 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:14.987  4621  4621 D A2dpProfile: Bluetooth service disconnected
,08-16 18:15:14.997  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 18:15:14.997  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 18:15:14.997  7144  7144 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:14.997  3181  3181 D HidService: Received stop request...Stopping profile...
08-16 18:15:14.997  3181  3181 D HidService: Stopping Bluetooth HidService
08-16 18:15:14.997  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:15:14.997  3181  3181 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 18:15:14.997  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:15:14.997  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:14.997  3181  3181 D HealthService: Received stop request...Stopping profile...
,08-16 18:15:14.997  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:14.997  7144  7144 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:14.997  4621  4621 D BluetoothInputDevice: Proxy object disconnected
08-16 18:15:14.997  4621  4621 D HidProfile: Bluetooth service disconnected
,08-16 18:15:14.997  3181  3181 D PanService: Received stop request...Stopping profile...
08-16 18:15:14.997  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:15.007  1379  1379 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 18:15:15.007  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:15.007  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:15.007  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:15.007  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 18:15:15.007  4621  4621 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:15.007  4621  4621 D PanProfile: Bluetooth service disconnected
08-16 18:15:15.007  3181  3181 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 18:15:15.007  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:15.017  3181  3181 D SapService: Received stop request...Stopping profile...
08-16 18:15:15.017  3181  3181 D SapService: Stopping Bluetooth SapService
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:15.017  4621  4621 D BluetoothMap: Proxy object disconnected
,08-16 18:15:15.017  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 18:15:15.017  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 18:15:15.017  3181  3181 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 18:15:15.017  3181  3323 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:15:15.017  3181  3181 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:15:15.017  3181  3181 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:15.017  4621  4621 D MapProfile: Bluetooth service disconnected
,08-16 18:15:15.017  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:15.017  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.017  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:15.017  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.017  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.017  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 18:15:15.027  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:15.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 18:15:15.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:15.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.027  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.027  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 18:15:15.027  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:15:15.027  4621  4621 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-16 18:15:15.027  4621  4621 D SapProfile: Bluetooth service disconnected
08-16 18:15:15.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 18:15:15.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:15.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:15.027  3181  3181 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 18:15:15.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 18:15:15.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:15.027  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 18:15:15.027  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 18:15:15.027  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:15:15.027  3181  3252 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:15.027  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:15.027  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:15.027  3181  3252 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 18:15:15.027  1379  1379 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-16 18:15:15.027  1379  1379 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 18:15:15.027  1379  1379 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 18:15:15.027  1379  1379 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:15.027  1379  1379 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 18:15:15.027  1174  1949 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.027  1174  1949 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.027  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:15.027  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 18:15:15.027  3181  3252 I BluetoothAdapterState: Entering OffState
08-16 18:15:15.027  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:15.027  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:15.027  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:15.027  1017  1130 D Tethering: InitialState.processMessage what=4
,08-16 18:15:15.037  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:15.037  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:15.037  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:15.037  1017  1130 E Tethering: No numeric data
08-16 18:15:15.037  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:15.037  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:15.037  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 18:15:15.037  4621  4629 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 18:15:15.037  4621  4629 D Bluetoothsap: Unbinding service...
,08-16 18:15:15.037  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:15.037  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:15.037  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:15.037  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:15.037  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:15.037  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:15.037  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:15.037  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:15.047  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:15.047  1017  1124 V NetworkStats: performPollLocked() took 5ms
,08-16 18:15:15.047  3181  3196 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.047  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:15.047  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:15.047  4621  4629 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.057  4621  4629 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.057  4621  4632 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 18:15:15.057  6788  6798 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.057  6788  6798 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.057  6788  6798 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 18:15:15.057  6788  6798 D BluetoothLeAdvertiser: Exit stop advertising
08-16 18:15:15.057  6788  6798 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 18:15:15.057  6788  6798 D BluetoothLeScanner: Exiting stopAllScan
08-16 18:15:15.057  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.067  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.067  4621  4629 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.067  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.067  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.067  1465  1499 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.067  1465  1499 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.067  3181  3193 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.067  3181  3193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.067  4621  4632 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:15:15.067  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 18:15:15.067  1479  1764 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.067  1479  1764 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.077  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 18:15:15.077  1711  1736 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.077  1711  1736 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.077  1685  1695 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.077  1685  1695 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.077  1454  1501 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.077  1454  1501 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.077  4621  4632 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:15:15.077  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 18:15:15.077  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.077  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.077  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 18:15:15.077  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:15.077  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,08-16 18:15:15.077  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:15.077  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 18:15:15.087   287   287 E SMD     : DCD OFF
08-16 18:15:15.087  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.087  6788  6788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:15:15.087  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 18:15:15.087  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.087  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:15.087  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:15.087  1174  1174 D BluetoothTile:  getBluetoothState : 10
,08-16 18:15:15.087  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.087  1854  1854 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:15.087  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.097  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:15.097  1017  1321 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:15.097  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:15.097  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:15.097  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.097  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.097  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:15.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.107  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 18:15:15.107  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.107  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.107  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.107  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.107  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.107  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.117  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.117  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.117  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:15.117  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:15.137   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 18:15:15.137   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:15.137  7144  7177 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 18:15:15.157   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 18:15:15.157   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:15.157  7144  7177 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 18:15:15.207  1379  1379 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:15.267  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 18:15:15.267  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:15.267  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:15.267  1379  1379 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 18:15:15.277  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-16 18:15:15.277  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 18:15:15.277  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:15.277  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:15.287  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 18:15:15.287  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.287  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.287  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.287  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.287  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:15.287  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 18:15:15.287  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:15.287  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:15.287  1174  1174 D HotspotTile: onReceive : 1, 0
,08-16 18:15:15.287  1711  2194 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:15.287  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.287  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:15.297  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.k.d(PG:583)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.307  1017  1485 I ActivityManager: Killing 6729:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-16 18:15:15.297  7144  7144 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.297  7144  7144 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.307  1017  1749 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:15.307  1017  1749 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.307  1017  1749 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:15.307  1017  1749 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.307  1017  1749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:15.307  1629  1629 I Hs20UtilService: Starting #8
08-16 18:15:15.307  1629  1658 I Hs20UtilService: Message received 5007
08-16 18:15:15.317  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:15.317  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 18:15:15.317  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 18:15:15.317  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:15.317  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:15.317  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:15.317  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 18:15:15.327  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.327  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.327  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-16 18:15:15.327  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-16 18:15:15.327  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.327  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.327  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.327  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.337  7188  7188 E Zygote  : MountEmulatedStorage()
08-16 18:15:15.337  7188  7188 I libpersona: KNOX_SDCARD checking this for 10102
08-16 18:15:15.337  7188  7188 E Zygote  : v2
08-16 18:15:15.337  7188  7188 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:15.337  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:15.337  1017  1478 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7188 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 18:15:15.337  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:15.347  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 18:15:15.367   304   304 I art     : Explicit concurrent mark sweep GC freed 8666(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 653us total 25.636ms
08-16 18:15:15.377  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:15.377  7188  7188 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.387   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.774ms
,08-16 18:15:15.387  7144  7187 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 18:15:15.397   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.869ms
,08-16 18:15:15.407  7188  7188 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 18:15:15.407  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:15.407  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-16 18:15:15.427  1017  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:15.427  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.427  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:15.427  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.427  1017  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.427  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.427  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:15.637  7188  7210 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-16 18:15:15.637  7188  7210 I Babel_SMS: MmsConfig.loadMmsSettings
08-16 18:15:15.637  7188  7210 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-16 18:15:15.637  7188  7210 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 18:15:15.647  7188  7210 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-16 18:15:15.647  7188  7210 I Babel_SMS: MmsConfig.loadFromResources
,08-16 18:15:15.647  7188  7210 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 18:15:15.647  7188  7210 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-16 18:15:15.657  1017  1504 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 18:15:15.657  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.657  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.657  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.657  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 18:15:15.677  7188  7188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:15.687  7188  7188 I Babel_Crash: startup - clean
,08-16 18:15:15.707  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:15.717  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:15.717  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:15.717  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:15.717  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:15.717  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:15.717  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:15.717  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 18:15:15.717  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.717  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.717  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.717  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.737  7213  7213 E Zygote  : MountEmulatedStorage()
08-16 18:15:15.737  7213  7213 E Zygote  : v2
08-16 18:15:15.737  7213  7213 I libpersona: KNOX_SDCARD checking this for 10064
08-16 18:15:15.737  7213  7213 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:15.737  7213  7213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:15.737  7213  7213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:15.737  7213  7213 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:15.737  7188  7188 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
08-16 18:15:15.737  1017  1504 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7213 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:15.737  7188  7188 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 18:15:15.747  7188  7188 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 18:15:15.747  7188  7188 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 18:15:15.747  7188  7188 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 18:15:15.757  7213  7213 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.757  7213  7213 D ActivityThread: Added TimaKeyStore provider,
,08-16 18:15:15.767  7188  7188 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 18:15:15.767  7188  7188 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 18:15:15.767  7188  7188 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 18:15:15.777  7188  7188 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 18:15:15.787  7213  7213 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 18:15:15.787  7188  7188 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 18:15:15.787  7188  7188 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:15:15.797  7188  7188 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 18:15:15.797  7188  7188 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 18:15:15.797  7188  7188 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:15:15.797  7188  7188 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 18:15:15.797  7188  7188 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 18:15:15.807  7213  7213 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:15.807  7188  7188 W VideoCapabilities: Unsupported mime video/mp43
,08-16 18:15:15.807  7213  7213 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 18:15:15.807  7188  7188 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 18:15:15.817  7188  7188 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 18:15:15.827  7188  7188 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 18:15:15.837  7213  7213 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:15.837  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 18:15:15.837  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.837  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.837  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.837  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.857  7229  7229 E Zygote  : MountEmulatedStorage()
08-16 18:15:15.857  7229  7229 E Zygote  : v2
08-16 18:15:15.857  7229  7229 I libpersona: KNOX_SDCARD checking this for 10065
08-16 18:15:15.857  7229  7229 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:15.857  7229  7229 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:15.857  1017  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7229 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:15.857  1017  1029 I ActivityManager: Killing 6747:com.wsomacp/u0a23 (adj 15): empty #21
,08-16 18:15:15.857  7229  7229 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:15.857  7229  7229 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:15.867  1017  1045 D Tethering: interfaceRemoved wlan0
,08-16 18:15:15.867  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 18:15:15.877  7188  7188 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:15:15.877  7188  7188 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:15:15.877  7188  7188 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:15:15.887  7188  7188 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:15:15.887  1017  4214 I ActivityManager: Killing 6833:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-16 18:15:15.887  7229  7229 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.887  7229  7229 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.887  7188  7188 I vclib   : onServiceConnected
,08-16 18:15:15.907  7229  7229 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:15.917  1017  1505 I ActivityManager: Killing 6876:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 18:15:15.917  1017  4214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:15.917  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:15.917  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.917  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.917  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:15.927  1629  1629 I Hs20UtilService: Starting #9
,08-16 18:15:15.927  1629  1658 I Hs20UtilService: Message received 5007
,08-16 18:15:15.927  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:15.927  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:15.927  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:15.927  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:15.927  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:15.927  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:15.927  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:15.937  1017  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:15.937  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:15.937  1017  1321 W ActivityManager: userId = 0, bbcId = -10000,
08-16 18:15:15.937  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.937  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:15.937  1629  1629 I Hs20UtilService: Starting #10
08-16 18:15:15.937  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:15.937  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:15.947  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:15.947  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:15.947  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:15.947  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.947  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.947  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.957  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.957  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.957  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:15.957  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.967  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.967  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.967  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.967  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.967  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.967  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.967  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.977  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.977  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:15.977  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.977  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.987  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.987  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.987  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.987  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.997  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.997  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.997  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:15.997  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.997  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.997  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.007  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:16.007  1017  1506 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 18:15:16.007  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.007  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.007  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.007  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:16.017  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:16.017  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:16.027  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:16.027  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:16.027  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 18:15:16.037  1017  1045 D Tethering: interfaceRemoved p2p0
08-16 18:15:16.037  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 18:15:16.047  1017  4211 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:16.047  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:16.047  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.047  1017  4211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.047  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:16.057  1629  1629 I Hs20UtilService: Starting #11
,08-16 18:15:16.057  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:16.057  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:16.057  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:16.057  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:16.057  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:16.067  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 18:15:16.067  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.067  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.067  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.067  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.077  1017  1516 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7247 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 18:15:16.077  7247  7247 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.077  7247  7247 E Zygote  : v2
08-16 18:15:16.077  7247  7247 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:16.077  7247  7247 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.077  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:16.087  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.087  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:16.107  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.107  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.127  7247  7247 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 18:15:16.127  7247  7247 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 18:15:16.127  7247  7247 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 18:15:16.147  7247  7247 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 18:15:16.147  7247  7247 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 18:15:16.147  7247  7247 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 18:15:16.147  7247  7247 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:16.147  1017  4213 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-16 18:15:16.147  1017  4213 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-16 18:15:16.147  1017  4213 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-16 18:15:16.147  7247  7262 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-16 18:15:16.147  1017  4213 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-16 18:15:16.147  1017  4213 I ActivityManager: Killing 6894:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-16 18:15:16.157  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 18:15:16.157  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.157  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.157  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.157  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.177  7264  7264 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.177  7264  7264 I libpersona: KNOX_SDCARD checking this for 10001
08-16 18:15:16.177  7264  7264 E Zygote  : v2
08-16 18:15:16.177  7264  7264 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.177  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 18:15:16.177  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7264 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 18:15:16.177  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.177  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:16.197  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.197  7264  7264 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.267  1017  4215 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-16 18:15:16.267  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.267  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.267  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.267  1017  4215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.287  7282  7282 E Zygote  : MountEmulatedStorage()
,08-16 18:15:16.287  7282  7282 E Zygote  : v2
08-16 18:15:16.287  7282  7282 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:16.287  7282  7282 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.287  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:16.287  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:16.287  1017  4215 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7282 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:16.287  1017  4215 I ActivityManager: Killing 6502:com.android.mms/u0a41 (adj 15): empty #21
,08-16 18:15:16.287  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.307  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.307  7282  7282 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.347  7282  7282 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 18:15:16.377  1017  1516 D CountryDetector: No listener is left
,08-16 18:15:16.467  7282  7282 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-16 18:15:16.477  7282  7282 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-16 18:15:16.477  7282  7282 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:16.477  7282  7282 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 18:15:16.477  7282  7282 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-16 18:15:16.477  7282  7282 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 18:15:16.477  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-16 18:15:16.477  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.487  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.487  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.487  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.497  1017  1029 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7298 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:16.497  1017  1029 I ActivityManager: Killing 6913:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21,
,08-16 18:15:16.497  7298  7298 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.497  7298  7298 E Zygote  : v2
08-16 18:15:16.497  7298  7298 I libpersona: KNOX_SDCARD checking this for 10008
08-16 18:15:16.497  7298  7298 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.497  7298  7298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:16.497  7298  7298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.507  7298  7298 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.517  7298  7298 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.517  7298  7298 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.577  1017  1505 I ActivityManager: Killing 6327:com.samsung.android.sm/1000 (adj 15): empty #21
,08-16 18:15:16.587  1017  4211 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-16 18:15:16.587  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.587  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.587  1017  4211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:16.587  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-16 18:15:16.607  3785  7313 I iu.SyncManager: SYNC; picasa accounts
,08-16 18:15:16.607  3785  3785 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-16 18:15:16.617  1017  4211 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:16.617  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.617  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.617  1017  4211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:16.617  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:16.627  3785  3785 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 18:15:16.627  3785  3785 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-16 18:15:16.637  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 18:15:16 GMT+02:00 2016
,08-16 18:15:16.637  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 18:15:16.637  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.637  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.637  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.637  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:16.647  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 18:15:16.647  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 18:15:16.647  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.647  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.647  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.647  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.657  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 18:15:16.657  2802  2802 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:16.667  7316  7316 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.667  7316  7316 E Zygote  : v2
,08-16 18:15:16.667  7316  7316 I libpersona: KNOX_SDCARD checking this for 10031
08-16 18:15:16.667  7316  7316 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.667  1017  1029 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7316 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-16 18:15:16.667  7316  7316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:16.667  7316  7316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.667  7316  7316 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.667  2802  2802 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:16.677  2802  7315 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 18:15:16.677  2802  7315 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:16.687  2802  7315 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 18:15:16.687  2802  7315 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-16 18:15:16.687  7316  7316 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.697  7316  7316 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.697  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 18:15:16.727  7316  7316 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 18:15:16.727  1017  4215 I ActivityManager: Killing 6930:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-16 18:15:16.737  1017  1749 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 18:15:16.737  2740  7331 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-16 18:15:16.737  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.737  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.737  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.737  1017  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.747  2740  7331 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 18:15:16.747  2740  7331 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 18:15:16.747  2740  7331 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-16 18:15:16.747  2740  7331 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 18:15:16.757  7332  7332 E Zygote  : MountEmulatedStorage()
,08-16 18:15:16.757  7332  7332 E Zygote  : v2
08-16 18:15:16.757  7332  7332 I libpersona: KNOX_SDCARD checking this for 10032,
08-16 18:15:16.757  7332  7332 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.757  7332  7332 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:16.757  1017  1749 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7332 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 18:15:16.767  7332  7332 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.767  7332  7332 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-16 18:15:16.797  7332  7332 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.797  7332  7332 D ActivityThread: Added TimaKeyStore provider,
,08-16 18:15:16.857  7332  7347 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-16 18:15:16.857  7332  7347 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 18:15:16.857  7332  7347 D SPPClientService: PushLog.txt file is not deleted.
,08-16 18:15:16.857  7332  7347 D SPPClientService: PushLog.txt file is not deleted.
,08-16 18:15:16.857  7332  7347 D SPPClientService: ============PushLog. stop!,
,08-16 18:15:16.867  7332  7332 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 18:15:16.867  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-16 18:15:16.867  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.867  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.867  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.867  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.887  1017  1135 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7349 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:16.887  7349  7349 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.887  1017  1135 I ActivityManager: Killing 6945:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-16 18:15:16.887  7349  7349 E Zygote  : v2
08-16 18:15:16.887  7349  7349 I libpersona: KNOX_SDCARD checking this for 10036
08-16 18:15:16.887  7349  7349 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:16.887  7349  7349 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:16.887  1017  1516 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-16 18:15:16.887  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.887  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-16 18:15:16.887  1017  1516 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 18:15:16.887  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 18:15:16.887  7349  7349 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:16.887  7349  7349 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.907  7349  7349 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.907  7349  7349 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.917  7332  7355 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-16 18:15:16.917  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 18:15:16.947  7349  7349 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@21a33009
,08-16 18:15:16.957  7349  7349 I SA      : [SSP] onCreated
,08-16 18:15:16.967  7349  7349 I SA      : [TPM] There is no property file
,08-16 18:15:16.967  7349  7349 I SA      : [SCU] isHaveSA() - false
,08-16 18:15:16.967  7349  7349 I SA      : [TPM] getModelProperty : null
08-16 18:15:16.967  7349  7349 I SA      : [TPM] getCSCProperty : null
,08-16 18:15:16.967  7349  7349 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-16 18:15:16.967  7349  7349 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-16 18:15:16.967  7349  7349 I SA      : [DM] TFT FEATURE: false
,08-16 18:15:16.977  7349  7349 I SA      : [DM] init START
,08-16 18:15:16.977  7349  7349 I SA      : [DM] This device is not a Vodafone
,08-16 18:15:16.977  7349  7349 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-16 18:15:16.977  7349  7349 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-16 18:15:16.987  7349  7349 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-16 18:15:16.997  7349  7349 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-16 18:15:17.007  7349  7349 I SA      : [SCU] isHaveSA() - false
08-16 18:15:17.007  7349  7349 I SA      : support phone number id : false
08-16 18:15:17.007  7349  7349 I SA      : [DM] Supports Ref Jpn : true
,08-16 18:15:17.007  7349  7349 I SA      : [DM] init END
08-16 18:15:17.007  7349  7349 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-16 18:15:17.007  7349  7349 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-16 18:15:17.007  7349  7349 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 18:15:17.007  7349  7349 I SA      : [SLFUCHKMGR] constructor called
,08-16 18:15:17.017  7349  7349 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-16 18:15:17.017  7349  7349 I SA      : [OR] == isSIMCardReady false ==
,08-16 18:15:17.017  7349  7349 I SA      : [SCU] == networkStateCheck == false
,08-16 18:15:17.017  7349  7349 I SA      : [OR] onReceive END
,08-16 18:15:17.027  1017  1485 I ActivityManager: Killing 7031:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-16 18:15:17.027  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:17.037  1822  1822 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:17.037  2664  5177 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-16 18:15:17.037  1822  1822 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-16 18:15:17.037  1822  1822 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-16 18:15:17.037  1822  1822 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-16 18:15:17.037  1822  1822 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:17.047  1822  1822 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:17.047  1822  1822 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 18:15:17.047  1017  4214 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 18:15:17.047  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.047  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.047  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.047  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.067  7371  7371 E Zygote  : MountEmulatedStorage()
,08-16 18:15:17.067  7371  7371 E Zygote  : v2
08-16 18:15:17.067  1017  4214 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7371 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:17.067  7371  7371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:17.067  7371  7371 I libpersona: KNOX_SDCARD checking this for 10077
08-16 18:15:17.067  7371  7371 I libpersona: KNOX_SDCARD not a persona,
,08-16 18:15:17.067  7371  7371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:17.067  7371  7371 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.087  7371  7371 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.087  7371  7371 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.267  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-16 18:15:17.267  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.267  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.277  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.277  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 18:15:17.277  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 18:15:17.277  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.277  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.277  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.277  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.287  7390  7390 E Zygote  : MountEmulatedStorage(),
08-16 18:15:17.287  7390  7390 I libpersona: KNOX_SDCARD checking this for 10110
08-16 18:15:17.287  7390  7390 E Zygote  : v2
,08-16 18:15:17.287  7390  7390 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:17.287  7390  7390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:17.297  1017  1516 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7390 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:17.297  7390  7390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:17.297  1017  4215 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-16 18:15:17.297  7390  7390 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.297  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.297  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.297  1017  4215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:17.297  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 18:15:17.297  7188  7389 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 18:15:17.307  1017  1321 I ActivityManager: Killing 6998:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-16 18:15:17.317  7390  7390 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.317  7390  7390 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.327   304   304 I art     : Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 23.742ms
,08-16 18:15:17.337   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.519ms
,08-16 18:15:17.357   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.171ms
,08-16 18:15:17.427  1017  4214 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-16 18:15:17.517   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 18:15:17.517   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.517  7390  7409 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 18:15:17.527   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:17.527   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.527  7390  7409 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 18:15:17.537   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 18:15:17.537   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.537  7390  7410 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 18:15:17.537   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:17.537   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.537  7390  7410 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 18:15:17.567  7390  7390 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 18:15:17.567  7390  7390 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 18:15:17.567  7390  7390 I GAv4    :   adb logcat -s GAv4
,08-16 18:15:17.587  7390  7390 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:15:17.587  1017  4215 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 18:15:17.597  7390  7390 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:15:17.607  7390  7412 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:15:17.667  1017  1506 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:17.667  1017  1506 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 18:15:17.667  1017  1506 D SecContentProvider2: mCursor = null
,08-16 18:15:17.667  1017  1506 D WifiService: setWifiEnabled: true pid=6788, uid=10170
,08-16 18:15:17.667  1017  1506 W ActivityManager: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:17.667  1017  1506 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:17.667  1017  1506 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:17.667  1017  1506 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 18:15:17.667  1017  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:17.667  1017  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:17.667  1017  1506 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:17.667  1017  1506 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 18:15:17.667  1017  1506 D SettingsProvider: name = wifi_on
,08-16 18:15:17.667  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 18:15:17.787  1017  1050 I PowerManagerService: [PWL] Off : 50s ago
08-16 18:15:17.787  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 18:15:17.787  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 18:15:17.787  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=2883)
,08-16 18:15:17.827  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:17.827  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.827  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.827  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 18:15:17.857  7390  7390 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-16 18:15:17.877  7390  7390 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 2842-2846)
08-16 18:15:17.877  7390  7390 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 18:15:17.887  7390  7390 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c0152e8}
,08-16 18:15:17.887  7390  7390 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 18:15:17.887  7390  7390 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 18:15:17.907  7390  7390 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-16 18:15:17.907  7390  7390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:15:17.917  7390  7390 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 18:15:17.927  7390  7390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:15:17.927  7390  7390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:15:17.927  7390  7390 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:15:17.927  7390  7390 I Adreno-EGL: Local Branch: 
08-16 18:15:17.927  7390  7390 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:15:17.927  7390  7390 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:15:17.927  7390  7390 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:15:17.987  1017  3327 D SSRM:n  : SIOP:: AP = 380
,08-16 18:15:17.987  7390  7390 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 18:15:17.997  7390  7447 W cr.media: Requires BLUETOOTH permission
,08-16 18:15:17.997  7390  7390 I NSApplication: Starting up...
,08-16 18:15:17.997  1017  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 18:15:17.997  1017  4211 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 18:15:18.007  1017  4213 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 18:15:18.007  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.007  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.007  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.007  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.017  1017  4213 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7452 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:18.027  1017  4213 I ActivityManager: Killing 7049:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-16 18:15:18.027  7452  7452 E Zygote  : MountEmulatedStorage()
08-16 18:15:18.027  7452  7452 I libpersona: KNOX_SDCARD checking this for 10117
08-16 18:15:18.027  7452  7452 E Zygote  : v2
08-16 18:15:18.027  7452  7452 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:18.027  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:18.027  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:18.027  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:18.047  1017  1045 D Tethering: interfaceAdded wlan0,
,08-16 18:15:18.047  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:18.047  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:18.047  1017  1130 E Tethering: No numeric data
,08-16 18:15:18.047  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:18.047  1017  1130 D Tethering: clearTetheredNotification()
08-16 18:15:18.047  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:18.047  1017  1130 D Tethering: InitialState.processMessage what=4
,08-16 18:15:18.047  1017  1130 E Tethering: No numeric data
,08-16 18:15:18.057  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.057  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:18.057  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:18.057  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:18.057  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:18.057  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:18.057  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:18.057  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:18.057  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:18.057   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 18:15:18.057   277  1016 D SoftapController: Softap fwReload - Ok
08-16 18:15:18.057  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:18.057  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:18.057  1017  1045 D Tethering: interfaceAdded p2p0
,08-16 18:15:18.057  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 18:15:18.067  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-16 18:15:18.067  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.067   277  1016 D CommandListener: Setting iface cfg
08-16 18:15:18.067   277  1016 D CommandListener: Trying to bring down wlan0
,08-16 18:15:18.067   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:18.067  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:18.067  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:18.067  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 18:15:18.067  1017  1124 V NetworkStats: performPollLocked(flags=0x1),
08-16 18:15:18.067  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.067  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.067  7452  7452 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:18.067  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-16 18:15:18.067  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:18.077  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.077  1017  1124 V NetworkStats: performPollLocked() took 8ms
,08-16 18:15:18.087  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.087  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.087   287   287 E SMD     : DCD OFF
,08-16 18:15:18.087  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.087  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.087  7452  7452 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:18.137  7468  7468 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-16 18:15:18.137  7468  7468 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:15:18.137  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 18:15:18.157  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-16 18:15:18.157   344   344 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7468,
08-16 18:15:18.157   344   344 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-16 18:15:18.157  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 18:15:18.157  7468  7468 I wpa_supplicant: ssSupport state is = 1,
08-16 18:15:18.157  7468  7468 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 18:15:18.157  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 18:15:18.157   344   344 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7468
08-16 18:15:18.157   344   344 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-16 18:15:18.167  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 18:15:18.187  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:18.187  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.187  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.187  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:18.187  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 18:15:18.187  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:18.187  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:18.187  1174  1174 D HotspotTile: onReceive : 2, 0
,08-16 18:15:18.187  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:18.187  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:18.327   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-16 18:15:18.337  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-16 18:15:18.387  7468  7468 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 18:15:18.387  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 18:15:18.397  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-16 18:15:18.397   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
08-16 18:15:18.397   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 18:15:18.397  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,08-16 18:15:18.397  7468  7468 I wpa_supplicant: ssSupport state is = 1
,08-16 18:15:18.407  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 18:15:18.407  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:18.407  7468  7468 E wpa_supplicant: SIM READ ERROR
08-16 18:15:18.407  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:18.407  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:18.407  7468  7468 E wpa_supplicant: SIM READ ERROR
08-16 18:15:18.407  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:18.407  7468  7468 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:18.407  7468  7468 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:18.407  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:18.407  7468  7468 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 18:15:18.407  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:18.407  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:18.407  7468  7468 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:18.407  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:18.407  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:18.407  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:18.457  1017  4213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 18:15:18.457  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.457  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.457  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.457  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.467  7477  7477 E Zygote  : MountEmulatedStorage()
,08-16 18:15:18.467  7477  7477 I libpersona: KNOX_SDCARD checking this for 10121
08-16 18:15:18.467  7477  7477 E Zygote  : v2
08-16 18:15:18.467  7477  7477 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:18.467  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:18.467  1017  4213 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7477 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-16 18:15:18.467  1017  4213 I ActivityManager: Killing 6963:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-16 18:15:18.467  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:18.477  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:18.487  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 18:15:18.487  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.497  7477  7477 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.507  7477  7477 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:18.507  7477  7477 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 18:15:18.507  7477  7477 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:18.517  7477  7477 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:18.527  7477  7477 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-16 18:15:18.527  7477  7477 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 18:15:18.527  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-16 18:15:18.527  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.527  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.527  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.527  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.547  7494  7494 E Zygote  : MountEmulatedStorage(),
08-16 18:15:18.547  7494  7494 I libpersona: KNOX_SDCARD checking this for 10141
08-16 18:15:18.547  7494  7494 E Zygote  : v2
08-16 18:15:18.547  7494  7494 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:18.547  7494  7494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:18.547  7494  7494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:18.547  7494  7494 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:18.557  1017  1030 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7494 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-16 18:15:18.557  1017  1030 I ActivityManager: Killing 6978:com.android.calendar/u0a131 (adj 15): empty #21
,08-16 18:15:18.567  7494  7494 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.577  7494  7494 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.587  7494  7494 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-16 18:15:18.587  7494  7494 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:18.587  7494  7494 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:18.587  7494  7494 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 18:15:18.637  1017  1505 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.647  1017  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.657  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 18:15:18.657  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 18:15:18.667  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-16 18:15:18.667   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
08-16 18:15:18.667   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 18:15:18.667  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 18:15:18.667  7468  7468 I wpa_supplicant: ssSupport state is = 1
,08-16 18:15:18.667  7468  7468 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 18:15:18.667  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 18:15:18.677  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-16 18:15:18.677   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
08-16 18:15:18.677   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 18:15:18.677  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 18:15:18.677  7468  7468 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:18.677  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:18.677  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:18.677  7468  7468 E wpa_supplicant: SIM READ ERROR
,08-16 18:15:18.677  7468  7468 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:18.677  7468  7468 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:18.677  7468  7468 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:18.687  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:18.687  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:18.687  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:18.687  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:18.687  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:18.687  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:18.697  1017  4213 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.707  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.737  7468  7468 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-16 18:15:18.737  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 18:15:18.747  1017  1505 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-16 18:15:18.747  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.747  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.747  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.747  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.757  1017  1504 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.757  7518  7518 E Zygote  : MountEmulatedStorage()
08-16 18:15:18.757  7518  7518 E Zygote  : v2
08-16 18:15:18.757  7518  7518 I libpersona: KNOX_SDCARD checking this for 10068
08-16 18:15:18.757  7518  7518 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:18.757  7518  7518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:18.767  1017  1505 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7518 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
08-16 18:15:18.767  7518  7518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:18.767  7518  7518 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-16 18:15:18.777  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.797  1017  1504 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:18.797  1017  4214 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-16 18:15:18.807  7518  7518 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.807  7518  7518 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.807  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.807  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.807  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.807  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.817  7468  7468 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-16 18:15:18.817  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 18:15:18.817  7468  7468 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:18.827  1017  4214 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7534 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
08-16 18:15:18.827  1017  4214 I ActivityManager: Killing 6762:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-16 18:15:18.827  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-16 18:15:18.827  7534  7534 E Zygote  : MountEmulatedStorage()
08-16 18:15:18.827  7534  7534 I libpersona: KNOX_SDCARD checking this for 10009
08-16 18:15:18.827  7534  7534 E Zygote  : v2,
08-16 18:15:18.827  7534  7534 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:18.827  7534  7534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 18:15:18.827  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 18:15:18.827  7468  7468 I wpa_supplicant: HOTSPOT20_ENABLE called
08-16 18:15:18.827  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:18.827  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:18.827  7468  7468 E wpa_supplicant: SIM READ ERROR
08-16 18:15:18.827  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
08-16 18:15:18.837  1017  1749 I ActivityManager: Killing 7072:com.android.vending/u0a26 (adj 15): empty #21
,08-16 18:15:18.837  7534  7534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:18.837  7534  7534 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 18:15:18.877  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 18:15:18.877  7534  7534 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.877  7534  7534 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.897  7468  7468 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:18.907  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-16 18:15:18.917  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:18.917  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:18.917  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:18.917  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:18.917  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:18.917  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:18.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.917  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:18.917  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:18.917  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:18.927  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:18.927  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-16 18:15:18.927  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-16 18:15:18.927  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:18.927  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 18:15:18.927  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:18.927  1174  1174 D HotspotTile: onReceive : 3, 0,
,08-16 18:15:18.937  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:18.937  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:18.937  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 18:15:18.937  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:18.937  1017  1127 E WifiConfigStore: Not a HS20
,08-16 18:15:18.947  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 18:15:18.947  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-16 18:15:18.957  7468  7468 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON,
08-16 18:15:18.957  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 18:15:18.957  7468  7468 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 18:15:18.957  7468  7468 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-16 18:15:18.957  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 18:15:18.957  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 18:15:18.957  7468  7468 I wpa_supplicant: First Scan Start
,08-16 18:15:18.957  7468  7468 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,08-16 18:15:18.957  7188  7188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:18.957  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-16 18:15:18.957  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:18.957  1017  1127 I WifiNative-HAL: startHal
,08-16 18:15:18.957  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ebf288c
,08-16 18:15:18.957  1017  1127 I WifiNative-HAL: Could not start hal
,08-16 18:15:18.957  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:18.967  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-16 18:15:18.967   277  1016 D CommandListener: Setting iface cfg
08-16 18:15:18.967   277  1016 D CommandListener: Trying to bring up p2p0
08-16 18:15:18.967  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 18:15:18.967  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 18:15:18.967  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:15:18.967  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:18.967  1017  1151 I WifiNative-HAL: startHal
08-16 18:15:18.967  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dab49bc
08-16 18:15:18.967  1017  1151 I WifiNative-HAL: Could not start hal
08-16 18:15:18.967  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:18.967  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:18.967  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-16 18:15:18.967  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-16 18:15:18.967  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:18.967  1017  1151 E WifiScanningService: could not start HAL
08-16 18:15:18.967  1017  1126 D WifiP2pService: P2pEnablingState
08-16 18:15:18.967  7468  7468 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:18.967  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:18.967  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 18:15:18.967  1017  1126 D WifiP2pService: P2p socket connection successful
08-16 18:15:18.967  1017  1126 D WifiP2pService: P2pEnabledState
,08-16 18:15:18.977  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 18:15:18.977  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:18.977  7468  7468 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-16 18:15:18.977  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,08-16 18:15:18.977  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:18.977  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:18.977  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 18:15:18.977  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-16 18:15:18.977  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:18.977  1017  1048 D WifiDisplayController: disconnect
08-16 18:15:18.977  1017  1048 D WifiDisplayController: updateConnection
08-16 18:15:18.977  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:18.977  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:18.987  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-16 18:15:18.987  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-16 18:15:18.987  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:18.987  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:18.987  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:18.987  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:18.987  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:18.987  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 18:15:18.987  1017  1127 D SecContentProvider2: mCursor = null
08-16 18:15:18.987  1017  1749 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:18.987  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:18.987  1017  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-16 18:15:18.987  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  secondary type: null
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  wps: 0
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  grpcapab: 0
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  devcapab: 0
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  status: 3
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  wfdInfo: null
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-16 18:15:18.987  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-16 18:15:19.017  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 18:15:19.017  1017  1126 D WifiP2pService: InactiveState
,08-16 18:15:19.017  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:19.017  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:19.017  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 18:15:19.017  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:19.017  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:19.037  1017  4215 I art     : Explicit concurrent mark sweep GC freed 61474(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 22MB/34MB, paused 2.585ms total 193.456ms
,08-16 18:15:19.047  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:19.047  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:19.047  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:19.057  7518  7518 D BadgeProvider: onCreate
,08-16 18:15:19.057  7518  7518 D BadgeProvider: DatabaseHelper
,08-16 18:15:19.087  7518  7529 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 18:15:19.087  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-16 18:15:19.087  1017  1516 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 18:15:19.097  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 18:15:19.097  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 18:15:19.107  7518  7529 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-16 18:15:19.107  7518  7529 D BadgeProvider: sendNotify, [notify] : null
08-16 18:15:19.107  7518  7529 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 18:15:19.107  7518  7529 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 18:15:19.107  7518  7529 D BadgeProvider: update, [UpdateCount] : 1
,08-16 18:15:19.107  1507  1507 D Launcher.Model: reloadBadges entered.
,08-16 18:15:19.127  1017  4211 I ActivityManager: Killing 7213:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-16 18:15:19.137  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:19.137  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:19.137  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:19.137  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:19.137  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:19.137  1629  1629 I Hs20UtilService: Starting #12
,08-16 18:15:19.137  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:19.137  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:19.137  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:19.137  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:19.137  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:19.147  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:19.147  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:19.147  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:19.147  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:19.147  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:19.157  1629  1629 I Hs20UtilService: Starting #13
,08-16 18:15:19.157  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:19.157  1629  1658 I Hs20UtilService: Message received 5011
08-16 18:15:19.157  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:19.157  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:19.157  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:19.157  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:19.157  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:19.157  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-16 18:15:19.167  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:19.167  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:19.167  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:19.167  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:19.167  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:19.167  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:19.167  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:19.167  1017  1505 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 18:15:19.177  1017  1505 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-16 18:15:19.177  1017  1505 W BroadcastQueue: android.os.TransactionTooLargeException
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-16 18:15:19.177  1017  1505 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:19.177  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 18:15:19.177  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:19.177  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:19.177  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:19.177  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:19.177   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:19.197  7556  7556 E Zygote  : MountEmulatedStorage()
08-16 18:15:19.197  7556  7556 E Zygote  : v2
,08-16 18:15:19.197  7556  7556 I libpersona: KNOX_SDCARD checking this for 10064
08-16 18:15:19.197  7556  7556 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:19.197  1017  1505 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7556 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:19.197  7556  7556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:19.197  7556  7556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:19.197  7556  7556 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:19.217  7556  7556 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:19.217  7556  7556 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:19.237  1017  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7213/cgroup.procs: No such file or directory
,08-16 18:15:19.237  7556  7556 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 18:15:19.247  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:19.257  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 18:15:19.287  7556  7556 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:19.297  7229  7229 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:19.297  1017  1135 I ActivityManager: Killing 7122:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-16 18:15:20.177  7468  7468 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
,08-16 18:15:20.177  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 18:15:20.177  7468  7468 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 18:15:20.177  7468  7468 I wpa_supplicant: Trying to associate with  'G700'
08-16 18:15:20.177  7468  7468 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-16 18:15:20.177   314   314 I ServiceManager: Waiting for service AtCmdFwd...
08-16 18:15:20.177  1017  7540 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 18:15:20.177  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-16 18:15:20.197  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:20.207  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:20.297  7468  7468 E wpa_supplicant: Cmd 35605 not handled
,08-16 18:15:20.297  7468  7468 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-16 18:15:20.297  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-16 18:15:20.297  7468  7468 I wpa_supplicant: Associated with F4.99.3E,
08-16 18:15:20.297  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:20.297  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:20.297  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:20.297  7468  7468 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 18:15:20.297  7468  7468 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 18:15:20.297  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 18:15:20.307  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 18:15:20.307  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:20.307  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:20.307  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:20.307  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:20.307  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:20.307  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:20.307  1017  1045 D Tethering: interfaceStatusChanged wlan0, true,
,08-16 18:15:20.307  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 18:15:20.307  1017  1130 E Tethering: No numeric data
,08-16 18:15:20.317  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:20.317  1017  1127 D SecContentProvider2: mCursor = null
08-16 18:15:20.317  7468  7468 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 18:15:20.317  7468  7468 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 18:15:20.317  7468  7468 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-16 18:15:20.317  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:20.317  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:20.317  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:20.317  7468  7468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:20.317  7468  7468 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 18:15:20.317  7468  7468 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 18:15:20.317  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:20.317  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:20.317  7468  7468 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 18:15:20.317  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:20.317  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 18:15:20.317  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:20.317  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 18:15:20.317  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:20.317  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:20.317  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:20.317  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:20.317  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:20.327  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:20.327  1017  1124 V NetworkStats: performPollLocked() took 5ms
08-16 18:15:20.327  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:20.327  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:20.327  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:20.327  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 18:15:20.337  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:20.337  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.337  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.347  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 18:15:20.347  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 18:15:20.347  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:20.347  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 18:15:20.347  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:20.347  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:20.347  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:20.347  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:20.347  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:20.347  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 18:15:20.357  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:20.357  1629  1629 I Hs20UtilService: Starting #14
,08-16 18:15:20.357  1629  1658 I Hs20UtilService: Message received 5007
08-16 18:15:20.357  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:20.357  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.357  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:20.357  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:20.357  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:20.357  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:20.357  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.367   277  1016 D CommandListener: Setting iface cfg,
08-16 18:15:20.367  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 18:15:20.377  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:20.377  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:20.377  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:20.377  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:20.387  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:20.387  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.387  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.387  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.387  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.387  1017  1127 E WifiNative-wlan0: do suspend false
,08-16 18:15:20.387  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:20.387  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-16 18:15:20.387  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-16 18:15:20.397  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:20.607  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 18:15:20.617  7573  7573 I dhcpcd  : version 5.5.6 starting
,08-16 18:15:20.617  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 18:15:20.677  1017  1321 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-16 18:15:20.677  1017  1321 D WifiService: setWifiEnabled: false pid=6788, uid=10170,
08-16 18:15:20.677  1017  1321 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-16 18:15:20.677  1017  1321 D SecContentProvider2: mCursor = null,
08-16 18:15:20.677  1017  1321 D SettingsProvider: name = wifi_on
,08-16 18:15:20.687  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-16 18:15:20.687  7573  7573 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 18:15:20.687  7573  7573 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 18:15:20.687  7573  7573 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-16 18:15:20.697  7573  7573 I dhcpcd  : bssid match
,08-16 18:15:20.697  7573  7573 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-16 18:15:20.707  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:20.727  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-16 18:15:20.727  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
08-16 18:15:20.737   277  1016 D CommandListener: Clearing all IP addresses on wlan0,
,08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 18:15:20.737  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:20.737  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.737  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.737  1017  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.737  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 18:15:20.737  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.737  1017  1129 V NetworkStats: updateIfacesLocked()
08-16 18:15:20.737  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:20.737  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:20.737   277  1016 E Netd    : no such netId 503
08-16 18:15:20.737  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 18:15:20.737  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:20.737  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:20.747  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:20.747  1017  1129 V NetworkStats: performPollLocked() took 4ms
08-16 18:15:20.747  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:20.757  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:20.757  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:20.757  1017  7571 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-16 18:15:20.757  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-16 18:15:20.757  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
,08-16 18:15:20.757  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 18:15:20.757  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 18:15:20.757  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-16 18:15:20.757  1017  7571 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 18:15:20.757  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-16 18:15:20.757  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:20.757  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:20.757  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:15:20.757  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:20.757  1629  1629 I Hs20UtilService: Starting #15
08-16 18:15:20.757  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 18:15:20.757  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:20.757  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:20.757  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:20.757  1629  1658 I Hs20UtilService: Message received 5007
08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.757  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.757  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:20.757  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:20.757  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:20.757  1017  1129 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 18:15:20.767  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:20.767  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:20.767  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:20.767  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.767  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:20.767  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:20.767  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:20.767  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:20.767  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:20.767  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 18:15:20.767  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:20.777  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 18:15:20.777  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:20.777  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:20.777  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:20.777  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 18:15:20.777  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:20.777  1017  1048 D WifiDisplayController: disconnect
08-16 18:15:20.777  1017  1048 D WifiDisplayController: updateConnection
08-16 18:15:20.777  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:20.777  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:20.777  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.777  1017  1126 D WifiP2pService: P2pDisablingState
,08-16 18:15:20.777  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 18:15:20.777  1017  1126 D WifiP2pService: p2p socket connection lost
,08-16 18:15:20.777  1017  1126 D WifiP2pService: P2pDisabledState
,08-16 18:15:20.777  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:20.777  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 18:15:20.777  1017  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:20.777  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:20.787  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 18:15:20.787  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:20.787  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:20.787  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:20.787  7573  7573 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
08-16 18:15:20.787  7573  7573 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-16 18:15:20.787  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:20.797  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.797  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:20.797  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:20.797  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:20.797  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:20.797  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.797  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.797  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 18:15:20.797  7556  7556 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:20.807  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 18:15:20.807  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-16 18:15:20.807  7229  7229 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.807   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:20.817  7468  7468 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,08-16 18:15:20.827  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-16 18:15:20.827  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:20.827  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:20.827  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.827  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.847  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:20.847  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 18:15:20.847  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:20.857  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:20.857  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.857  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:20.857  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.857  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:20.857  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.857  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.867  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:20.867  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:20.867  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:20.867  1629  1629 I Hs20UtilService: Starting #16
,08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:20.867  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.867  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.867  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:20.867  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 18:15:20.867  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:20.867  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:20.867  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:20.867  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:20.867  1174  1174 D HotspotTile: onReceive : 0, 0
08-16 18:15:20.867  1629  1658 I Hs20UtilService: Message received 5007
,08-16 18:15:20.867  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:20.867  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:20.877  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:20.877  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.877  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:20.877  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:20.877  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 18:15:20.877  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.877  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:20.877  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:20.887  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:20.887  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:20.887  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.887  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:20.887  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:20.907  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:20.907  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:20.907  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:20.907  1629  1629 I Hs20UtilService: Starting #17
08-16 18:15:20.907  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:20.907  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:20.907  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:20.907  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:20.907  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:20.987  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:21.027  1017  4211 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:21.027  1017  4211 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 18:15:21.027  1017  4211 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 18:15:21.027  1017  4211 D BatteryService: stay LED for charging
08-16 18:15:21.027  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:21.027  1017  1017 I MotionRecognitionService: Plugged
,08-16 18:15:21.027  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:21.037  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 18:15:21.037  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:21.037  1438  1438 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 18:15:21.037  1438  1438 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 18:15:21.057  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 18:15:21.057  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-16 18:15:21.067  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:21.067  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:21.067  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:21.087  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 18:15:21.087  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:21.087  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:21.087  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 18:15:21.087   287   287 E SMD     : DCD OFF
,08-16 18:15:21.117  7468  7468 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-16 18:15:21.117  7468  7468 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
08-16 18:15:21.117  7468  7468 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
08-16 18:15:21.117  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:21.117  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.117  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 18:15:21.117  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.117  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:21.117  1017  1130 D Tethering: InitialState.processMessage what=4
08-16 18:15:21.117  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.117  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:21.117  1017  1130 E Tethering: No numeric data
,08-16 18:15:21.127  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:21.127  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:21.127  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:21.127  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:21.127  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:21.127  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 18:15:21.127  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:21.127  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 18:15:21.127  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:21.127  1174  1174 D HotspotTile: updateTetherState():false, false
08-16 18:15:21.127  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:21.127  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:21.127  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-16 18:15:21.127  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:21.137  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:21.137  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:21.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:21.297  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.297  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:21.297  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:21.447  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:21.587  7468  7468 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-16 18:15:21.597  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 18:15:21.597  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:21.597  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:21.697  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-16 18:15:21.697  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 18:15:21.697  7188  7188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:21.707  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.707  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.707  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:21.707  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:21.707  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-16 18:15:21.717  1174  1174 D HotspotTile: onReceive : 1, 0
08-16 18:15:21.717  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:21.717  1711  2194 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:21.717  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:21.717  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:21.727  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:21.727  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:21.727  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:21.727  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:21.737  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:21.737  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:21.737  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:21.737  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 18:15:21.737  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:21.737  1629  1629 I Hs20UtilService: Starting #18
,08-16 18:15:21.737  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:21.747  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:22.137  1017  1096 V AlarmManager: waitForAlarm result :4
,08-16 18:15:22.147   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-16 18:15:22.147   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-16 18:15:22.167  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.167  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.167  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-16 18:15:22.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:22.417  1017  1045 D Tethering: interfaceRemoved wlan0
,08-16 18:15:22.417  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 18:15:22.667  1017  1045 D Tethering: interfaceRemoved p2p0
,08-16 18:15:22.667  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 18:15:23.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:23.447  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 18:15:23.687  6788  6873 D BluetoothAdapter: enable()
,08-16 18:15:23.687  1017  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:23.687  1017  1505 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 18:15:23.687  1017  1505 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:23.687  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:23.687  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.697  1017  1505 D SettingsProvider: name = bluetooth_on
,08-16 18:15:23.697  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.697  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.697  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 18:15:23.707  3181  3252 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 18:15:23.707  3181  3252 D BluetoothAdapterProperties: Setting state to 11
,08-16 18:15:23.707  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:15:23.707  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 18:15:23.707  3181  3252 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 18:15:23.707  3181  3252 D BluetoothAdapterService: Autoconnection is available 
,08-16 18:15:23.707  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-16 18:15:23.707  3181  3252 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 18:15:23.707  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:23.707  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:23.707  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:23.707  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:23.707  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-16 18:15:23.707  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10,
,08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:23.717  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:23.717  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:23.717  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.717  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-16 18:15:23.727  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:23.727  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:23.727  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-16 18:15:23.727  1854  1854 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:23.737  1017  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:23.737  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.737  1017  1516 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:23.737  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:23.737  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:23.737  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 18:15:23.737  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:23.737  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.737  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.747  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:23.747  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.747  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:23.747  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.747  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:23.757  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:23.757  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:23.757  3181  3181 D HeadsetService: Received start request. Starting profile...
08-16 18:15:23.757  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.757  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.757  3181  3181 D HeadsetService: start()
08-16 18:15:23.757  3181  3181 D HeadsetStateMachine: make
,08-16 18:15:23.757  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.757  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.757  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.767  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-16 18:15:23.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:23.767  1017  4213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.767  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 18:15:23.767  1017  4213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.767  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:23.767  1017  4213 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.767  1017  4213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.767  1017  4213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.767  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:23.767  1017  4211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 18:15:23.767  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 18:15:23.767  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 18:15:23.767  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.767  1017  4211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.767  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.767  3181  3181 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 18:15:23.777  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:23.777  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:23.777  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:23.777  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.777  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.777  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.777  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.777  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.787  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:23.787  1017  4215 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 18:15:23.787  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.787  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:23.787  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:23.787  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.787  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.787  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 18:15:23.787  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:23.787  1017  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 18:15:23.787  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 18:15:23.787  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.787  1017  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.787  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.797  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 18:15:23.797  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:23.797  3181  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:23.797  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.797  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 18:15:23.797  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.797  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.797  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.797  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.797  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.797  1017  1321 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 18:15:23.807  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:23.807  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.807  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.807  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.807  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.807  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.807  3181  3181 I bluedroid: get_profile_interface handsfree
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.807  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.807  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:23.807  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:23.807  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:23.807  3181  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 18:15:23.807  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:23.807  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:23.807  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:23.807  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:23.827  7608  7608 E Zygote  : MountEmulatedStorage(),
08-16 18:15:23.827  7608  7608 E Zygote  : v2
08-16 18:15:23.827  7608  7608 I libpersona: KNOX_SDCARD checking this for 10055,
08-16 18:15:23.827  7608  7608 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:23.827  7608  7608 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:23.827  1017  1478 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7608 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-16 18:15:23.827  7608  7608 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:23.837  7608  7608 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:23.837  3181  3181 E DualScoManager: Dual Sco Manager already instantiated
,08-16 18:15:23.837  3181  3181 I DualScoManager: Set HeadsetServiceHelper
08-16 18:15:23.837  3181  3181 D BluetoothAtMessage: createCMTIContentObservers
08-16 18:15:23.837  1017  1485 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 18:15:23.837  1017  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-16 18:15:23.837  1017  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:23.837  1017  1485 D SettingsProvider: selectionArgs: false
08-16 18:15:23.837  1017  1485 D SettingsProvider: selectionArgs: 1002
08-16 18:15:23.837  1017  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:23.837  1017  1485 D SettingsProvider: ret = -1
08-16 18:15:23.837  3181  7607 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 18:15:23.837  3181  3181 D HeadsetService: mStartError = false
08-16 18:15:23.837  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:23.837  3181  3181 D A2dpService: Received start request. Starting profile...
08-16 18:15:23.837  3181  3181 D A2dpService: start()
08-16 18:15:23.837  3181  3181 I bluedroid: get_profile_interface avrcp
,08-16 18:15:23.847  3181  7607 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 18:15:23.847  3181  7607 D HeadsetStateMachine: map size, before remove : 0
08-16 18:15:23.847  3181  7607 D HeadsetStateMachine: map size, after remove: 0
,08-16 18:15:23.847  3181  3181 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 18:15:23.847  3181  3181 D Avrcp   : Initialize Media Controller
08-16 18:15:23.847  3181  3181 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-16 18:15:23.847  3181  3181 E Avrcp   : getActiveSessions
08-16 18:15:23.847  3181  3181 D Avrcp   : pick active media Controller
08-16 18:15:23.847  3181  3181 D Avrcp   : Get the active Media Controller 
,08-16 18:15:23.857  7608  7608 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:23.857  3181  3181 I Avrcp   :  Updating now playing list upon AVRCP Start
08-16 18:15:23.857  3181  3181 D A2dpStateMachine: make
08-16 18:15:23.857  7608  7608 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:23.857  3181  7617 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 18:15:23.857  3181  3181 I bluedroid: get_profile_interface a2dp
,08-16 18:15:23.857  3181  7625 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:23.857  3181  3181 E bt-btif : warning : media task started media_task_refcnt 1 
08-16 18:15:23.857  3181  3181 D A2dpService: mStartError = false
08-16 18:15:23.857  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:23.857  3181  7621 D A2dpStateMachine: Enter Disconnected: -2
,08-16 18:15:23.867  3181  3181 D HidService: Received start request. Starting profile...
08-16 18:15:23.867  3181  3181 D HidService: start()
08-16 18:15:23.867  3181  3181 I bluedroid: get_profile_interface hidhost
08-16 18:15:23.867  3181  3181 D HidService: setHidService(): set to: null
08-16 18:15:23.867  3181  3181 D HidService: mStartError = false
08-16 18:15:23.867  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:23.867  3181  3181 D HealthService: Received start request. Starting profile...
08-16 18:15:23.867  3181  3181 D HealthService: start()
,08-16 18:15:23.867  3181  3181 I bluedroid: get_profile_interface health
08-16 18:15:23.867  3181  3181 D HealthService: mStartError = false
08-16 18:15:23.867  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:23.867  3181  3181 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 18:15:23.867  1454  1501 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 18:15:23.867  1454  1454 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 18:15:23.867  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 18:15:23.867  1454  1501 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 18:15:23.877  3181  3181 D PanService: Received start request. Starting profile...
08-16 18:15:23.877  3181  3181 D PanService: start()
08-16 18:15:23.877  3181  3181 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:15:23.877  3181  3181 I bluedroid: get_profile_interface pan
08-16 18:15:23.877  3181  3181 D PanService: mStartError = false
08-16 18:15:23.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:23.877  3181  3181 D BluetoothMapService: Received start request. Starting profile...,
08-16 18:15:23.877  3181  3181 D BluetoothMapService: start()
08-16 18:15:23.877  3181  7617 D BluetoothMediaBrowser: no now playing list
08-16 18:15:23.877  3181  7617 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 18:15:23.877  3181  3181 D BluetoothMapService: mStartError = false
08-16 18:15:23.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:23.877  3181  3181 D SapService: Received start request. Starting profile...
08-16 18:15:23.877  3181  3181 D SapService: start()
08-16 18:15:23.877  3181  3181 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 18:15:23.877  3181  3181 I bluedroid: get_profile_interface sap
08-16 18:15:23.877  3181  3181 D SapService: mStartError = false
08-16 18:15:23.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:23.877  3181  3181 D HeadsetStateMachine: Proxy object connected
08-16 18:15:23.877  3181  3181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-16 18:15:23.877  3181  3181 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 18:15:23.877  3181  7607 D HeadsetStateMachine: Disconnected process message: 11
08-16 18:15:23.877  3181  7607 D HeadsetStateMachine: Disconnected process message: 18
08-16 18:15:23.877  3181  3181 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-16 18:15:23.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 18:15:23.877  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 18:15:23.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 18:15:23.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 18:15:23.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 18:15:23.877  3181  7607 D HeadsetStateMachine: Disconnected process message: 10
08-16 18:15:23.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-16 18:15:23.877  3181  7607 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:15:23.877  3181  7607 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:23.887  7608  7608 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 18:15:23.897  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-16 18:15:23.897  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 18:15:23.897  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:15:23.897  3181  3252 I bluedroid: enable
,08-16 18:15:23.907  3181  3255 E bt-btif : Calling BTA_HhEnable
,08-16 18:15:23.907  3181  3255 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-16 18:15:23.907  3181  3255 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-16 18:15:23.907  3181  3255 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 18:15:23.907  3181  3255 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-16 18:15:23.907  3181  3255 E BluetoothServiceJni: populateRssiValuesNative
08-16 18:15:23.907  3181  3255 I bluedroid: getModelRssiValues
08-16 18:15:23.907  3181  3255 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 18:15:23.907  3181  3255 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:23.907  1017  1017 D SettingsProvider: name = bluetooth_name
,08-16 18:15:23.917  3181  3255 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-16 18:15:23.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:23.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:23.917  7608  7608 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-16 18:15:23.927  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:23.927  3181  3255 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:23.927  3181  3255 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:23.927  3181  3255 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-16 18:15:23.927  3181  3255 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-16 18:15:23.927  3181  3255 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-16 18:15:23.927  3181  3255 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 18:15:23.927  3181  3255 E bt-btif : JVenable fails
08-16 18:15:23.927  7608  7608 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 18:15:23.927  7608  7608 D UserAnalysis: Create SecureDbHelper
,08-16 18:15:23.927  5905  5905 D FactoryTest: Not factory mode
08-16 18:15:23.927  5905  5905 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 18:15:23.927  3181  3255 D bte_conf: Device ID record 1 : primary
08-16 18:15:23.927  3181  3255 D bte_conf:   vendorId            = 0075
08-16 18:15:23.927  3181  3255 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:23.927  3181  3255 D bte_conf:   product             = 0100
08-16 18:15:23.927  3181  3255 D bte_conf:   version             = 0200
08-16 18:15:23.927  3181  3255 D bte_conf:   clientExecutableURL = 
08-16 18:15:23.927  3181  3255 D bte_conf:   serviceDescription  = 
08-16 18:15:23.927  3181  3255 D bte_conf:   documentationURL    = 
08-16 18:15:23.927  5905  5905 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-16 18:15:23.927  5905  5905 D MTPRx   : still no open session command from host, so toast
,08-16 18:15:23.927  3181  3255 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 18:15:23.927  3181  3255 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 18:15:23.927  3181  3255 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 18:15:23.927  5905  5905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-16 18:15:23.927  5905  5905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-16 18:15:23.927  5905  5905 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118898
,08-16 18:15:23.927  1017  4213 E PersonaManagerService: inState():  stateMachine is null !!
08-16 18:15:23.927  1017  4213 I PersonaManagerService: PersonaId don't exist
08-16 18:15:23.927  1017  4213 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 18:15:23.937  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 18:15:23.937  3181  3252 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:15:23.937  3181  3252 D BluetoothAdapterProperties: State =  11
,08-16 18:15:23.937  1017  1506 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 18:15:23.937  7608  7608 D IntelligenceServiceApplication: onCreate()
,08-16 18:15:23.937  3181  3252 D BluetoothAdapterProperties: Setting state to 12
08-16 18:15:23.937  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 18:15:23.937  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:23.937  3181  3255 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:15:23.937  3181  3255 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:15:23.937  1017  1505 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 18:15:23.937  1017  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:23.937  1017  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:23.937  1017  1505 D SettingsProvider: selectionArgs: false
08-16 18:15:23.937  1017  1505 D SettingsProvider: selectionArgs: 1002
08-16 18:15:23.937  1017  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:23.937  1017  1505 D SettingsProvider: ret = -1
,08-16 18:15:23.937  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:23.937  3181  3252 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 18:15:23.947  1017  4213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:23.947  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:23.947  1017  4213 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.947  1017  4213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.947  1017  4213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-16 18:15:23.947  7608  7608 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 18:15:23.947  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:23.947  1017  4213 W ActivityManager: mDVFSHelper.acquire()
,08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:23.957  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:23.957  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:23.957  1017  4213 I ActivityManager: Killing 7144:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-16 18:15:23.967  1017  4213 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:23.977  1017  4213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 18:15:23.977  1017  4213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 18:15:23.977  1017  4213 D InputDispatcher: Focused application set to: xxxx
08-16 18:15:23.977  1017  4213 D InputDispatcher: Focus left window: 6788
,08-16 18:15:23.977  5905  5905 E MTPRx   : started activity for popup
,08-16 18:15:23.977  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 18:15:23.977  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:23.977  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 18:15:23.977  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.977  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.987  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 18:15:23.987  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.987  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.987  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.987  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:23.987  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 18:15:23.987  3181  3252 D BluetoothAdapterService: starting service from this receiver
,08-16 18:15:23.987  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:23.987  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:23.987  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:23.987  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:23.987  1174  2089 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:23.987  1174  2089 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:23.997  4621  4632 D Bluetoothsap: onBluetoothStateChange: up=true
,08-16 18:15:23.997  3181  3181 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-16 18:15:23.997  4621  4632 D Bluetoothsap: Binding service...
,08-16 18:15:23.997  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.997  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.997  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.997  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.997  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:23.997  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 18:15:23.997  3181  3252 I BluetoothAdapterState: Entering On State from state = 11
08-16 18:15:23.997  3181  3181 I BluetoothPbapService: Handler(): got msg=1
08-16 18:15:23.997  1017  4213 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:24.007  4621  4632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 18:15:24.007  3181  7633 V BluetoothPbapService: PBAP Service initSocket try: 0
08-16 18:15:24.007  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 18:15:24.007  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.007  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.007  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.007  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.007  4621  4632 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 18:15:24.007  3181  3193 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:24.017  3181  3193 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.017  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.017  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.017  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.017  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.017  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.017  3181  7633 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:24.017  3181  7633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:24.017  3181  7633 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 18:15:24.017  3181  7633 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.017  3181  7633 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:24.017  3181  7633 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@efd638d
,08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:24.017  4621  4621 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 18:15:24.017  4621  4621 D SapProfile: Bluetooth service connected
08-16 18:15:24.017  4621  4621 D Bluetoothsap: getConnectedDevices()
,08-16 18:15:24.017  3181  7633 D BluetoothSocket: channel: 19
08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:24.017  5905  5905 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:24.017  3181  7633 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 18:15:24.027  3181  3181 D BluetoothA2dp: Proxy object connected
08-16 18:15:24.027  3181  3181 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-16 18:15:24.027  1454  1494 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.027  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:24.027  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.027  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.027  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.027  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.037  1454  1494 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.037  4621  4629 D BluetoothPan: Binding service...
,08-16 18:15:24.037  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:24.037  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.037  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.037  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.037  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.037  4621  4632 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:24.037  4621  4632 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.037  4621  4629 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:15:24.037  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-16 18:15:24.037  4621  4621 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:24.037  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 18:15:24.037  4621  4621 D PanProfile: Bluetooth service connected
08-16 18:15:24.037  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.037  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.037  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.047  1454  1494 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.047  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.047  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.047  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.047  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.047  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.047  1454  1494 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.047  6788  6804 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.047  6788  6804 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:24.047  1017  1047 D BluetoothPan: Binding service...
08-16 18:15:24.047  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:24.047  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.047  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:24.047  5905  5905 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-16 18:15:24.047  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.047  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 18:15:24.047  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 18:15:24.047  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:24.047  4621  4632 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:24.047  1017  1017 D BluetoothA2dp: Proxy object connected
,08-16 18:15:24.047  4621  4632 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.057  1017  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 18:15:24.057  1017  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 18:15:24.057  1017  1505 D InputDispatcher: Focused application set to: xxxx
,08-16 18:15:24.057  1017  1505 D InputDispatcher: Focus entered window: 6788
,08-16 18:15:24.057  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 18:15:24.067  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:24.067  1017  1478 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 18:15:24.067  1017  1478 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3f130e70 attribute=null, token = android.os.BinderProxy@1e0e68f7
,08-16 18:15:24.067  4621  4621 D BluetoothMap: Proxy object connected
,08-16 18:15:24.067  4621  4621 D MapProfile: Bluetooth service connected
08-16 18:15:24.067  4621  4621 D BluetoothMap: getConnectedDevices()
,08-16 18:15:24.067  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.067  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.067  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.067  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.067  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.067  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.067  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.067  1479  1492 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.067  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.067  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.077  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.077  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:24.077  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.077  1479  1492 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.077  1465  1480 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.077  1465  1480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.077  4621  4621 D BluetoothA2dp: Proxy object connected
08-16 18:15:24.077  4621  4621 D A2dpProfile: Bluetooth service connected
,08-16 18:15:24.077  3181  3196 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.077  3181  3196 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.087  1017  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #17
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: android.os.DeadObjectException
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:15:24.087  1017  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 18:15:24.087   287   287 E SMD     : DCD OFF
08-16 18:15:24.087  4621  4629 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:15:24.087  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 18:15:24.087  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.087  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.087  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.087  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.097  1479  1490 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.097  1479  1490 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.097  4621  4621 D BluetoothPbap: Proxy object connected
08-16 18:15:24.097  4621  4621 D PbapServerProfile: Bluetooth service connected
,08-16 18:15:24.097  1454  7634 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.097  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:24.097  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.097  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.097  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.097  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.097  1454  7634 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.097  1711  1957 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:24.097  1711  1957 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.097  1685  1695 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.097  1685  1695 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.107  4621  4632 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.107  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:24.107  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.107  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.107  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.107  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.107  4621  4632 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:24.107  4621  4621 D HeadsetProfile: Bluetooth service connected
08-16 18:15:24.107  1454  1501 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:24.107  1454  1501 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.107  4621  4632 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 18:15:24.107  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 18:15:24.107  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.107  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.107  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.107  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.107  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 18:15:24.107  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 18:15:24.107  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:24.107  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-16 18:15:24.107  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:24.117  1454  1454 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f5e00ff, true
,08-16 18:15:24.117  5905  5905 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-16 18:15:24.117  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:24.117  1454  1454 D BluetoothHeadset: registerMessageListener
,08-16 18:15:24.127  1854  1854 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:24.127  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:24.127  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:24.127  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-16 18:15:24.127  5905  5905 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 18:15:24.127  5905  5905 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 18:15:24.127  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:24.137  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.137  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.137  3181  3256 D HeadsetService: registerMessageListener
,08-16 18:15:24.137  1017  1135 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:24.137  3181  3256 D HeadsetService: registerMessageListener
08-16 18:15:24.137  3181  7607 D HeadsetStateMachine: Disconnected process message: 70
08-16 18:15:24.137  1454  1454 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 18:15:24.137  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 18:15:24.137  3181  7607 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22468942
,08-16 18:15:24.137  1017  4213 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 18:15:24.137  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:24.137  4621  4621 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 18:15:24.137  4621  4621 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 18:15:24.137  4621  4621 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-16 18:15:24.147  4621  4621 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 18:15:24.147  1454  1454 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
08-16 18:15:24.147  1454  1454 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 18:15:24.147  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:24.147  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128,
,08-16 18:15:24.147  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:24.147  3181  7637 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 18:15:24.147  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:24.157  3181  7607 D HeadsetStateMachine: Disconnected process message: 9
08-16 18:15:24.157  3181  7607 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 18:15:24.157  6788  6788 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 18:15:24.157  6788  6788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-16 18:15:24.157  6788  6788 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 18:15:24.157  6788  6788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 18:15:24.157  1017  1504 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 18:15:24.157  1017  1504 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 18:15:24.157  1017  1504 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 18:15:24.157  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 18:15:24.157  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 18:15:24.157   282   726 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 18:15:24.157  3181  7637 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:24.157  3181  7637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:24.157   282   726 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 18:15:24.157   282   726 V voice   : voice_set_parameters: exit with code(-2)
08-16 18:15:24.157   282   726 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 18:15:24.157   282   726 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 18:15:24.157   282   726 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 18:15:24.157   282   726 V audio_hw_primary: adev_set_parameters: exit
08-16 18:15:24.157  3181  7607 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-16 18:15:24.157  3181  7637 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-16 18:15:24.157  3181  7637 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.157  3181  7637 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:24.157  3181  7637 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e6bd53
08-16 18:15:24.157  3181  7637 D BluetoothSocket: channel: 5
,08-16 18:15:24.167  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:24.167  1017  1516 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:24.167  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.167  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.167  1017  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.167  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:24.167  4621  4621 D BluetoothInputDevice: Proxy object connected
,08-16 18:15:24.177  4621  4621 D HidProfile: Bluetooth service connected
08-16 18:15:24.177  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:24.177  6788  6788 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 18:15:24.177  6788  6788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 18:15:24.187  6788  6788 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3af01396 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3a83c32a, 16908290=android.view.AbsSavedState$1@3a83c32a}, android:focusedViewId=100}]}]
,08-16 18:15:24.187   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-16 18:15:24.187  6788  6788 V ActivityThread: updateVisibility : ActivityRecord{2b22f088 token=android.os.BinderProxy@c2ea47a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 18:15:24.187  6788  6788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 18:15:24.187  6788  6788 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 18:15:24.187  6788  6788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-16 18:15:24.187  6788  6788 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c2ea47a time:119153
,08-16 18:15:24.187  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:24.187  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:24.197  1017  1504 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:24.197  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:24.207  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 18:15:24.207  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:24.207  3181  3181 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:24.207  1017  4214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:24.207  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.217  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.217  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.217  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.227  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 18:15:24.227  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:24.227  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:24.227  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:24.227  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:24.237  7640  7640 E Zygote  : MountEmulatedStorage()
,08-16 18:15:24.237  7640  7640 E Zygote  : v2
08-16 18:15:24.237  7640  7640 I libpersona: KNOX_SDCARD checking this for 10105
08-16 18:15:24.237  7640  7640 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:24.237  7640  7640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:24.237  7640  7640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:24.237  7640  7640 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 18:15:24.237  1017  1516 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7640 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-16 18:15:24.247  1017  1749 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:24.257  3181  7655 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 18:15:24.257  3181  7655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:24.257  3181  7655 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
,08-16 18:15:24.257  3181  7655 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.257  3181  7655 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:24.257  3181  7655 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3795dbaf
08-16 18:15:24.257  3181  7655 D BluetoothSocket: channel: 12
08-16 18:15:24.257  3181  7655 I BtOppRfcommListener: Accept thread started.
,08-16 18:15:24.267  7640  7640 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:24.267  7640  7640 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:24.377   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 18:15:24.377   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:24.377  7640  7662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 18:15:24.377   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 18:15:24.377   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:24.387  7640  7662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.k.d(PG:583)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  1017  4211 I ActivityManager: Killing 7247:com.sec.pcw.device/1000 (adj 15): empty #21
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:24.527  7640  7640 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:24.527  7640  7640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 18:15:24.597  7640  7669 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 18:15:24.607  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:24.607  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.607  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:24.607  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 18:15:26.707  6788  6873 D BluetoothAdapter: disable()
,08-16 18:15:26.707  1017  1506 D SettingsProvider: name = bluetooth_on
,08-16 18:15:26.717  3181  3252 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 18:15:26.717  3181  3252 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:26.717  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 18:15:26.717  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:26.717  3181  3252 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 18:15:26.717  1017  4211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:26.717  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.727  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.727  1017  4211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.727  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.727  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:26.727  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 18:15:26.727  3181  3252 D BluetoothAdapterService: terminating service from this receiver
,08-16 18:15:26.727  3181  3181 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 18:15:26.727  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 18:15:26.727  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c180bbc, channel: 19, state: LISTENING
,08-16 18:15:26.727  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c180bbc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@efd638d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29387745mSocket: android.net.LocalSocket@5bffe9a impl:android.net.LocalSocketImpl@376e83cb fd:FileDescriptor[80]
08-16 18:15:26.727  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.727  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.727  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.727  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5bffe9a impl:android.net.LocalSocketImpl@376e83cb fd:FileDescriptor[80]
,08-16 18:15:26.727  3181  3252 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 18:15:26.727  3181  3252 D BluetoothAdapterProperties: mDiscovering is false
,08-16 18:15:26.737  1017  4214 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:26.737  3181  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 18:15:26.747  4621  4621 D BluetoothPbap: Proxy object disconnected
08-16 18:15:26.747  4621  4621 D PbapServerProfile: Bluetooth service disconnected
,08-16 18:15:26.747  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:26.747  3181  3255 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:26.747  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 18:15:26.747  3181  3252 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 18:15:26.747  3181  3252 E bt-btif : cmd socket is not created
,08-16 18:15:26.757  3181  3252 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:15:26.757  3181  7655 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:26.757  3181  3257 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-16 18:15:26.757  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.757  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:26.757  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.757  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:26.757  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.767  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:26.767  6788  6788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.767  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:26.767  3181  3257 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:15:26.777  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:26.777  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-16 18:15:26.777  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:26.777  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:26.787  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:26.787  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:26.787  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-16 18:15:26.787  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:26.787  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 18:15:26.787  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:26.787  1017  1321 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:26.787  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:26.797  1854  1854 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:26.797  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:26.797  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7ee42c1, channel: 5, state: LISTENING
08-16 18:15:26.797  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7ee42c1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e6bd53, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b0f6a66mSocket: android.net.LocalSocket@28df91a7 impl:android.net.LocalSocketImpl@13bc1654 fd:FileDescriptor[82]
08-16 18:15:26.797  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28df91a7 impl:android.net.LocalSocketImpl@13bc1654 fd:FileDescriptor[82]
,08-16 18:15:26.797  3181  3181 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:26.797  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@edb49fd, channel: 12, state: LISTENING
08-16 18:15:26.797  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@edb49fd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3795dbaf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a97c6f2mSocket: android.net.LocalSocket@2269a143 impl:android.net.LocalSocketImpl@12ee43c0 fd:FileDescriptor[85]
08-16 18:15:26.797  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2269a143 impl:android.net.LocalSocketImpl@12ee43c0 fd:FileDescriptor[85]
,08-16 18:15:26.797  3181  7655 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 18:15:26.797  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:26.807  3181  3181 V BluetoothOppManager: cleanUp...
,08-16 18:15:26.807  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:26.807  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:26.807  1017  1506 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 18:15:26.807  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.807  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.807  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.807  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:26.817  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:26.817  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:26.817  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:26.827  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:26.827  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 18:15:26.947  1017  1043 W ActivityManager: mDVFSHelper.release()
,08-16 18:15:26.957  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 18:15:26.957  3181  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:26.957  3181  3252 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:26.957  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 18:15:26.957  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.957  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.957  1017  1135 W ActivityManager: userId = 0, bbcId = -10000,
08-16 18:15:26.957  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.957  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 18:15:26.957  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:26.957  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:26.957  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.957  3181  3181 D HeadsetService: Received stop request...Stopping profile...
,08-16 18:15:26.957  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.967  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.967  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.967  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.967  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-16 18:15:26.967  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:26.967  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:26.967  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 18:15:26.977  3181  3181 D A2dpService: Received stop request...Stopping profile...
,08-16 18:15:26.977  3181  7621 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:15:26.977  4621  4621 D HeadsetProfile: Bluetooth service disconnected
,08-16 18:15:26.977  1017  4211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.977  1017  4211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 18:15:26.977  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 18:15:26.977  1017  4211 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.977  1017  4211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.977  1017  4211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.977  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-16 18:15:26.977  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:26.977  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 18:15:26.977  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:26.977  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.977  1017  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.977  1017  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.977  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 18:15:26.977  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:26.987  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:26.987  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-16 18:15:26.987  1017  4214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.987  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2,
08-16 18:15:26.987  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 18:15:26.987  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.987  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.987  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:26.987  4621  4621 D BluetoothA2dp: Proxy object disconnected
,08-16 18:15:26.987  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.987  4621  4621 D A2dpProfile: Bluetooth service disconnected
08-16 18:15:26.987  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:26.987  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 18:15:26.987  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.987  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.987  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 18:15:26.987  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 18:15:26.987  3181  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:26.987  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.987  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.997  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.997  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.997  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:26.997  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:26.997  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:26.997  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-16 18:15:26.997  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-16 18:15:26.997  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:26.997  3181  3252 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:15:26.997  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 18:15:26.997  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:26.997  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 18:15:26.997  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 18:15:26.997  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 18:15:27.007  3181  3181 D HidService: Received stop request...Stopping profile...
08-16 18:15:27.007  3181  3181 D HidService: Stopping Bluetooth HidService
,08-16 18:15:27.007  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:15:27.007  3181  3181 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 18:15:27.007  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 18:15:27.007  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:27.007  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-16 18:15:27.007  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:27.007  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 18:15:27.007  3181  3181 D HealthService: Received stop request...Stopping profile...
08-16 18:15:27.007  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:27.007  4621  4621 D BluetoothInputDevice: Proxy object disconnected
08-16 18:15:27.007  4621  4621 D HidProfile: Bluetooth service disconnected
,08-16 18:15:27.007  3181  7625 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 18:15:27.007  3181  3181 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:15:27.007  3181  3181 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:27.007  3181  3181 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:27.007  3181  3181 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 18:15:27.017  3181  3181 D PanService: Received stop request...Stopping profile...
,08-16 18:15:27.017  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:27.017  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 18:15:27.017  3181  3181 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 18:15:27.017  4621  4621 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:27.017  4621  4621 D PanProfile: Bluetooth service disconnected
,08-16 18:15:27.017  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:27.017  3181  3181 D SapService: Received stop request...Stopping profile...
,08-16 18:15:27.017  3181  3181 D SapService: Stopping Bluetooth SapService
08-16 18:15:27.017  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:27.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:27.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:27.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:27.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.027  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:15:27.027  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 18:15:27.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:27.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:27.027  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:15:27.027  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 18:15:27.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 18:15:27.027  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 18:15:27.027  4621  4621 D BluetoothMap: Proxy object disconnected
08-16 18:15:27.027  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 18:15:27.027  3181  3181 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-16 18:15:27.027  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 18:15:27.027  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 18:15:27.027  4621  4621 D MapProfile: Bluetooth service disconnected
,08-16 18:15:27.027  4621  4621 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 18:15:27.027  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:15:27.027  3181  3252 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:27.027  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:27.027  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:27.027  3181  3252 D BluetoothAdapterService: updateAdapterState state is 10
08-16 18:15:27.027  4621  4621 D SapProfile: Bluetooth service disconnected
,08-16 18:15:27.027  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:27.027  1174  1189 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:27.027  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 18:15:27.027  3181  3252 I BluetoothAdapterState: Entering OffState
08-16 18:15:27.027  1174  1189 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:27.027  4621  4632 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 18:15:27.027  4621  4632 D Bluetoothsap: Unbinding service...
,08-16 18:15:27.037  3181  7636 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.037  4621  7554 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.037  4621  7554 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.037  4621  4632 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 18:15:27.037  6788  6804 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.037  6788  6804 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:27.037  6788  6804 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-16 18:15:27.037  6788  6804 D BluetoothLeAdvertiser: Exit stop advertising
08-16 18:15:27.037  6788  6804 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 18:15:27.037  6788  6804 D BluetoothLeScanner: Exiting stopAllScan
,08-16 18:15:27.037  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.037  4621  4629 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.037  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.037  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  1465  1499 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:27.047  1465  1499 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  7640  7656 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:27.047  7640  7656 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  3181  3196 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.047  3181  3196 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  4621  7554 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 18:15:27.047  1479  1492 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.047  1479  1492 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  1711  1957 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.047  1711  1957 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  1685  1695 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.047  1685  1695 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.047  1454  7634 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.047  1454  7634 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.057  4621  4629 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:15:27.057  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.057  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,08-16 18:15:27.057  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:27.057  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:27.067  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:27.067  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-16 18:15:27.067  1017  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:27.067  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 18:15:27.067  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 18:15:27.067  1854  1854 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:27.067  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.077  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:27.077  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:27.077  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:27.077  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 18:15:27.077  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.077  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.087  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.087  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:27.087  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:27.087   287   287 E SMD     : DCD OFF
,08-16 18:15:27.097  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:27.097  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:27.097  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.097  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 18:15:27.817  1017  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:28.007  1017  3327 D SSRM:n  : SIOP:: AP = 340
,08-16 18:15:29.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:29.727  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:15:29.727  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:30.097   287   287 E SMD     : DCD OFF
,08-16 18:15:30.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:31.077  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:31.077  1017  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 18:15:31.087  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 18:15:31.087  1017  1029 D BatteryService: stay LED for charging
,08-16 18:15:31.087  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:31.087  1017  1017 I MotionRecognitionService: Plugged
,08-16 18:15:31.087  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:31.087  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 18:15:31.087  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:31.097  1438  1438 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 18:15:31.097  1438  1438 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 18:15:31.117  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 18:15:31.117  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-16 18:15:31.117  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:31.117  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:31.117  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 18:15:31.197   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:32.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:32.727  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 18:15:32.727  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c0d151b added. We now have 6 listener(s)
08-16 18:15:32.727  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:32.727  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:32.727  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2be266b8 added. We now have 7 listener(s)
08-16 18:15:32.727  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:32.727  6788  6873 I System.out: IsBluetoothEnabled
,08-16 18:15:32.727  6788  6873 D BluetoothAdapter: disable()
08-16 18:15:32.727  1017  1516 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-16 18:15:32.737  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:32.737  6788  6873 D BluetoothAdapter: enable()
,08-16 18:15:32.737  1017  1505 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 18:15:32.737  1017  1505 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:32.737  1017  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:32.737  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:32.737  1017  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:32.747  1017  1505 D SettingsProvider: name = bluetooth_on
,08-16 18:15:32.757  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:32.757  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:32.757  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,08-16 18:15:32.767  3181  3252 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-16 18:15:32.767  3181  3252 D BluetoothAdapterProperties: Setting state to 11
08-16 18:15:32.767  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:15:32.767  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:32.767  3181  3252 D BluetoothAdapterService: updateAdapterState state is 11,
08-16 18:15:32.767  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:32.767  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-16 18:15:32.767  3181  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-16 18:15:32.767  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:32.767  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:32.767  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:32.767  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:32.767  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-16 18:15:32.777  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.777  1174  1174 D BluetoothTile:  getBluetoothState : 11
08-16 18:15:32.777  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:32.777  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 18:15:32.777  1854  1854 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:32.777  1017  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:32.777  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:32.777  1017  4215 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:32.777  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:32.787  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:32.787  1017  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.787  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.787  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:32.787  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.787  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.787  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:32.787  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:32.787  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 18:15:32.787  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.787  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.787  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:32.787  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.787  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.797  3181  3181 D HeadsetService: Received start request. Starting profile...
08-16 18:15:32.797  3181  3181 D HeadsetService: start()
08-16 18:15:32.797  3181  3181 D HeadsetStateMachine: make
,08-16 18:15:32.797  3181  3181 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 18:15:32.797  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-16 18:15:32.797  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:32.797  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 18:15:32.797  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:32.797  1017  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 18:15:32.797  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.807  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:32.807  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.807  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 18:15:32.807  1017  4214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:32.807  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 18:15:32.807  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.807  1017  1505 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 18:15:32.807  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:32.807  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-16 18:15:32.807  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:32.807  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:32.807  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-16 18:15:32.807  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 18:15:32.807  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.807  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.807  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 18:15:32.807  3181  3181 I bluedroid: get_profile_interface handsfree
,08-16 18:15:32.807  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.807  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 18:15:32.817  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.817  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.817  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.817  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:32.817  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:32.817  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:32.817  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:32.817  1017  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.817  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 18:15:32.817  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.817  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.817  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:32.827  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:32.827  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:32.827  3181  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:32.827  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:32.827  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 18:15:32.827  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.827  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.827  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.827  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.827  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 18:15:32.837  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:32.837  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.837  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.837  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.837  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.837  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:32.837  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.837  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.837  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:32.837  3181  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:32.837  3181  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:32.837  3181  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 18:15:32.837  3181  3181 E DualScoManager: Dual Sco Manager already instantiated
08-16 18:15:32.837  3181  3181 I DualScoManager: Set HeadsetServiceHelper
08-16 18:15:32.837  3181  3181 D BluetoothAtMessage: createCMTIContentObservers
,08-16 18:15:32.837  1017  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 18:15:32.837  1017  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.837  1017  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.837  1017  1504 D SettingsProvider: selectionArgs: false
08-16 18:15:32.837  1017  1504 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.837  1017  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.837  1017  1504 D SettingsProvider: ret = -1
,08-16 18:15:32.847  3181  7686 D HeadsetStateMachine: Enter Disconnected: -2,
,08-16 18:15:32.847  3181  3181 D HeadsetService: mStartError = false
08-16 18:15:32.847  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:32.847  3181  3181 D A2dpService: Received start request. Starting profile...
08-16 18:15:32.847  3181  3181 D A2dpService: start()
08-16 18:15:32.847  3181  3181 I bluedroid: get_profile_interface avrcp
,08-16 18:15:32.847  3181  7686 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 18:15:32.847  3181  7686 D HeadsetStateMachine: map size, before remove : 0,
08-16 18:15:32.847  3181  7686 D HeadsetStateMachine: map size, after remove: 0
,08-16 18:15:32.847  3181  3181 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
08-16 18:15:32.847  3181  3181 D Avrcp   : Initialize Media Controller
08-16 18:15:32.847  3181  3181 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-16 18:15:32.847  3181  3181 E Avrcp   : getActiveSessions,
08-16 18:15:32.847  3181  3181 D Avrcp   : pick active media Controller,
08-16 18:15:32.847  3181  3181 D Avrcp   : Get the active Media Controller ,
,08-16 18:15:32.857  3181  3181 I Avrcp   :  Updating now playing list upon AVRCP Start
08-16 18:15:32.857  3181  7687 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 18:15:32.857  3181  3181 D A2dpStateMachine: make
,08-16 18:15:32.867  3181  3181 I bluedroid: get_profile_interface a2dp
,08-16 18:15:32.867  3181  7689 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:32.867  3181  3181 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 18:15:32.867  3181  3181 D A2dpService: mStartError = false
08-16 18:15:32.867  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:32.867  3181  7688 D A2dpStateMachine: Enter Disconnected: -2
08-16 18:15:32.867  3181  3181 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 18:15:32.867  1454  7634 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 18:15:32.867  1454  1454 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 18:15:32.867  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 18:15:32.867  1454  7634 I Telecom : BluetoothPhoneService: Result of Message : true
08-16 18:15:32.867  3181  3181 D HidService: Received start request. Starting profile...
08-16 18:15:32.867  3181  3181 D HidService: start()
08-16 18:15:32.867  3181  3181 I bluedroid: get_profile_interface hidhost
08-16 18:15:32.867  3181  3181 D HidService: setHidService(): set to: null
08-16 18:15:32.867  3181  3181 D HidService: mStartError = false
08-16 18:15:32.867  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:32.867  3181  3181 D HeadsetStateMachine: Proxy object connected
08-16 18:15:32.867  3181  3181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 18:15:32.867  3181  7686 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:32.867  3181  3181 D HealthService: Received start request. Starting profile...
08-16 18:15:32.867  3181  3181 D HealthService: start()
,08-16 18:15:32.877  3181  3181 I bluedroid: get_profile_interface health
08-16 18:15:32.877  3181  3181 D HealthService: mStartError = false
08-16 18:15:32.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28,
08-16 18:15:32.877  3181  3181 D PanService: Received start request. Starting profile...
08-16 18:15:32.877  3181  3181 D PanService: start()
08-16 18:15:32.877  3181  3181 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:15:32.877  3181  3181 I bluedroid: get_profile_interface pan
08-16 18:15:32.877  3181  3181 D PanService: mStartError = false
08-16 18:15:32.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:32.877  3181  3181 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 18:15:32.877  3181  3181 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-16 18:15:32.877  3181  7687 D BluetoothMediaBrowser: no now playing list
08-16 18:15:32.877  3181  7686 D HeadsetStateMachine: Disconnected process message: 18
08-16 18:15:32.877  3181  7687 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 18:15:32.877  3181  3181 D BluetoothMapService: Received start request. Starting profile...
08-16 18:15:32.877  3181  3181 D BluetoothMapService: start()
,08-16 18:15:32.877  3181  3181 D BluetoothMapService: mStartError = false
08-16 18:15:32.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:32.877  3181  3181 D SapService: Received start request. Starting profile...
08-16 18:15:32.877  3181  3181 D SapService: start()
08-16 18:15:32.877  3181  3181 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-16 18:15:32.877  3181  3181 I bluedroid: get_profile_interface sap
08-16 18:15:32.877  3181  3181 D SapService: mStartError = false
08-16 18:15:32.877  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
08-16 18:15:32.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 18:15:32.877  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 18:15:32.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 18:15:32.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 18:15:32.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 18:15:32.877  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 18:15:32.877  3181  7686 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:32.877  3181  7686 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 18:15:32.887  3181  7686 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:32.897  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 18:15:32.897  3181  3181 E BluetoothAdapterService(877477416): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 18:15:32.897  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 18:15:32.897  3181  3252 I bluedroid: enable
,08-16 18:15:32.897  3181  3255 E bt-btif : Calling BTA_HhEnable
,08-16 18:15:32.907  3181  3255 E bt-btif : BTM_SEC_REG[11]: id 330xb6, service name [] (up to 21 chars saved)
08-16 18:15:32.907  3181  3255 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 18:15:32.907  3181  3255 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-16 18:15:32.907  3181  3255 E BluetoothServiceJni: populateRssiValuesNative
08-16 18:15:32.907  3181  3255 I bluedroid: getModelRssiValues
08-16 18:15:32.907  3181  3255 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-16 18:15:32.907  1017  1017 D SettingsProvider: name = bluetooth_name
,08-16 18:15:32.907  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:32.907  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:32.907  3181  3255 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-16 18:15:32.907  3181  3255 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-16 18:15:32.907  3181  3255 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-16 18:15:32.907  3181  3255 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 18:15:32.907  3181  3255 E bt-btif : JVenable fails
,08-16 18:15:32.917  3181  3255 D bte_conf: Device ID record 1 : primary
08-16 18:15:32.917  3181  3255 D bte_conf:   vendorId            = 0075
,08-16 18:15:32.917  3181  3255 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:32.917  3181  3255 D bte_conf:   product             = 0100
08-16 18:15:32.917  3181  3255 D bte_conf:   version             = 0200
,08-16 18:15:32.917  3181  3255 D bte_conf:   clientExecutableURL = 
,08-16 18:15:32.917  3181  3255 D bte_conf:   serviceDescription  = 
08-16 18:15:32.917  3181  3255 D bte_conf:   documentationURL    = 
08-16 18:15:32.917  3181  3255 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 18:15:32.917  3181  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 18:15:32.917  3181  3252 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:15:32.917  3181  3252 D BluetoothAdapterProperties: State =  11
,08-16 18:15:32.917  1017  4213 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:32.917  3181  3255 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 18:15:32.917  3181  3255 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 18:15:32.917  3181  3252 D BluetoothAdapterProperties: Setting state to 12
08-16 18:15:32.917  3181  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:32.927  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:32.927  3181  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:32.927  3181  3255 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:15:32.927  3181  3255 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:15:32.927  1017  1485 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 18:15:32.927  1017  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.927  1017  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.927  1017  1485 D SettingsProvider: selectionArgs: false
08-16 18:15:32.927  1017  1485 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.927  1017  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.927  1017  1485 D SettingsProvider: ret = -1
,08-16 18:15:32.927  3181  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:32.927  3181  3252 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 18:15:32.927  1017  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.927  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.927  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:32.927  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:32.937  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.937  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.937  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:32.937  3181  3252 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:32.937  3181  3252 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-16 18:15:32.937  3181  3252 D BluetoothAdapterService: starting service from this receiver
,08-16 18:15:32.937  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:32.937  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 18:15:32.937  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:32.937  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:32.937  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:32.937  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:32.937  3181  3252 I BluetoothAdapterState: Entering On State from state = 11
,08-16 18:15:32.937  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:32.947  3181  3181 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 18:15:32.947  3181  3181 I BluetoothPbapService: Handler(): got msg=1
,08-16 18:15:32.947  1017  1749 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:32.947  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:32.947  1174  1949 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:32.947  1174  1949 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:32.947  4621  7554 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 18:15:32.947  4621  7554 D Bluetoothsap: Binding service...
,08-16 18:15:32.957  4621  7554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 18:15:32.957  3181  7694 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 18:15:32.957  3181  7694 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 18:15:32.957  3181  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:32.967  3181  7694 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 18:15:32.967  3181  7694 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:32.967  3181  7694 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:32.967  3181  7694 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@352badaa
,08-16 18:15:32.967  3181  7694 D BluetoothSocket: channel: 19
08-16 18:15:32.967  3181  7694 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 18:15:33.087   287   287 E SMD     : DCD OFF
08-16 18:15:33.097  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 18:15:33.097  1017  1047 I art     : Explicit concurrent mark sweep GC freed 57035(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.295ms total 139.317ms
08-16 18:15:33.097  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-16 18:15:33.097  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.097  4621  7554 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 18:15:33.097  3181  3196 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:33.097  3181  3196 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.097  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:33.097  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.097  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.097  1454  1501 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.097  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.097  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.097  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.097  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.097  1454  1501 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:33.097  4621  4629 D BluetoothPan: Binding service...
,08-16 18:15:33.107  4621  4621 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 18:15:33.107  4621  4621 D SapProfile: Bluetooth service connected
08-16 18:15:33.107  4621  4621 D Bluetoothsap: getConnectedDevices()
,08-16 18:15:33.107  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:33.107  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.107  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.107  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.107  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.107  4621  7554 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.107  4621  7554 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:33.107  3181  3181 D BluetoothA2dp: Proxy object connected
,08-16 18:15:33.107  3181  3181 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 18:15:33.107  4621  4629 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 18:15:33.107  4621  4621 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:33.107  4621  4621 D PanProfile: Bluetooth service connected
,08-16 18:15:33.117  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 18:15:33.117  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.117  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.117  1454  1494 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.117  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.117  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.117  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.117  1454  1494 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:33.117  6788  6798 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.117  6788  6798 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.117  1017  1047 D BluetoothPan: Binding service...
08-16 18:15:33.117  4621  4621 D BluetoothMap: Proxy object connected
08-16 18:15:33.117  4621  4621 D MapProfile: Bluetooth service connected
08-16 18:15:33.117  4621  4621 D BluetoothMap: getConnectedDevices()
08-16 18:15:33.117  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:33.117  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.117  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:33.117  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:33.117  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 18:15:33.117  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:33.117  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.117  4621  7554 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:33.117  1017  1017 D BluetoothA2dp: Proxy object connected
,08-16 18:15:33.117  4621  7554 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.117  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:33.117  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.117  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.117  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.117  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.117  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.117  4621  4621 D BluetoothA2dp: Proxy object connected
08-16 18:15:33.117  4621  4621 D A2dpProfile: Bluetooth service connected
,08-16 18:15:33.127  1479  1764 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.127  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.127  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 18:15:33.127  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.127  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.127  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.127  1479  1764 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:33.127  1465  1480 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.127  1465  1480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:33.127  7640  7657 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.127  7640  7657 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.127  3181  7636 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.127  3181  7636 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.127  4621  4632 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:15:33.127  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-16 18:15:33.127  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 18:15:33.127  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.127  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.127  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.127  1479  2137 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:33.127  1479  2137 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.127  4621  4621 D BluetoothPbap: Proxy object connected
08-16 18:15:33.127  4621  4621 D PbapServerProfile: Bluetooth service connected
,08-16 18:15:33.127  1454  1501 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.137  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.137  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.137  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.137  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.137  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 18:15:33.137  1454  1501 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:33.137  1711  1731 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:33.137  1711  1731 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.137  1685  4212 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:33.137  1685  4212 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:33.137  4621  7554 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.137  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.137  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.137  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.137  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.137  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.137  4621  4621 D HeadsetProfile: Bluetooth service connected
,08-16 18:15:33.137  4621  7554 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:33.137  1454  1494 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.137  1454  1494 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.137  4621  4632 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 18:15:33.137  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 18:15:33.137  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.147  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.147  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.147  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-16 18:15:33.147  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 18:15:33.147  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 18:15:33.147  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:33.147  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-16 18:15:33.147  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-16 18:15:33.147  4621  4621 D BluetoothInputDevice: Proxy object connected
08-16 18:15:33.147  4621  4621 D HidProfile: Bluetooth service connected
,08-16 18:15:33.157  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:33.157  1454  1454 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@238e4ecc, true
,08-16 18:15:33.157  1454  1454 D BluetoothHeadset: registerMessageListener
,08-16 18:15:33.157  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:33.157  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.157  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-16 18:15:33.157  1854  1854 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:33.167  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:33.167  3181  3256 D HeadsetService: registerMessageListener
,08-16 18:15:33.167  3181  3256 D HeadsetService: registerMessageListener
08-16 18:15:33.167  3181  7686 D HeadsetStateMachine: Disconnected process message: 70
08-16 18:15:33.167  3181  7686 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1e70c911
,08-16 18:15:33.167  1454  1454 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 18:15:33.167  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 18:15:33.167  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:33.167  4621  4621 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.167  1454  1454 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 18:15:33.167  1454  1454 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 18:15:33.167  1454  1454 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 18:15:33.167  3181  7686 D HeadsetStateMachine: Disconnected process message: 9
,08-16 18:15:33.167  4621  4621 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 18:15:33.167  4621  4621 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 18:15:33.167  4621  4621 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 18:15:33.167  4621  4621 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 18:15:33.167  3181  7695 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 18:15:33.167  3181  7686 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 18:15:33.167  1017  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:33.177  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 18:15:33.177  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:33.177   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 18:15:33.177   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 18:15:33.177   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-16 18:15:33.177   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-16 18:15:33.177   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 18:15:33.177   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 18:15:33.177   282   282 V audio_hw_primary: adev_set_parameters: exit
08-16 18:15:33.177  3181  7686 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 18:15:33.177  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:33.177  4621  4621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 18:15:33.177  1017  4214 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 18:15:33.177  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.177  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.177  1017  4214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.177  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:33.177  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:33.187  4621  4621 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:33.187  3181  7695 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:33.187  3181  7695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:33.187  1685  1685 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:33.187  3181  7695 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-16 18:15:33.187  3181  7695 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:33.187  3181  7695 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:33.187  3181  7695 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@276efa76
08-16 18:15:33.187  3181  7695 D BluetoothSocket: channel: 5
,08-16 18:15:33.187   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:33.197  4621  4621 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:33.197  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:33.197  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 18:15:33.207  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@344d3e28
,08-16 18:15:33.207  3181  3181 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:33.207  1017  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.207  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.207  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.207  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.207  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.217  1017  4211 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:33.227  3181  7700 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:33.227  3181  7700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:33.227  3181  7700 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[88]}
08-16 18:15:33.227  3181  7700 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:33.227  3181  7700 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:33.227  3181  7700 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15c84802
08-16 18:15:33.227  3181  7700 D BluetoothSocket: channel: 12
08-16 18:15:33.227  3181  7700 I BtOppRfcommListener: Accept thread started.
,08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:33.767  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:33.767  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:33.767  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:33.767  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1501fc91 added. We now have 8 listener(s)
08-16 18:15:33.767  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:33.767  1017  4213 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:33.767  1017  4213 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 18:15:33.767  1017  4213 D SecContentProvider2: mCursor = null
,08-16 18:15:33.777  1017  4213 D WifiService: setWifiEnabled: false pid=6788, uid=10170
,08-16 18:15:33.777  1017  4213 D SettingsProvider: name = wifi_on
,08-16 18:15:33.777  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:33.777  1017  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:33.777  1017  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 18:15:33.777  1017  1478 D SecContentProvider2: mCursor = null
,08-16 18:15:33.787  1017  1478 D WifiService: setWifiEnabled: true pid=6788, uid=10170
,08-16 18:15:33.787  1017  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:33.787  1017  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:33.787  1017  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6788, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:33.787  1017  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 18:15:33.787  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:33.787  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:33.787  1017  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:33.787  1017  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:33.787  1017  1478 D SettingsProvider: name = wifi_on
,08-16 18:15:33.787  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 18:15:34.127  1017  1045 D Tethering: interfaceAdded wlan0
,08-16 18:15:34.127  1017  1130 E Tethering: No numeric data
,08-16 18:15:34.127  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-16 18:15:34.127  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:34.127  1017  1130 D Tethering: clearTetheredNotification()
08-16 18:15:34.127  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:34.127  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:34.137  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:34.137  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:34.137  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:34.137  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:34.137  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-16 18:15:34.147  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:34.147  1017  1130 D Tethering: InitialState.processMessage what=4
,08-16 18:15:34.147  1017  1130 E Tethering: No numeric data
,08-16 18:15:34.147  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:34.147  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:34.147  1017  1045 D Tethering: interfaceAdded p2p0
,08-16 18:15:34.147  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 18:15:34.147  1017  1124 V NetworkStats: performPollLocked() took 20ms
08-16 18:15:34.147  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:34.157  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:34.157  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 18:15:34.157  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.157  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:34.157  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:34.157  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:34.157  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:34.157  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:34.157  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.157  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:34.167  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:34.167   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-16 18:15:34.167   277  1016 D SoftapController: Softap fwReload - Ok
,08-16 18:15:34.167  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-16 18:15:34.167  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:34.167   277  1016 D CommandListener: Setting iface cfg
08-16 18:15:34.167   277  1016 D CommandListener: Trying to bring down wlan0
,08-16 18:15:34.167  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:34.167  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:34.167   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:34.177  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 18:15:34.177  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-16 18:15:34.187   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 18:15:34.197  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:34.207  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:34.207  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:34.207  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:34.207  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:34.207  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:34.207  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:34.207  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:34.207  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 18:15:34.207  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:34.207  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:34.217  1174  1174 D HotspotTile: onReceive : 2, 0
,08-16 18:15:34.217  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:34.217  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:34.237  1017  4215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:34.237  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-16 18:15:34.237  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.237  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.237  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:34.237  7711  7711 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-16 18:15:34.237  7711  7711 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:15:34.237  7711  7711 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-16 18:15:34.237  1629  1629 I Hs20UtilService: Starting #19
08-16 18:15:34.237  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:34.247  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:34.247  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:34.247  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:34.247  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:34.247  7711  7711 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-16 18:15:34.257   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7711
08-16 18:15:34.257   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 18:15:34.257  7711  7711 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 18:15:34.257  7711  7711 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:34.257  7711  7711 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 18:15:34.257  7711  7711 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-16 18:15:34.257   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7711
08-16 18:15:34.257   344   344 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 18:15:34.407   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-16 18:15:34.407  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-16 18:15:34.457  7711  7711 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 18:15:34.457  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 18:15:34.467  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-16 18:15:34.467   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7711
08-16 18:15:34.467   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 18:15:34.467  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 18:15:34.467  7711  7711 I wpa_supplicant: ssSupport state is = 1,
08-16 18:15:34.467  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:34.467  7711  7711 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:34.467  7711  7711 E wpa_supplicant: SIM READ ERROR
08-16 18:15:34.467  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 18:15:34.467  7711  7711 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:34.467  7711  7711 E wpa_supplicant: SIM READ ERROR
08-16 18:15:34.467  7711  7711 I wpa_supplicant: Blacklist: Clear (all) 
08-16 18:15:34.467  7711  7711 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:34.467  7711  7711 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-16 18:15:34.467  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:34.467  7711  7711 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 18:15:34.467  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:34.467  7711  7711 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 18:15:34.477  7711  7711 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-16 18:15:34.477  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 18:15:34.477  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:34.477  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:34.617  7711  7711 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 18:15:34.757  7711  7711 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 18:15:34.757  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 18:15:34.767  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 18:15:34.767   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7711
08-16 18:15:34.767   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-16 18:15:34.777  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 18:15:34.777  7711  7711 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:34.777  7711  7711 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 18:15:34.777  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 18:15:34.787  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 18:15:34.787   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7711
08-16 18:15:34.787   344   344 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 18:15:34.787  7711  7711 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 18:15:34.787  7711  7711 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:34.797  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.787  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 18:15:34.787  7711  7711 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:34.787  7711  7711 E wpa_supplicant: SIM READ ERROR
08-16 18:15:34.787  7711  7711 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:34.787  7711  7711 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:34.787  7711  7711 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 18:15:34.797  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.797  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.797  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:34.797  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:34.797  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:34.927  7711  7711 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 18:15:34.927  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 18:15:35.027  7711  7711 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-16 18:15:35.027  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 18:15:35.027  7711  7711 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:35.037  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-16 18:15:35.037  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 18:15:35.037  7711  7711 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-16 18:15:35.037  7711  7711 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:35.037  7711  7711 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:35.037  7711  7711 E wpa_supplicant: SIM READ ERROR
08-16 18:15:35.037  7711  7711 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:35.057  7711  7711 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 18:15:35.067  7711  7711 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 18:15:35.067  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-16 18:15:35.087  4621  4621 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:35.087  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.087  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.087  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:35.087  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 18:15:35.087  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:35.087  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:35.087  1174  1174 D HotspotTile: onReceive : 3, 0
,08-16 18:15:35.097  1017  4215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:35.097  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:35.097  1017  1127 E WifiConfigStore: Not a HS20
08-16 18:15:35.097  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:35.097  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:35.097  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:35.097  6788  6788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:35.097  1629  1629 I Hs20UtilService: Starting #20
,08-16 18:15:35.097  1629  1658 I Hs20UtilService: Message received 5011
,08-16 18:15:35.107  6788  6788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:35.107  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:35.107  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 18:15:35.107  7010  7010 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 18:15:35.107  7010  7010 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:35.107  7010  7010 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:35.117  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13],
08-16 18:15:35.117  7711  7711 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON,
08-16 18:15:35.117  7711  7711 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-16 18:15:35.117  7711  7711 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-16 18:15:35.117  7711  7711 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-16 18:15:35.117  7711  7711 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 18:15:35.117  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 18:15:35.117  7711  7711 I wpa_supplicant: First Scan Start,
08-16 18:15:35.117  7711  7711 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 18:15:35.127  7188  7188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-16 18:15:35.127  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-16 18:15:35.127  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:35.127  1017  1127 I WifiNative-HAL: startHal
,08-16 18:15:35.127  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ebf288c
08-16 18:15:35.127  1017  1127 I WifiNative-HAL: Could not start hal
,08-16 18:15:35.137  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 18:15:35.137  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:35.137  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.137  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:35.137  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 18:15:35.137  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 18:15:35.137  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-16 18:15:35.137   277  1016 D CommandListener: Setting iface cfg
08-16 18:15:35.137  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:35.137  1017  1151 I WifiNative-HAL: startHal
08-16 18:15:35.137  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dab49bc
08-16 18:15:35.137  1017  1151 I WifiNative-HAL: Could not start hal
08-16 18:15:35.137  1017  1151 E WifiScanningService: could not start HAL
08-16 18:15:35.137   277  1016 D CommandListener: Trying to bring up p2p0
08-16 18:15:35.137  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-16 18:15:35.137  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 18:15:35.137  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:35.137  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:35.137  1017  1126 D WifiP2pService: P2pEnablingState
08-16 18:15:35.137  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-16 18:15:35.137  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 18:15:35.137  1017  1126 D WifiP2pService: P2p socket connection successful
08-16 18:15:35.137  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:35.137  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:35.137  1017  1126 D WifiP2pService: P2pEnabledState
08-16 18:15:35.137  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:35.137  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-16 18:15:35.137  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 18:15:35.137  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:35.147  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 18:15:35.147  7711  7711 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 18:15:35.147  7711  7711 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:35.147  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 18:15:35.147  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-16 18:15:35.147  1017  1048 D WifiDisplayController: disconnect
08-16 18:15:35.147  1017  1048 D WifiDisplayController: updateConnection
08-16 18:15:35.147  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:35.147  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:35.147  7711  7711 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-16 18:15:35.147  1017  1127 E WifiStateMachine: Failed to set frequency band 0
08-16 18:15:35.147  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:35.147  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:35.147  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:35.147  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:35.147  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 18:15:35.157  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:35.157  1017  1127 D SecContentProvider2: mCursor = null
08-16 18:15:35.157  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-16 18:15:35.157  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:15:35.157  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:35.157  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:35.157  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:35.157  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 18:15:35.157  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:35.157  1017  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:35.157  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:35.157  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
08-16 18:15:35.157  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 18:15:35.157  1017  1126 D WifiP2pService: DeviceAddress: 0a:75:42
08-16 18:15:35.157  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:35.157  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  secondary type: null
,08-16 18:15:35.157  1017  1048 D WifiDisplayController:  wps: 0
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  grpcapab: 0
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  devcapab: 0
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  status: 3
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  wfdInfo: null
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-16 18:15:35.157  1017  1048 D WifiDisplayController:  SConnectInfo : null
08-16 18:15:35.157  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:35.167  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:35.167  7556  7556 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 18:15:35.167  7556  7556 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:35.167  7229  7229 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:35.177  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 18:15:35.177  1017  1126 D WifiP2pService: InactiveState
,08-16 18:15:35.177  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:35.177  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:35.177  7711  7711 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-16 18:15:35.177  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:35.177  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:35.817  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:35.817  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 18:15:35.827  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 18:15:35.827  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 18:15:35.827  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3af01396 Bundle[{}]
,08-16 18:15:35.827  6788  6873 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:15:35.827  6788  6873 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 18:15:35.837  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 18:15:35.837  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 18:15:35.837  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 18:15:35.837  6788  6873 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 18:15:35.837  6788  6873 I System.out: Running OutgoingSocketThread
,08-16 18:15:35.847  6788  7720 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1366)
,08-16 18:15:35.847  6788  7720 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40055
,08-16 18:15:35.847  6788  7720 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 18:15:36.097   287   287 E SMD     : DCD OFF
,08-16 18:15:36.307  7711  7711 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
,08-16 18:15:36.317  7711  7711 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-16 18:15:36.317  1017  7717 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-16 18:15:36.317  7711  7711 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 18:15:36.317  7711  7711 I wpa_supplicant: Trying to associate with  'G700'
,08-16 18:15:36.317  7711  7711 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-16 18:15:36.317  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-16 18:15:36.337  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:36.337  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:36.437  7711  7711 E wpa_supplicant: Cmd 35605 not handled
08-16 18:15:36.437  7711  7711 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 18:15:36.437  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 18:15:36.437  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:36.437  7711  7711 I wpa_supplicant: Associated with F4.99.3E
08-16 18:15:36.437  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:36.437  7711  7711 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 18:15:36.437  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:36.437  7711  7711 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 18:15:36.437  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 18:15:36.437  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:36.437  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:36.437  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:36.437  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:36.437  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:36.437  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:36.437  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 18:15:36.437  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:36.437  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 18:15:36.447  1017  1130 E Tethering: No numeric data,
,08-16 18:15:36.447  7711  7711 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-16 18:15:36.447  7711  7711 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 18:15:36.447  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:36.447  1017  1130 D Tethering: clearTetheredNotification()
,08-16 18:15:36.447  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:36.447  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:36.447  1017  1127 D SecContentProvider2: mCursor = null
08-16 18:15:36.447  7711  7711 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 18:15:36.447  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:36.457  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 18:15:36.447  7711  7711 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:36.447  7711  7711 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 18:15:36.447  7711  7711 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 18:15:36.447  7711  7711 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 18:15:36.447  7711  7711 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:36.457  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:36.447  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:36.457  1174  1174 D HotspotTile: updateTetherState():false, false
08-16 18:15:36.447  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:36.457  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:36.457  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-16 18:15:36.457  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:36.457  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:36.457  1017  1127 D SecContentProvider2: mCursor = null
08-16 18:15:36.457  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-16 18:15:36.457  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:36.467  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:36.467  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:36.467  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 18:15:36.477  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 18:15:36.477  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-16 18:15:36.477  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-16 18:15:36.477  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:36.477  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:36.487  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.487  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:36.487  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-16 18:15:36.487  1017  4213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:36.487  1017  4213 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:36.487  1017  4213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:36.487  1017  4213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:36.487  1017  4213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:36.487  1629  1629 I Hs20UtilService: Starting #21
08-16 18:15:36.487  1629  1658 I Hs20UtilService: Message received 5007
,08-16 18:15:36.497  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:36.497  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:36.497  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:36.507  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:36.507  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:36.507  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:36.507  4621  4621 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:36.507  4621  4695 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:36.517   277  1016 D CommandListener: Setting iface cfg
,08-16 18:15:36.517  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-16 18:15:36.527  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:36.527  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:36.537  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:36.537  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:36.537  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:36.537  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:36.537  1017  1127 E WifiNative-wlan0: do suspend false
,08-16 18:15:36.537  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:36.537  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:36.537  1017  1127 D SecContentProvider2: mCursor = null
,08-16 18:15:36.537  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-16 18:15:36.537  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 18:15:36.547  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.547  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:36.757  7724  7724 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 18:15:36.757  7724  7724 I dhcpcd  : version 5.5.6 starting
,08-16 18:15:36.767  7724  7724 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 18:15:36.807  7724  7724 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-16 18:15:36.807  7724  7724 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 18:15:36.807  7724  7724 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 18:15:36.807  7724  7724 I dhcpcd  : bssid match
08-16 18:15:36.807  7724  7724 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-16 18:15:36.847  6788  6873 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1367)
08-16 18:15:36.847  6788  6873 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1367)
08-16 18:15:36.847  6788  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1372)
08-16 18:15:36.847  6788  6873 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 18:15:36.847  6788  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1373)
08-16 18:15:36.847  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:36.847  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f2e7f6 added. We now have 2 listener(s)
,08-16 18:15:36.857  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:15:36.857  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:36.857  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:36.857  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:36.857  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195de7f7 added. We now have 9 listener(s)
08-16 18:15:36.857  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:36.857  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:36.857  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:36.867  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:36.867  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:36.867  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:36.867  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:36.867  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:36.867  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:15:36.867  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3138d0cd added. We now have 3 listener(s)
,08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105d8d82 added. We now have 10 listener(s)
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:36.877  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:36.877  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:36.877  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:15:36.877  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f2e7f6 removed from the list
08-16 18:15:36.877  1017  1096 V AlarmManager: waitForAlarm result :4
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195de7f7 removed from the list,
08-16 18:15:36.877  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:36.877  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:36.877  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195de7f7 not in the list
08-16 18:15:36.877  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105d8d82 removed from the list
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:36.877  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:36.877  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:36.877  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:36.877  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3138d0cd removed from the list
08-16 18:15:36.887  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 18:15:36.887  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d7f0c93 added. We now have 2 listener(s)
,08-16 18:15:36.887  7724  7724 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-16 18:15:36.887  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 18:15:36.887  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:36.887  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:36.887  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:36.887  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f54d0 added. We now have 9 listener(s)
08-16 18:15:36.887  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:36.897  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:36.897  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:36.907  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:36.907   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 18:15:36.907   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-16 18:15:36.907  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:36.907  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:36.907  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:36.907  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2daffce added. We now have 3 listener(s)
,08-16 18:15:36.917  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 18:15:36.917  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:36.917  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:36.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:36.917  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:36.917  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1883deef added. We now have 10 listener(s)
08-16 18:15:36.917  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:36.917  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:36.917  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:36.917  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:36.917  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:36.917  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:36.917  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:36.917  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:36.927  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:36.927  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:36.927  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-16 18:15:36.927  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:36.927  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:36.937  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:36.937  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:36.937  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:36.947  3181  7636 D BtGatt.GattService: registerClient() - UUID=7d395cf2-a3d5-4683-8d64-763657a04757
,08-16 18:15:36.987  7724  7724 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-16 18:15:36.987  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=7d395cf2-a3d5-4683-8d64-763657a04757, clientIf=6
,08-16 18:15:36.987  6788  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:36.997  3181  3196 D BtGatt.GattService: start scan with filters
08-16 18:15:36.997  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:36.997  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:36.997  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:36.997  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:36.997  3181  3304 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:37.007  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:37.007  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:37.007  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:37.007  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:37.007  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.017  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 18:15:37.017  3181  3304 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:37.017  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:37.017  3181  3304 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-16 18:15:37.017  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 18:15:37.017  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.017  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:37.017  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-16 18:15:37.027  6788  6873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:15:37.027  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-16 18:15:37.027  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
08-16 18:15:37.027  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 18:15:37.027  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 18:15:37.027  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.027  3181  3256 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:37.027  3181  3193 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 18:15:37.027  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:15:37.027  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:37.037  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:37.037  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:37.037  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-16 18:15:37.037  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.037  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:37.037  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:37.037  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:37.037  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 18:15:37.037  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.037  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:37.037  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:37.037  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:37.037  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.037  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.037  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.037  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.037  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d7f0c93 removed from the list
08-16 18:15:37.037  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.037  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f54d0 removed from the list
08-16 18:15:37.037  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 18:15:37.037  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.047  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.047  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f54d0 not in the list
08-16 18:15:37.047  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.047  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1883deef removed from the list
08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.047  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.047  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.047  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2daffce removed from the list
08-16 18:15:37.047  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.047  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e597b0b added. We now have 2 listener(s)
08-16 18:15:37.047  3181  3304 D BtGatt.ScanManager: filter size is 1
08-16 18:15:37.047  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 6
08-16 18:15:37.047  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 18:15:37.047  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.047  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.047  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.057  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.057  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1518ede8 added. We now have 9 listener(s)
08-16 18:15:37.057  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.057  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:37.057  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 18:15:37.057  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.057  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 18:15:37.057  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:37.057  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.067  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:37.067  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:37.067  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:37.067  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:37.067  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.067  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17033aa6 added. We now have 3 listener(s)
08-16 18:15:37.067  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:15:37.077  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.077  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.077  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.077  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2bce7 added. We now have 10 listener(s)
08-16 18:15:37.077  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.077  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:37.077  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:37.077  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:37.077  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:37.077  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:37.077  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:37.087  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.087  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.087  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:37.087  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-16 18:15:37.097  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-16 18:15:37.107  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-16 18:15:37.107  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:37.107  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:37.117  3181  3196 D BtGatt.GattService: registerClient() - UUID=f30faa05-b7ec-4016-8eb3-1fb0c3d68d58
,08-16 18:15:37.157  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=f30faa05-b7ec-4016-8eb3-1fb0c3d68d58, clientIf=6
,08-16 18:15:37.157  6788  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:37.157  3181  3333 D BtGatt.GattService: start scan with filters
08-16 18:15:37.157  3181  3304 D BtGatt.ScanManager: handling starting scan,
08-16 18:15:37.157  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:37.157  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:37.157  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:37.157  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:37.167  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 18:15:37.167  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.167  3181  3304 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:37.167  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:37.167  3181  3304 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-16 18:15:37.167  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 18:15:37.167  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.167  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:37.167  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:37.167  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:37.167  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.167  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:37.167  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:37.167  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:37.167  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:37.177  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 18:15:37.177  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.177  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:15:37.177  6788  6873 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 18:15:37.177  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:37.177  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:37.177  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 18:15:37.177  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-16 18:15:37.177  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e597b0b removed from the list,
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.177  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1518ede8 removed from the list
08-16 18:15:37.177  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.177  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:15:37.177  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 18:15:37.177  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1518ede8 not in the list
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:37.177  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:37.177  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 18:15:37.177  3181  7636 D BtGatt.GattService: stopScan() - queue size =1
08-16 18:15:37.187  3181  3304 D BtGatt.ScanManager: filter size is 1,
08-16 18:15:37.187  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 7
08-16 18:15:37.187  3181  3196 D BtGatt.GattService: unregisterClient() - clientIf=6
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-16 18:15:37.187  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:37.187  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.187  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.187  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:37.187  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:37.187  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.187  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa2bce7 removed from the list
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.187  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.187  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.187  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.187  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17033aa6 removed from the list
,08-16 18:15:37.187  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.187  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36544083 added. We now have 2 listener(s)
08-16 18:15:37.187  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:37.187  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.187  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:37.197  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 18:15:37.197  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.197  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.197  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.197  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d99200 added. We now have 9 listener(s)
08-16 18:15:37.197  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:37.197  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:37.197  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 18:15:37.197  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.197  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:37.197  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:37.197  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:37.197  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:37.197  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.197  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fecf87e added. We now have 3 listener(s)
,08-16 18:15:37.207  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.207  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.207  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:15:37.207  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.207  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.207  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:37.207  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1061df added. We now have 10 listener(s)
08-16 18:15:37.207  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.207  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:15:37.207  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:37.207  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:37.207  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:37.207  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:37.207  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:37.217  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:37.217  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:37.217  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:37.217  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:37.217  6788  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:37.217  3181  3333 D BtGatt.GattService: registerClient() - UUID=73b76e49-ac79-444b-919c-330ad14aa6f9
,08-16 18:15:37.267  3181  3255 D BtGatt.GattService: onClientRegistered() - UUID=73b76e49-ac79-444b-919c-330ad14aa6f9, clientIf=6
,08-16 18:15:37.267  6788  7553 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:37.267  3181  3193 D BtGatt.GattService: start scan with filters
,08-16 18:15:37.267  3181  3304 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:37.267  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:37.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:37.267  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:37.267  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:37.277  3181  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 18:15:37.277  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.277  3181  3304 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:37.277  3181  3304 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:37.277  3181  3304 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-16 18:15:37.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:37.277  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:37.277  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:37.277  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 18:15:37.277  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.277  3181  3304 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:37.277  3181  3304 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:37.277  3181  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:37.277  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.277  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:37.287  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:37.287  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.287  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:37.297  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:37.297  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:15:37.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:15:37.297  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.297  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:37.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 18:15:37.297  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36544083 removed from the list
08-16 18:15:37.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.297  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d99200 removed from the list
,08-16 18:15:37.297  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:37.297  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:37.297  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.297  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:15:37.297  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.297  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:37.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:37.297  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.307  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d99200 not in the list
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:37.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:37.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:37.307  3181  3256 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:37.307  3181  3304 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:37.307  3181  3304 D BtGatt.ScanManager: delete FilterIndex - 8
,08-16 18:15:37.307  3181  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-16 18:15:37.307  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.307  3181  3304 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:37.307  3181  7636 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:37.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:37.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:37.307  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:37.307  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:37.317  3181  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 18:15:37.317  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:37.317  3181  3304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:37.317  3181  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 18:15:37.317  3181  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:37.317  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:37.317  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 18:15:37.317  6788  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:37.317  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:37.317  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.327  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:37.327  6788  6788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:37.327  6788  6788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:37.327  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.327  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.327  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1061df removed from the list
,08-16 18:15:37.327  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.327  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.327  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.327  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fecf87e removed from the list
,08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10433cfb added. We now have 2 listener(s)
,08-16 18:15:37.327  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:15:37.327  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.327  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:37.327  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57a118 added. We now have 9 listener(s)
08-16 18:15:37.327  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:37.337  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:37.337  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:37.337  6788  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:37.347  6788  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:37.347  6788  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de59956 added. We now have 3 listener(s)
,08-16 18:15:37.347  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfeadd7 added. We now have 10 listener(s)
08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:37.347  6788  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:37.347  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:37.347  6788  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.347  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10433cfb removed from the list
08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.347  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57a118 removed from the list
,08-16 18:15:37.347  6788  6788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:37.347  6788  6873 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.347  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 18:15:37.347  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.347  6788  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57a118 not in the list
08-16 18:15:37.347  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.347  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.357  6788  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfeadd7 removed from the list
08-16 18:15:37.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.357  6788  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.357  6788  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.357  6788  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.357  6788  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de59956 removed from the list
,08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 18:15:37.357  6788  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:37.357  1017  1127 E WifiNative-wlan0: do suspend true
,08-16 18:15:37.367  6788  7758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1380, name: My test thread name)
08-16 18:15:37.367  6788  7758 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1380, thread name: My test thread name)
08-16 18:15:37.367  6788  7758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1380, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 18:15:37.367  6788  7759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1382, name: My test thread name)
,08-16 18:15:37.367  6788  7759 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1382, thread name: My test thread name)
08-16 18:15:37.367  6788  7759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1382, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 18:15:37.367  6788  6873 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 18:15:37.367  6788  6873 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 18:15:37.367  6788  6873 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0,
08-16 18:15:37.367  6788  6873 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 18:15:37.367  6788  6873 D com.test.thalitest.ThaliTestRunner: Total duration: 23275 ms
,08-16 18:15:37.367  6788  6873 I jxcore-log: Total number of executed tests:  80
08-16 18:15:37.367  6788  6873 I jxcore-log: 
,08-16 18:15:37.367  6788  6873 I jxcore-log: Number of passed tests:  80
08-16 18:15:37.367  6788  6873 I jxcore-log: 
,08-16 18:15:37.367  6788  6873 I jxcore-log: Number of failed tests:  0
08-16 18:15:37.367  6788  6873 I jxcore-log: 
,08-16 18:15:37.367  6788  6873 I jxcore-log: Number of ignored tests:  0
08-16 18:15:37.367  6788  6873 I jxcore-log: 
08-16 18:15:37.367  6788  6873 I jxcore-log: Total duration:  23275
08-16 18:15:37.367  6788  6873 I jxcore-log: 
,08-16 18:15:37.377  6788  6873 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 18:15:37.377  6788  6873 I jxcore-log: 
,08-16 18:15:37.377  6788  6788 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.387  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-16 18:15:37.387  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.387  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.387  6788  6873 I jxcore-log: 
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1017  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 18:15:37.397  1017  1127 E WifiStateMachine: VerifyingLinkState enter
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.397  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,08-16 18:15:37.397  6788  6873 I jxcore-log: 
08-16 18:15:37.397  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
08-16 18:15:37.407  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
08-16 18:15:37.407  1017  1129 D ConnectivityService: Adding iface wlan0 to network 504
08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
,08-16 18:15:37.407  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:37.407  6788  6873 I jxcore-log: 
08-16 18:15:37.417  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-16 18:15:37.417  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:37.417  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:37.417  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:37.417  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 18:15:37.427  1017  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:37.427  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:37.427  1017  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.427  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:37.427  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:37.427  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:37.427  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.427  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.427  1017  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-16 18:15:37.427  1629  1629 I Hs20UtilService: Starting #22
08-16 18:15:37.427  1017  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-16 18:15:37.427  1629  1658 I Hs20UtilService: Message received 5007
,08-16 18:15:37.427  1017  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 18:15:37.427  1017  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-16 18:15:37.427  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:37.427  1017  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-16 18:15:37.427  1017  1129 D ConnectivityService: LTETest block dns file not exists
08-16 18:15:37.427  4621  4621 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 18:15:37.427  1017  1129 V NetworkStats: updateIfacesLocked()
08-16 18:15:37.427  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.427  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:37.427  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:37.427  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:37.437  1017  1129 V NetworkStats: performPollLocked() took 5ms
08-16 18:15:37.437  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.447  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:37.447  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.447  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 18:15:37.447  1017  1129 E ConnectivityService: updateNetworkInfo()
08-16 18:15:37.447  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:37.447  1017  1129 V NetworkStats: updateIfacesLocked()
08-16 18:15:37.447  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.447  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:37.447  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 18:15:37.447  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:37.447  1017  1129 V NetworkStats: performPollLocked() took 3ms
08-16 18:15:37.447  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.447  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.447  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.457  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.457  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.457  1017  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.457  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:37.457  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.457  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 18:15:37.457  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:37.457  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-16 18:15:37.457  1017  7722 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 18:15:37.467  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:37.467  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:37.467  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:37.467  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:37.467  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:37.467  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:15:37.467  1017  1129 D ConnectivityService:    accepting network in place of null
08-16 18:15:37.467   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 18:15:37.467   277  1012 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-16 18:15:37.467  1479  1479 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
08-16 18:15:37.467  1479  1479 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:37.467  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:15:37.467  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-16 18:15:37.467  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-16 18:15:37.467  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 18:15:37.467  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
,08-16 18:15:37.467  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-16 18:15:37.477  1017  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-16 18:15:37.477  1017  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:15:37.477  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:37.477  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.477  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:37.477  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1629  1629 I Hs20UtilService: Starting #23
08-16 18:15:37.477  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.477  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.477  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1017  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-16 18:15:37.477  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 18:15:37.477  1629  1658 I Hs20UtilService: Message received 5007,
08-16 18:15:37.477  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.477  1017  1124 V NetworkStats: updateIfacesLocked()
08-16 18:15:37.477  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:37.477  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:37.477  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:37.477  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.477  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:37.477  1174  1682 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  1017  1124 V NetworkStats: performPollLocked() took 5ms
08-16 18:15:37.487  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.487  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:37.487  4621  4621 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:37.487  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-16 18:15:37.487  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:37.487  4621  4621 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 18:15:37.487  4621  4621 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:37.497  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.497  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.497  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.507  1017  4215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:37.507  1017  4215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:37.507  1017  4215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:37.507  1017  4215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:37.507  1017  4215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:37.507  1629  1629 I Hs20UtilService: Starting #24
08-16 18:15:37.507  1629  1658 I Hs20UtilService: Message received 5007
08-16 18:15:37.507  4621  4621 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:37.507  4621  4621 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 18:15:37.517  1017  1749 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-16 18:15:37.517  1017  4214 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 18:15:37.517  1017  4214 D SecContentProvider2: mCursor = null
,08-16 18:15:37.517  1017  4211 D SecContentProvider2: uri = 15 selection = getToastGravity
08-16 18:15:37.517  1017  4211 D SecContentProvider2: mCursor = null
,08-16 18:15:37.517  1017  1505 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 18:15:37.517  1017  1505 D SecContentProvider2: mCursor = null
08-16 18:15:37.517  1017  1321 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-16 18:15:37.517  1017  1321 D SecContentProvider2: mCursor = null
,08-16 18:15:37.527  1017  4215 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 18:15:37.527  1017  4215 D SecContentProvider2: mCursor = null
08-16 18:15:37.527  1017  1485 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-16 18:15:37.527  1017  1485 D SecContentProvider2: mCursor = null
,08-16 18:15:37.537  6788  6788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 18:15:37.537  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:37.537  6788  6873 I jxcore-log: 
,08-16 18:15:37.557   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-16 18:15:37.557  1017  1749 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-16 18:15:37.557  1017  7722 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 18:15:37.567  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 18:15:37.647  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:15:37 GMT], X-Android-Received-Millis=[1471364137656], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471364137624]}
,08-16 18:15:37.647  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:15:37.647  1017  7722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 18:15:37.647  1017  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.647  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 18:15:37.647  1017  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-16 18:15:37.647  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-16 18:15:37.647  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 18:15:37.647  1174  1682 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:37.647  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,08-16 18:15:37.647  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:37.647  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-16 18:15:37.647  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 18:15:37.657  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.657  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.657  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.657  7762  7762 D AndroidRuntime: ,
08-16 18:15:37.657  7762  7762 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 18:15:37.667  7762  7762 D AndroidRuntime: CheckJNI is OFF,
08-16 18:15:37.667  7762  7762 D AndroidRuntime: readGMSProperty: start
08-16 18:15:37.667  7762  7762 D AndroidRuntime: readGMSProperty: already setted!!,
08-16 18:15:37.667  7762  7762 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 18:15:37.667  7762  7762 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 18:15:37.667  7762  7762 D AndroidRuntime: readGMSProperty: end
,08-16 18:15:37.667  7762  7762 D AndroidRuntime: addProductProperty: start
,08-16 18:15:37.687  6788  6788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:15:37.687  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-16 18:15:37.687  6788  6873 I jxcore-log: 
,08-16 18:15:37.787  7762  7762 E AffinityControl: AffinityControl: registerfunction enter,
,08-16 18:15:37.817  7762  7762 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 18:15:37.827  6788  6788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 18:15:37.827  6788  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:37.827  6788  6873 I jxcore-log: 
,08-16 18:15:37.847  1017  1516 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-16 18:15:37.847  1017  1516 D PackageManager: START PACKAGE DELETE: observer{302258877}
08-16 18:15:37.847  1017  1516 D PackageManager: pkg{<packageName>}
08-16 18:15:37.847  1017  1516 D PackageManager: user{0}
08-16 18:15:37.847  1017  1516 D PackageManager: caller{2000}
08-16 18:15:37.847  1017  1516 D PackageManager: flags{2}
08-16 18:15:37.847  1017  1516 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 18:15:37.847  1017  1516 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-16 18:15:37.847  1017  1516 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-16 18:15:37.847  1017  1516 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 18:15:37.847  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-16 18:15:37.847  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 18:15:37.847  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 18:15:37.847  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 18:15:37.847  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 18:15:37.847  1017  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-16 18:15:37.857  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg,
,08-16 18:15:37.857  1017  1043 I ActivityManager: Killing 6788:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 18:15:37.977  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:37.987  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{3e2d6f41 u0 com.test.thalitest/.MainActivity t163}
,08-16 18:15:38.007  1017  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 18:15:38.017  1017  1043 D InputDispatcher: Focus left window: 6788
,08-16 18:15:38.017   257  1039 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-16 18:15:38.017   257   434 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-16 18:15:38.027  1017  3327 D SSRM:n  : SIOP:: AP = 330
,08-16 18:15:38.037  1017  1043 D InputDispatcher: Focused application released
,08-16 18:15:38.037  1017  1749 W WindowManager: Failed looking up window
08-16 18:15:38.037  1017  1749 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1e0e68f7 does not exist
08-16 18:15:38.037  1017  1749 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-16 18:15:38.037  1017  1749 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-16 18:15:38.037  1017  1749 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-16 18:15:38.037  1017  1749 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-16 18:15:38.037  1017  1749 I WindowState: WIN DEATH: null
,08-16 18:15:38.047  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:15:38.047  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:38.047  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-16 18:15:38.057  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 18:15:38.087  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 18:15:38.097  1711  2088 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 18:15:38.097  1854  1854 E SamsungIME: mOCRHelper is null
,08-16 18:15:38.097  2818  2818 I art     : Explicit concurrent mark sweep GC freed 16601(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 821us total 43.822ms
,08-16 18:15:38.107  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-16 18:15:38.117  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 18:15:38.117  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 18:15:38.117  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-16 18:15:38.117  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-16 18:15:38.137  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 18:15:38.137  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 18:15:38.137  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 18:15:38 GMT+02:00 2016
,08-16 18:15:38.147  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 18:15:38.147  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.147  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:38.147  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:38.147  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:38.157  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 18:15:38.157  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 18:15:38.157  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-16 18:15:38.177  2802  2802 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 18:15:38.187  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-16 18:15:38.187  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:38.187  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-16 18:15:38.187  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:38.187  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:38.187  1017  1124 V NetworkStats: performPollLocked() took 7ms
08-16 18:15:38.187  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.187  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:38.197  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 18:15:38.197  1017  1135 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-16 18:15:38.197  1017  1135 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 18:15:38.197  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 18:15:38.197  2802  2802 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:38.197  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.197  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.197  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.197  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.197  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.207  2802  2802 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:38.207  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 18:15:38.217  7778  7778 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.217  7778  7778 E Zygote  : v2
08-16 18:15:38.217  7778  7778 I libpersona: KNOX_SDCARD checking this for 10090
08-16 18:15:38.217  7778  7778 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.217  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 18:15:38.217  1017  1135 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7778 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-16 18:15:38.217  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:38.227  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 18:15:38.227  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-16 18:15:38.227  1017  1505 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 18:15:38.227  1017  1505 D SecContentProvider2: mCursor = null
,08-16 18:15:38.227  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.227  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 18:15:38.227  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.257  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-16 18:15:38.257  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.257  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.257  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.257  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.257  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.257  7778  7778 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.267  7793  7793 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.267  7793  7793 E Zygote  : v2
08-16 18:15:38.267  7793  7793 I libpersona: KNOX_SDCARD checking this for 10052
08-16 18:15:38.267  7793  7793 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.267  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.267  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.277  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:38.277  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-16 18:15:38.277  1017  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7793 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-16 18:15:38.277  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-16 18:15:38.277  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.277  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.277  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.277  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.287  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) },
08-16 18:15:38.287  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-16 18:15:38.297  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.297  7802  7802 E Zygote  : MountEmulatedStorage(),
08-16 18:15:38.297  7802  7802 E Zygote  : v2
08-16 18:15:38.297  7802  7802 I libpersona: KNOX_SDCARD checking this for 10098
08-16 18:15:38.297  7802  7802 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.297  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 18:15:38.297  1017  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7802 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 18:15:38.297  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 18:15:38.297  1465  1465 D RegisteredServicesCache: empty dynamic service
08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0,
08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 18:15:38.307  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-16 18:15:38.297  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 18:15:38.307  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package ,
08-16 18:15:38.307  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 18:15:38.307  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-16 18:15:38.307  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 18:15:38.307  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-16 18:15:38.307  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.307  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.307  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:38.307  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.307  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.317  1017  3327 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 18:15:38.317  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:38.317  7793  7793 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.317   304   304 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 23.778ms
,08-16 18:15:38.327  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:38.327  7802  7802 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.337  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-16 18:15:38.337   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.526ms
,08-16 18:15:38.347  2802  7777 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 18:15:38.357  2802  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-16 18:15:38.357   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 18.140ms
,08-16 18:15:38.367  7823  7823 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.367  7823  7823 I libpersona: KNOX_SDCARD checking this for 10032
08-16 18:15:38.367  7823  7823 E Zygote  : v2
08-16 18:15:38.367  7823  7823 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:38.367  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.377  1017  1504 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7823 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 18:15:38.377  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:38.377  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-16 18:15:38.387  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.407  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 18:15:38.407  2802  2802 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 18:15:38.407  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.417  7823  7823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.417  7823  7823 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.417  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.437  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.437  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.447  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 18:15:38.447  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.447  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:38.457  1017  1057 I art     : Explicit concurrent mark sweep GC freed 70966(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.536ms total 286.305ms
,08-16 18:15:38.457  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-16 18:15:38.457  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.457  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.457  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.457  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.467  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 18:15:38.467  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-16 18:15:38.467  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 18:15:38.467  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 18:15:38.467  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-16 18:15:38.477  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 18:15:38.477  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 18:15:38.477  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 18:15:38.477  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 18:15:38.477  7838  7838 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.477  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-16 18:15:38.477  7838  7838 E Zygote  : v2
08-16 18:15:38.477  7838  7838 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:38.477  7838  7838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:38.477  7838  7838 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.477  1017  1504 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7838 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:38.477  7838  7838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:38.477  7838  7838 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.477  1017  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 18:15:38.487  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 18:15:38.487  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:38.487  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:38.487  1017  1057 D PackageManager: delete codoeFile: 
,08-16 18:15:38.497  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.497  1017  1504 I ActivityManager: Killing 7264:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-16 18:15:38.497  7778  7778 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 18:15:38.507  7778  7778 D elm:15121: ELMEngine.ELMEngine( context ).
,08-16 18:15:38.517  7838  7838 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 18:15:38.517  7838  7838 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:38.517  7778  7778 D elm:15121: MDMBridge.setEnterpriseBridge()
08-16 18:15:38.517  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-16 18:15:38.517  1017  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
08-16 18:15:38.517  1017  1057 D PackageManager: result of delete: 1{302258877}
08-16 18:15:38.517  1017  1321 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 18:15:38.517  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.517  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.517  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.517  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 18:15:38.527  7778  7778 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 18:15:38.547  7778  7778 D elm:15121: ElmAgentService : onCreate()
,08-16 18:15:38.547  7778  7853 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-16 18:15:38.547  7778  7853 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-16 18:15:38.547  7778  7853 D elm:15121: MDMBridge.getInstance()
08-16 18:15:38.547  7778  7853 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 18:15:38.547  7762  7762 D AndroidRuntime: Shutting down VM
08-16 18:15:38.547  7778  7853 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-16 18:15:38.547  1685  1685 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-16 18:15:38.547  1685  1685 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-16 18:15:38.547  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.557  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.557  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.567  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 18:15:38.567  1017  4214 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-16 18:15:38.567  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-16 18:15:38.567  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.567  1017  4214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.567  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-16 18:15:38.567  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.567  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.567  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 18:15:38.577  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:38.577  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 18:15:38.577  7778  7778 D elm:15121: ElmAgentService : onDestroy().
,08-16 18:15:38.587  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:38.587  1017  4215 I ActivityManager: Killing 7282:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-16 18:15:38.587  7823  7855 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-16 18:15:38.587  7823  7855 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 18:15:38.587  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-16 18:15:38.597  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 18:15:38.597  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:38.597  1017  1478 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-16 18:15:38.597  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.597  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.597  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.597  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-16 18:15:38.607  3785  7857 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-16 18:15:38.607  3785  7857 D AccountUtils: Clearing selected account for com.test.thalitest
08-16 18:15:38.607  1017  4213 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-16 18:15:38.607  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.607  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.607  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.607  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.627  7861  7861 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.627  7861  7861 E Zygote  : v2
08-16 18:15:38.627  7861  7861 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:38.627  7861  7861 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.627  7861  7861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.627  7861  7861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:38.627  7823  7855 D SPPClientService: PushLog.txt file is not deleted.
,08-16 18:15:38.627  7823  7855 D SPPClientService: PushLog.txt file is not deleted.
08-16 18:15:38.627  7823  7855 D SPPClientService: ============PushLog. stop!
08-16 18:15:38.627  7861  7861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.637  1017  4213 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7861 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:38.637  1017  4213 I ActivityManager: Killing 7298:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 18:15:38.647  1017  4213 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-16 18:15:38.647  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.647  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.647  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.647  1017  4213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.657  7876  7876 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.657  7876  7876 I libpersona: KNOX_SDCARD checking this for 10039
08-16 18:15:38.657  7876  7876 E Zygote  : v2
08-16 18:15:38.657  7876  7876 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:38.657  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.667  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 18:15:38.667  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.667  1017  4213 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7876 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 18:15:38.667  1017  1749 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:38.667  1017  1749 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.667  1017  1749 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.667  1017  1749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.677  7861  7861 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.677  7861  7861 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.677  1017  1485 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-16 18:15:38.677  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.677  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.677  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.677  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-16 18:15:38.687  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.687  7876  7876 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.687  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-16 18:15:38.687  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.687  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.687  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.687  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-16 18:15:38.687  1017  1516 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:38.687  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.687  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.687  1017  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.687  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.697  3785  7857 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-16 18:15:38.707  1017  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:38.707  7876  7876 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 18:15:38.707  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.707  1017  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.707  7876  7876 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:38.707  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.707  7876  7876 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:38.717  7876  7876 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 18:15:38.717  7876  7876 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 18:15:38.717  7876  7876 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 18:15:38.717  7876  7876 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 18:15:38.717  1017  4214 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 18:15:38.717  1017  4214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.717  1017  4214 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.717  1017  4214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.717  1017  4214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.727  7608  7608 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-16 18:15:38.727  1017  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:38.727  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:38.727  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.727  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.737  1017  4214 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-16 18:15:38.737  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.737  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.737  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.737  1017  4214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.747  7861  7861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-16 18:15:38.757  7895  7895 E Zygote  : MountEmulatedStorage(),
08-16 18:15:38.757  7895  7895 E Zygote  : v2
08-16 18:15:38.757  7895  7895 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:38.757  7895  7895 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.757  7895  7895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.757  7895  7895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:38.757  7762  7762 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-16 18:15:38.757  1017  4214 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:38.757  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:38.757  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-16 18:15:38.757  7895  7895 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.767  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.767  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.767  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.767  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.767  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.767  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.767  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.777  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 18:15:38.777  1017  1057 D PackageManager: userId{-1}
08-16 18:15:38.777  1017  1057 D PackageManager: andCode{true}
,08-16 18:15:38.787  7909  7909 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.787  7909  7909 E Zygote  : v2
08-16 18:15:38.787  7909  7909 I libpersona: KNOX_SDCARD checking this for 10011
08-16 18:15:38.787  7909  7909 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:38.787  7909  7909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.787  7909  7909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:38.787  7909  7909 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.787  1017  1135 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7909 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 18:15:38.787  1017  1321 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-16 18:15:38.787  1017  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
08-16 18:15:38.797  1017  1321 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.797  1017  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.797  1017  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
08-16 18:15:38.797  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-16 18:15:38.797  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.807  7895  7895 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.807  7895  7895 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.807  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.807  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.807  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.817  7909  7909 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.817  7909  7909 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.,
,08-16 18:15:38.837  1017  1504 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-16 18:15:38.837  7928  7928 E Zygote  : MountEmulatedStorage()
,08-16 18:15:38.837  7928  7928 E Zygote  : v2
,08-16 18:15:38.837  7928  7928 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:38.837  7928  7928 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-16 18:15:38.837  7928  7928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-16 18:15:38.837  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-16 18:15:38.847  7928  7928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false,
08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-16 18:15:38.847  7928  7928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-16 18:15:38.847  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-16 18:15:38.857  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 18:15:38.857  3785  3785 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-16 18:15:38.857  3785  3785 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-16 18:15:38.867  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-16 18:15:38.877  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-16 18:15:38.877  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-16 18:15:38.877  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.877  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-16 18:15:38.877  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.877  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-16 18:15:38.877  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.877  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-16 18:15:38.877  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.877  7909  7909 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 18:15:38.877  7928  7928 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:38.877  7909  7909 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 18:15:38.877  7928  7928 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.897  7946  7946 E Zygote  : MountEmulatedStorage()
,08-16 18:15:38.897  7946  7946 E Zygote  : v2
08-16 18:15:38.897  7946  7946 I libpersona: KNOX_SDCARD checking this for 10003
,08-16 18:15:38.897  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7946 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 18:15:38.897  7946  7946 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:38.907  7946  7946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 18:15:38.907  7946  7946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 18:15:38.907  7946  7946 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:38.917  7608  7608 D BluetoothAdapter: cancelDiscovery
,08-16 18:15:38.917  1017  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:38.927  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:38.927  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:38.927  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:38.927  3785  3785 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-16 18:15:38.927  3785  3785 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-16 18:15:38.937  3181  3253 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:15:38.937  7946  7946 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:38.937  7946  7946 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:38.937  7895  7895 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:38.947  3785  7919 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,08-16 18:15:38.947  1017  1478 I ActivityManager: Killing 7316:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-16 18:15:38.947  3785  7919 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-16 18:15:38.957  3785  7919 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-16 18:15:38.957  3785  7919 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-16 18:15:38.957  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 18:15:38.957  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.957  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.957  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:38.957  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:38.967  3785  7919 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
08-16 18:15:38.967  3785  7919 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-16 18:15:38.977  3785  7919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 18:15:38.977  3785  7919 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
,08-16 18:15:38.977  3785  7919 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-16 18:15:38.977  7909  7909 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-16 18:15:38.977  1017  1478 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 18:15:38.977  7909  7909 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-16 18:15:38.977  7964  7964 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:38.977  7964  7964 E Zygote  : MountEmulatedStorage()
08-16 18:15:38.977  7964  7964 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:38.977  7964  7964 E Zygote  : v2
08-16 18:15:38.977  3181  3196 D BluetoothAdapterProperties: mDiscovering is false
08-16 18:15:38.977  3181  3196 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-16 18:15:38.977  7608  7608 D BluetoothAdapter: cancelDiscovery = true
08-16 18:15:38.977  7608  7608 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
08-16 18:15:38.987  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-16 18:15:38.987  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 18:15:38.987  7964  7964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 18:15:38.987  3785  7919 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-16 18:15:38.987  3785  7919 E AndroidRuntime: Process: com.google.android.gms, PID: 3785
08-16 18:15:38.987  3785  7919 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:38.987  3785  7919 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:15:38.987  7964  7964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 18:15:38.987  7964  7964 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:38.987  1017  1749 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-16 18:15:38.997  7608  7608 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:39.007  1017  7975 E DropBoxManagerService: 	... 5 more
08-16 18:15:39.007  7608  7608 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 18:15:39.007  7608  7608 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,08-16 18:15:39.007  7895  7895 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
08-16 18:15:39.007  7909  7909 I MultiDex: VM with version 2.1.0 has multidex support
08-16 18:15:39.007  7909  7909 I MultiDex: install
08-16 18:15:39.007  7909  7909 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 18:15:39.007  7608  7608 E SQLiteDatabase: Error inserting timestamp=1471364138994 message=Predictor: service stopped by removePlaceCategories()
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:39.007  7608  7608 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:39.007  7608  7608 E UserAnalysis: It failed to insert to dump_log table
,08-16 18:15:39.007  3785  7919 I Process : Sending signal. PID: 3785 SIG: 9
,08-16 18:15:39.017  7895  7895 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 18:15:39.017  7895  7895 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
,08-16 18:15:39.017  7895  7895 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:39.017  7895  7895 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:39.017  7895  7895 D AndroidRuntime: Shutting down VM
08-16 18:15:39.017  7895,  7895 E AndroidRuntime: FATAL EXCEPTION: main
08-16 18:15:39.017  7895  7895 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7895
08-16 18:15:39.017  7895  7895 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at andr,oid.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 18:15:39.017  7895  7895 E AndroidRuntime: 	... 11 more
08-16 18:15:39.027  7964  7964 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:39.027  7876  7876 D NearbySource: Nearby Source Create!
08-16 18:15:39.027  7964  7964 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:39.027  7876  7876 D NearbyContext: Nearby Context Create!
08-16 18:15:39.047  1017  1516 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:39.047  1017  7985 E DropBoxManagerService: 	... 5 more
08-16 18:15:39.047  7928  7984 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
08-16 18:15:39.047  1017  1505 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-16 18:15:39.047  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-16 18:15:39.047  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:39.047  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:39.047  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-16 18:15:39.057  1017  1506 I ActivityManager: Killing 7349:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-16 18:15:39.057  7895  7895 I Process : Sending signal. PID: 7895 SIG: 9
,08-16 18:15:39.067  7928  7984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-16 18:15:39.067  1017  1749 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-16 18:15:39.067  1017  1749 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0

```
