#### Test 8362733705cfec3_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
09-12 13:56:42.875  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.875  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.875  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.875  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
09-12 13:56:42.885  1459  1674 D TP/MmsSmsProvider: query,matched:400, calling pid = 6330
09-12 13:56:42.885  6330  6330 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-12 13:56:42.895  6533  6533 E Zygote  : MountEmulatedStorage()
09-12 13:56:42.895  6533  6533 E Zygote  : v2
09-12 13:56:42.895  6533  6533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:42.895  6330  6530 D Mms/Synchronizer: [end]    doSync consume time = 25.04224
09-12 13:56:42.895  6533  6533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:42.895  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:42.895  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:42.895  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-12 13:56:42.895  6533  6533 I libpersona: KNOX_SDCARD checking this for 10068
09-12 13:56:42.895  6533  6533 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:42.895  1018  1954 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6533 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-12 13:56:42.895  1018  1329 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-12 13:56:42.895  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-12 13:56:42.905  6533  6533 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 13:56:42.905  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-12 13:56:42.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:42.915  6548  6548 E Zygote  : MountEmulatedStorage()
09-12 13:56:42.915  6548  6548 E Zygote  : v2
09-12 13:56:42.915  6548  6548 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:42.915  6330  6540 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-12 13:56:42.915  6330  6540 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-12 13:56:42.915  6548  6548 I libpersona: KNOX_SDCARD checking this for 10042
09-12 13:56:42.915  6548  6548 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:42.925  6533  6533 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:42.925  6533  6533 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:42.925  6548  6548 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:42.925  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:42.925  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:42.925  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:56:42.925  6548  6548 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-12 13:56:42.925  1018  1030 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6548 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-12 13:56:42.925  1018  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:56:42.925  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 13:56:42.925  1018  1030 I ActivityManager: Killing 6083:com.sec.android.app.music:service/u0a35 (adj 15): empty #21
09-12 13:56:42.935  1018  1442 I ActivityManager: Killing 5965:com.google.android.gm/u0a99 (adj 15): empty #21
09-12 13:56:42.945  6330  6529 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 51.4425
09-12 13:56:42.955  6548  6548 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:42.955  6548  6548 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:42.975  6297  6345 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 599 ms] updated apps [took 599 ms] 
09-12 13:56:42.975  6548  6548 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:56:42.975  6548  6548 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:56:42.975  6548  6548 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 13:56:42.975  1018  1030 I ActivityManager: Killing 5388:com.google.android.music:main/u0a108 (adj 15): empty #21
09-12 13:56:42.975  6533  6533 D BadgeProvider: onCreate
09-12 13:56:42.985  6533  6533 D BadgeProvider: DatabaseHelper
09-12 13:56:42.985  6513  6513 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-12 13:56:43.155  1900  6364 I qtaguid : Untagging socket 101
09-12 13:56:43.155  1900  1900 I ConfigFetchService: fetch service done; releasing wakelock
09-12 13:56:43.165  1018  1454 I art     : Explicit concurrent mark sweep GC freed 139007(7MB) AllocSpace objects, 7(1911KB) LOS objects, 33% free, 23MB/34MB, paused 2.597ms total 179.719ms
09-12 13:56:43.185  1900  1900 I ConfigFetchService: stopping self
09-12 13:56:43.185  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-12 13:56:43.185  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.185  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.195  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.195  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.205  6548  6548 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-12 13:56:43.205  6569  6569 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:56:43.205  6569  6569 E Zygote  : MountEmulatedStorage()
09-12 13:56:43.205  6569  6569 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:43.205  6569  6569 E Zygote  : v2
09-12 13:56:43.205  6569  6569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:43.205  6569  6569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:43.205  6569  6569 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:56:43.225  1018  1489 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6569 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 13:56:43.225  1018  1489 I ActivityManager: Killing 6124:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
09-12 13:56:43.225  1018  1329 I ActivityManager: Killing 6174:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
09-12 13:56:43.235  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-12 13:56:43.235  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-12 13:56:43.235  6330  6511 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-12 13:56:43.245  1459  2465 D TP/SmsProvider: query,matched:26, calling pid = 6330
09-12 13:56:43.245  1459  2465 D TP/SmsProvider: match 26:Elapsed time : 1.366 ms
09-12 13:56:43.245  6566  6566 D AndroidRuntime: 
09-12 13:56:43.245  6566  6566 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 13:56:43.255   283   283 E installd: system dir 0 : /system/app/
09-12 13:56:43.255   283   283 E installd: system dir 1 : /system/priv-app/
09-12 13:56:43.255   283   283 E installd: system dir 2 : /vendor/app/
09-12 13:56:43.255   283   283 E installd: system dir 3 : /oem/app/
09-12 13:56:43.255  6566  6566 D AndroidRuntime: CheckJNI is OFF
09-12 13:56:43.255  6566  6566 D AndroidRuntime: readGMSProperty: start
09-12 13:56:43.255  6566  6566 D AndroidRuntime: readGMSProperty: already setted!!
09-12 13:56:43.255  6566  6566 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:56:43.255  6566  6566 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:56:43.255  6566  6566 D AndroidRuntime: readGMSProperty: end
09-12 13:56:43.255  6566  6566 D AndroidRuntime: addProductProperty: start
09-12 13:56:43.255  6569  6569 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:43.265  6569  6569 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:43.265  1459  1474 D TP/MmsSmsProvider: query,matched:6, calling pid = 6330
09-12 13:56:43.275  1459  1474 D TP/MmsSmsProvider: match 6:Elapsed time : 0.951 ms
09-12 13:56:43.285  6569  6569 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-12 13:56:43.315  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-12 13:56:43.315  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.315  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.315  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.315  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.325  6591  6591 E Zygote  : MountEmulatedStorage()
09-12 13:56:43.325  6591  6591 E Zygote  : v2
09-12 13:56:43.325  1018  1030 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6591 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-12 13:56:43.335  6591  6591 I libpersona: KNOX_SDCARD checking this for 10023
09-12 13:56:43.335  6591  6591 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:43.335  6591  6591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:43.335  6591  6591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:43.335  6591  6591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:56:43.335  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-12 13:56:43.355  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:43.355  6591  6591 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:43.395  6566  6566 E AffinityControl: AffinityControl: registerfunction enter
09-12 13:56:43.415  6591  6591 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-12 13:56:43.435  6566  6566 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 13:56:43.435  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-12 13:56:43.435  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.435  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.435  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.435  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.445  6330  6511 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-12 13:56:43.455  6609  6609 E Zygote  : MountEmulatedStorage()
09-12 13:56:43.455  6609  6609 E Zygote  : v2
09-12 13:56:43.465  6609  6609 I libpersona: KNOX_SDCARD checking this for 10152
09-12 13:56:43.465  6609  6609 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:43.465  1018  1454 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6609 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-12 13:56:43.465  1018  1454 I ActivityManager: Killing 6024:com.android.calendar/u0a131 (adj 15): empty #21
09-12 13:56:43.465  1018  1031 E PersonaManagerService: inState():  stateMachine is null !!
09-12 13:56:43.465  1018  1031 I PersonaManagerService: PersonaId don't exist
09-12 13:56:43.465  1018  1031 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 13:56:43.465  6609  6609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:43.475  6609  6609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:43.475  6609  6609 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-12 13:56:43.485  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-12 13:56:43.485  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-12 13:56:43.495  1900  6402 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 143.351ms
09-12 13:56:43.505  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-12 13:56:43.505  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-12 13:56:43.505  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-12 13:56:43.505  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-12 13:56:43.505  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-12 13:56:43.515  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-12 13:56:43.515  6591  6591 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-12 13:56:43.515  6609  6609 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:43.525  1018  1031 W ActivityManager: mDVFSHelper.acquire()
09-12 13:56:43.525  6609  6609 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:43.525  1018  1031 D FocusedStackFrame: Set to : 0
09-12 13:56:43.545  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 13:56:43.545  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 13:56:43.545  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.545  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.545  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.545  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.565  6625  6625 E Zygote  : MountEmulatedStorage()
09-12 13:56:43.565  6625  6625 E Zygote  : v2
09-12 13:56:43.565  6625  6625 I libpersona: KNOX_SDCARD checking this for 10170
09-12 13:56:43.565  6625  6625 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:43.565  6625  6625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:43.565  1018  1031 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6625 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 13:56:43.565  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-12 13:56:43.565  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:56:43.565  1018  1031 D InputDispatcher: Focused application set to: xxxx
09-12 13:56:43.565  1018  1031 D InputDispatcher: Focus left window: 1490
09-12 13:56:43.565  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:56:43.565  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 13:56:43.565  6625  6625 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:43.565  6625  6625 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 13:56:43.575   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-12 13:56:43.575  6566  6566 D AndroidRuntime: Shutting down VM
09-12 13:56:43.595   309   309 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 25.922ms
09-12 13:56:43.605  1018  1442 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 13:56:43.605  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:43.605  6625  6625 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:43.615   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 19.274ms
09-12 13:56:43.615  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:56:43.615  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 13:56:43.615  1018  1488 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-12 13:56:43.615  1018  1018 V ActivityManager: Display changed displayId=0
09-12 13:56:43.635  6346  6428 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
09-12 13:56:43.635   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 21.243ms
09-12 13:56:43.635  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 13:56:43.665  1018  1488 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:56:43.675  6609  6609 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-12 13:56:43.675  6609  6609 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-12 13:56:43.695  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-12 13:56:43.695  6609  6609 I TapandpayWidget:Utils: Clear T&P info.
09-12 13:56:43.695  6346  6428 I AcmsKeyStoreHelper: Key Store exist
09-12 13:56:43.695  6346  6428 I AcmsKeyStoreHelper: Hence loading the keystore file
09-12 13:56:43.705  6609  6609 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-12 13:56:43.705  1900  1916 W art     : Suspending all threads took: 19.483ms
09-12 13:56:43.705  1018  1442 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-12 13:56:43.705  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.705  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.705  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.705  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:43.725  6642  6642 E Zygote  : MountEmulatedStorage()
09-12 13:56:43.725  6642  6642 E Zygote  : v2
09-12 13:56:43.725  6642  6642 I libpersona: KNOX_SDCARD checking this for 10009
09-12 13:56:43.725  6642  6642 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:43.725  6642  6642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:43.725  1018  1442 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6642 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-12 13:56:43.725  1018  1442 I ActivityManager: Killing 5882:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-12 13:56:43.725  6642  6642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:43.725  6642  6642 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 13:56:43.765   257   444 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-12 13:56:43.775   257  1102 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-12 13:56:43.785  6642  6642 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:43.785  6642  6642 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:43.785  6566  6566 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-12 13:56:43.795  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{211f79c6 token=android.os.BinderProxy@15e6fef7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-12 13:56:43.795  1490  1490 D Launcher: onTrimMemory. Level: 20
09-12 13:56:43.805  6346  6428 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-12 13:56:43.805  6346  6428 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-12 13:56:43.805  6346  6428 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-12 13:56:43.805  6346  6428 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:56:43.805  6346  6428 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-12 13:56:43.805  6346  6428 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
09-12 13:56:43.805  6346  6428 D AcmsCore: This is NOT a valid MirrorLink app
09-12 13:56:43.805  6346  6428 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-12 13:56:43.805  6346  6428 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:56:43.805  6346  6428 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-12 13:56:43.805  6346  6428 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
09-12 13:56:43.805  6346  6346 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-12 13:56:43.805  6346  6346 D AcmsService: Enter onDestroy
09-12 13:56:43.805  6346  6346 I AcmsService: cleanUp(): inside service clean up
09-12 13:56:43.805  6346  6346 D AcmsCore: AcmsCore: inside DeInit
09-12 13:56:43.805  6346  6346 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-12 13:56:43.805  6346  6346 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-12 13:56:43.805  6346  6346 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-12 13:56:43.805  6346  6346 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-12 13:56:43.805  6346  6346 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-12 13:56:43.805  6346  6346 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-12 13:56:43.805  6346  6346 D AcmsService: killing acms process
09-12 13:56:43.805  6346  6346 I Process : Sending signal. PID: 6346 SIG: 9
09-12 13:56:43.815  6406  6498 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 13:56:43.815  6406  6498 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 13:56:43.815  6406  6498 I GAv4    :   adb logcat -s GAv4
09-12 13:56:43.825  6625  6625 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-12 13:56:43.845  1018  1308 I ActivityManager: Process ACMS.Process (pid 6346)(adj 0) has died(52,762)
09-12 13:56:43.855  6625  6625 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4297-4300)
09-12 13:56:43.855  6625  6625 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 13:56:43.855  6406  6498 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-12 13:56:43.865  1018  1487 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 13:56:43.875  6625  6625 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a41d119}
09-12 13:56:43.875  6625  6625 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 13:56:43.875  6625  6625 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:56:43.875  6406  6498 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-12 13:56:43.895  1018  1030 I ActivityManager: Killing 6249:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-12 13:56:43.895  6406  6498 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-12 13:56:43.915  6406  6664 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-12 13:56:43.915  6625  6625 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-12 13:56:43.915  6625  6625 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:43.925  6625  6625 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 13:56:43.945  6625  6625 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:56:43.945  6625  6625 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:56:43.945  6625  6625 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:56:43.945  6625  6625 I Adreno-EGL: Local Branch: 
09-12 13:56:43.945  6625  6625 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:56:43.945  6625  6625 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:56:43.945  6625  6625 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-12 13:56:43.985  1900  3991 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-12 13:56:44.015  6625  6625 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:56:44.025  6625  6625 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-12 13:56:44.025  6625  6625 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-12 13:56:44.035  6625  6625 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-12 13:56:44.035  6625  6625 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-12 13:56:44.065  1900  3991 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-12 13:56:44.095  1900  3991 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-12 13:56:44.125  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-12 13:56:44.135  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:44.135  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:44.135  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:44.135  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:44.145  6689  6689 E Zygote  : MountEmulatedStorage()
09-12 13:56:44.145  6689  6689 E Zygote  : v2
09-12 13:56:44.145  6689  6689 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:56:44.145  6689  6689 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:44.145  6689  6689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:44.145  1018  1487 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6689 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 13:56:44.145  6689  6689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:44.145  1018  1487 I ActivityManager: Killing 6264:com.sec.spp.push/u0a32 (adj 15): empty #21
09-12 13:56:44.155  6689  6689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:56:44.155  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 13:56:44.155  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:44.155  1018  1954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:44.155  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:56:44.175  6625  6625 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:44.175  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{1a9d96b4 u0 com.test.thalitest/.MainActivity t163}
09-12 13:56:44.185  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:44.185  6689  6689 D ActivityThread: Added TimaKeyStore provider
09-12 13:56:44.205  6406  6686 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 13:56:44.205  6625  6625 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-12 13:56:44.205  6406  6686 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-12 13:56:44.215  6625  6625 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 13:56:44.215  6625  6625 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-12 13:56:44.215  6689  6689 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-12 13:56:44.215  6689  6689 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-12 13:56:44.215  1018  1489 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-12 13:56:44.215  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-12 13:56:44.225  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:44.225  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:44.225  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-12 13:56:44.225  1018  1954 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-12 13:56:44.225  6625  6625 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-12 13:56:44.235  6689  6689 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-12 13:56:44.235  6406  6686 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-12 13:56:44.245  6625  6625 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:44.245  6625  6625 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:56:44.255  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
09-12 13:56:44.255  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
09-12 13:56:44.255  6689  6705 E FilterInstaller: installFilters
09-12 13:56:44.255  6689  6705 E FilterInstaller: There is no requred permission
09-12 13:56:44.255  1018  1392 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:56:44.255  1018  1392 D AlarmManagerService: Setting time of day to sec=1473681404
09-12 13:56:44.255  1018  1392 D AlarmManagerService: Trying to open a file
09-12 13:56:44.265  1018  1392 D AlarmManagerService: File Open Success
09-12 13:56:44.265  1018  1392 D AlarmManagerService: File Close Success
09-12 13:56:44.265  1018  1392 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
09-12 13:56:44.972  1018  1392 W AlarmManagerService: Unable to set rtc to 1473681404: Invalid argument
09-12 13:56:44.972  1018  1096 V AlarmManager: waitForAlarm result :65536
09-12 13:56:44.972  1018  1488 I ActivityManager: Killing 5036:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-12 13:56:44.972  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=94721 batch.start=107293
09-12 13:56:44.972  1018  1018 I BackgroundCompactionService: onStart. jobID=801
09-12 13:56:44.972  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
09-12 13:56:44.972  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473681404986
09-12 13:56:44.972  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
09-12 13:56:44.972  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
09-12 13:56:44.981  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
09-12 13:56:44.981  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
09-12 13:56:44.981  1018  6707 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
09-12 13:56:44.981  1018  6707 I BackgroundCompactionService: compact_memory command done
09-12 13:56:44.991  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
09-12 13:56:45.001  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
09-12 13:56:45.001  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 13:56:45.001  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
09-12 13:56:45.011  6406  6686 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-12 13:56:45.011  6406  6686 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1460cd57: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-12 13:56:45.011  6406  6686 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-12 13:56:45.011  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 13:56:45.011  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 13:56:45.011  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 13:56:45.021  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
09-12 13:56:45.021  1018  1308 D SettingsProvider: name = lockscreen_zoom_panning_effect
09-12 13:56:45.021  1018  1308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:56:45.021  1018  1308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:56:45.021  1018  1308 D SettingsProvider: selectionArgs: false
09-12 13:56:45.021  1018  1308 D SettingsProvider: selectionArgs: 10049
09-12 13:56:45.021  1018  1308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:56:45.021  1018  1308 D SettingsProvider: ret = -1
09-12 13:56:45.021  1176  1176 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
09-12 13:56:45.031  1176  1176 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-12 13:56:45.031  1176  1176 I GeometricMosaic_Keyguard: update
09-12 13:56:45.031  1176  1176 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
09-12 13:56:45.041  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:56:45.071   287   287 E SMD     : DCD OFF
09-12 13:56:45.131  1018  1018 I DrmEventService:  no response from SecureClock 
09-12 13:56:45.131  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
09-12 13:56:45.131  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
09-12 13:56:45.131  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
09-12 13:56:45.131  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
09-12 13:56:45.131  6625  6712 D OpenGLRenderer: Render dirty regions requested: true
09-12 13:56:45.141  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-12 13:56:45.141  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.141  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.141  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.141  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.151  1176  1195 I art     : Background sticky concurrent mark sweep GC freed 26077(1240KB) AllocSpace objects, 1(16KB) LOS objects, 0% free, 20MB/20MB, paused 891us total 108.054ms
09-12 13:56:45.161  6713  6713 E Zygote  : MountEmulatedStorage()
09-12 13:56:45.161  6713  6713 E Zygote  : v2
09-12 13:56:45.161  6713  6713 I libpersona: KNOX_SDCARD checking this for 10008
09-12 13:56:45.161  6713  6713 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:45.161  6713  6713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:45.161  6713  6713 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:45.161  6713  6713 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 13:56:45.161  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6713 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:56:45.161  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 13:56:45.161  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:56:45.161  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
09-12 13:56:45.161  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 13:56:45.161  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:56:45.171  6625  6676 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-12 13:56:45.171  6625  6625 V ActivityThread: updateVisibility : ActivityRecord{929cff9 token=android.os.BinderProxy@8c451f2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 13:56:45.171  1018  1308 I ActivityManager: Killing 6271:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-12 13:56:45.181  6625  6625 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:56:45.181  6625  6625 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 13:56:45.201  6713  6713 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:45.201  6713  6713 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:45.201   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-12 13:56:45.211  1176  1176 I KeyguardEffectViewUtil: set current wallpaper info
,09-12 13:56:45.211  1018  1137 D SettingsProvider: name = keyguard_current_wallpaper_type
09-12 13:56:45.211  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:56:45.211  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:56:45.211  1018  1137 D SettingsProvider: selectionArgs: false
09-12 13:56:45.211  1018  1137 D SettingsProvider: selectionArgs: 10049
09-12 13:56:45.211  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:56:45.211  1018  1137 D SettingsProvider: ret = -1
,09-12 13:56:45.211  1018  1442 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-12 13:56:45.211  1018  1442 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:56:45.211  1018  1442 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:56:45.211  1018  1442 D SettingsProvider: selectionArgs: false
09-12 13:56:45.211  1018  1442 D SettingsProvider: selectionArgs: 10049
09-12 13:56:45.211  1018  1442 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:56:45.211  1018  1442 D SettingsProvider: ret = -1
,09-12 13:56:45.211  1018  1954 D SettingsProvider: name = keyguard_current_wallpaper_res_id
09-12 13:56:45.211  1018  1954 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:56:45.211  1018  1954 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:56:45.211  1018  1954 D SettingsProvider: selectionArgs: false
09-12 13:56:45.211  1018  1954 D SettingsProvider: selectionArgs: 10049
09-12 13:56:45.211  1018  1954 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:56:45.211  1018  1954 D SettingsProvider: ret = -1
,09-12 13:56:45.221  1018  1031 D InputDispatcher: Focus entered window: 6625
,09-12 13:56:45.221  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:56:45.221  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:56:45.231  6625  6625 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:56:45.231  6625  6712 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:56:45.231  6625  6712 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-12 13:56:45.231  6625  6712 D OpenGLRenderer: Enabling debug mode 0
,09-12 13:56:45.271  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:56:45.281  1018  6733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:56:45.281  1176  1630 D TEST    : run!!!
09-12 13:56:45.281  1176  1176 D PanelView: There is/are notification(s) 
,09-12 13:56:45.291  6713  6713 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-12 13:56:45.291  1869  1869 I SamsungIME: getCurrentCandidateView
,09-12 13:56:45.301  1176  1630 I GeometricMosaic_Renderer: setBackgroundBitmap
,09-12 13:56:45.301  1018  1048 I ActivityManager: Displayed Component not be shown by security: +933ms (total +1s65ms)
,09-12 13:56:45.301  1018  1048 W ActivityManager: mDVFSHelper.release()
09-12 13:56:45.301  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a9d96b4 u0 com.test.thalitest/.MainActivity t163} time:95057
,09-12 13:56:45.311  6625  6625 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-12 13:56:45.311  6625  6625 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8c451f2 time:95067
,09-12 13:56:45.321   257   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-12 13:56:45.321   257  1889 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-12 13:56:45.331  6713  6713 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,09-12 13:56:45.341  6625  6625 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6625
,09-12 13:56:45.351  1018  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:56:45.351  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,09-12 13:56:45.351  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:45.351  1018  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:45.351  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:56:45.381  1018  1030 I ActivityManager: Killing 6315:com.samsung.helphub/1000 (adj 15): empty #21
,09-12 13:56:45.401  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:56:45.401  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,09-12 13:56:45.401  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:45.401  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:45.401  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:56:45.411  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Sep 12 13:56:45 GMT+02:00 2016
,09-12 13:56:45.421  1869  1869 D SamsungIME: Dismiss ExpandCandiate
,09-12 13:56:45.421  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 13:56:45.421  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-12 13:56:45.421  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:45.421  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:45.421  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:56:45.431  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.,
09-12 13:56:45.431  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
09-12 13:56:45.431  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.431  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.431  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.431  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:45.431  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 13:56:45.431  2931  2931 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:56:45.441  2931  2931 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:56:45.441  6741  6741 E Zygote  : MountEmulatedStorage()
09-12 13:56:45.441  6741  6741 E Zygote  : v2
09-12 13:56:45.441  6741  6741 I libpersona: KNOX_SDCARD checking this for 10036
09-12 13:56:45.441  6741  6741 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:45.441  2931  6740 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,09-12 13:56:45.441  1018  1489 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6741 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:45.451  2931  6740 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED,
,09-12 13:56:45.451  2931  6740 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Mon Sep 12 13:56:45 GMT+02:00 2016
,09-12 13:56:45.461  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:45.461  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:56:45.461  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-12 13:56:45.461  2931  6740 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,09-12 13:56:45.461  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onDestroy(),
,09-12 13:56:45.481  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:45.481  6741  6741 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:45.521  6741  6741 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1f8426e1
,09-12 13:56:45.521  6330  6330 I Mms/MmsApp:  start initViewCache mms
,09-12 13:56:45.521  6330  6330 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1881.467811
09-12 13:56:45.521  6330  6330 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-12 13:56:45.531  6741  6741 I SA      : [SSP] onCreated
,09-12 13:56:45.561  6741  6741 I SA      : [TPM] There is no property file
,09-12 13:56:45.561  6741  6741 I SA      : [SCU] isHaveSA() - false
,09-12 13:56:45.561  6741  6741 I SA      : [TPM] getModelProperty : null
,09-12 13:56:45.571  6741  6741 I SA      : [TPM] getCSCProperty : null
,09-12 13:56:45.571  6741  6741 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-12 13:56:45.571  6741  6741 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-12 13:56:45.571  6741  6741 I SA      : [DM] TFT FEATURE: false
,09-12 13:56:45.591  6741  6741 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,09-12 13:56:45.591  6741  6741 I SA      : [DM] init START
,09-12 13:56:45.601  6741  6741 I SA      : [DM] This device is not a Vodafone
,09-12 13:56:45.601  6625  6625 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:56:45.601  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c,
09-12 13:56:45.601  6741  6741 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-12 13:56:45.601  6741  6741 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-12 13:56:45.611  6741  6741 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-12 13:56:45.621  6741  6741 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-12 13:56:45.621  6741  6741 I SA      : [SCU] isHaveSA() - false
09-12 13:56:45.621  6741  6741 I SA      : support phone number id : false
09-12 13:56:45.621  6741  6741 I SA      : [DM] Supports Ref Jpn : true
,09-12 13:56:45.621  6741  6741 I SA      : [DM] init END
,09-12 13:56:45.631  6330  6330 D AbsListView: Get MotionRecognitionManager
,09-12 13:56:45.631  1018  1488 D MotionRecognitionService:  ssp status : false
,09-12 13:56:45.641  6330  6330 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 114.166094
,09-12 13:56:45.661  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 13:56:45.681  1869  1869 I SamsungIME: KeybaordView init() : load resources
,09-12 13:56:45.701  6625  6731 D jxcore_app_log: JniHelper::setJavaVM(0xb73152b0), pthread_self() = -1216187760
,09-12 13:56:45.711  1869  1869 I SamsungIME: getCurrentKeyboard
09-12 13:56:45.711  1869  1869 I SamsungIME: getTextKeyboard
,09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:56:45.711  6625  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18d43197 added. We now have 1 listener(s)
,09-12 13:56:45.721  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-12 13:56:45.721  6625  6731 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 13:56:45.721  6625  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:56:45.721  6625  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 13:56:45.731  6625  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311ba2 added. We now have 1 listener(s)
,09-12 13:56:45.731  6625  6731 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:56:45.731  1869  1869 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-12 13:56:45.731  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:56:45.731  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 13:56:45.731  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 13:56:45.731  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:56:45.731  6625  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 13:56:45.731  1018  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:56:45.741  6330  6330 D Mms/BubbleViewCache: fillCache bubble = 1
,09-12 13:56:45.741  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,09-12 13:56:45.741  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:45.741  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:45.741  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.741  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-12 13:56:45.751  6764  6764 E Zygote  : MountEmulatedStorage()
09-12 13:56:45.751  6764  6764 E Zygote  : v2
09-12 13:56:45.751  6764  6764 I libpersona: KNOX_SDCARD checking this for 10058
09-12 13:56:45.751  6764  6764 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:45.761  6764  6764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:45.761  1018  1954 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6764 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:45.761  1018  1954 I ActivityManager: Killing 5508:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-12 13:56:45.761  6625  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:56:45.761  6625  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
09-12 13:56:45.761  6764  6764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:45.761  6764  6764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:56:45.771  6625  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:56:45.771  6625  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:56:45.771  6625  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 13:56:45.771  6625  6731 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:56:45.771  6625  6731 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:56:45.781  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:56:45.781  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:56:45.791  6764  6764 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:45.791  6764  6764 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:45.801  6625  6625 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:56:45.871  6764  6764 I ExternalOEMControlProvider: onCreate
,09-12 13:56:45.881  1018  1030 I ActivityManager: Killing 6297:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-12 13:56:45.891  6764  6780 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,09-12 13:56:45.891  1775  1775 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,09-12 13:56:45.891  1775  1775 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-12 13:56:45.891  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,09-12 13:56:45.901  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:45.901  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.901  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:45.901  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:45.911  6781  6781 E Zygote  : MountEmulatedStorage(),
09-12 13:56:45.911  6781  6781 I libpersona: KNOX_SDCARD checking this for 10081
09-12 13:56:45.911  6781  6781 E Zygote  : v2
09-12 13:56:45.911  6781  6781 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:45.911  6781  6781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:45.911  6781  6781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:45.911  1018  1954 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6781 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:45.911  6781  6781 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:56:45.941  6781  6781 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:45.941  6781  6781 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:45.961  6781  6781 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-12 13:56:45.961  6781  6781 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:56:45.961  6781  6781 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:56:45.961  6781  6781 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:56:45.961  6781  6781 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-12 13:56:46.031  1018  1954 D SettingsProvider: name = next_alarm_formatted
,09-12 13:56:46.031  1018  1954 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:56:46.031  1018  1954 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:56:46.031  1018  1954 D SettingsProvider: selectionArgs: false
09-12 13:56:46.031  1018  1954 D SettingsProvider: selectionArgs: 10081
,09-12 13:56:46.031  1018  1954 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:56:46.031  1018  1954 D SettingsProvider: ret = -1
,09-12 13:56:46.161  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:56:46.161  1018  1030 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4186, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 13:56:46.161  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 13:56:46.161  1018  1030 D BatteryService: stay LED for charging
09-12 13:56:46.161  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:56:46.161  1018  1018 I MotionRecognitionService: Plugged
,09-12 13:56:46.171  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:56:46.171  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:56:46.171  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:56:46.171  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:56:46.171  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 13:56:46.181  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:56:46.181  2778  2889 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:56:46.191  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:46.201  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:46.201  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:46.241  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 13:56:46.241  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:56:46.241  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.241  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.241  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.251  6796  6796 E Zygote  : MountEmulatedStorage(),
,09-12 13:56:46.251  6796  6796 E Zygote  : v2,
09-12 13:56:46.261  6796  6796 I libpersona: KNOX_SDCARD checking this for 10090
,09-12 13:56:46.261  6796  6796 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:46.261  6796  6796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:46.261  6796  6796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:46.261  1018  1031 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6796 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-12 13:56:46.261  6796  6796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:56:46.261  1018  1031 I ActivityManager: Killing 6366:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-12 13:56:46.281  6796  6796 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:46.281  6796  6796 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.321  6796  6796 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,09-12 13:56:46.321  6796  6796 D elm:15121: ELMEngine.ELMEngine( context ).
,09-12 13:56:46.321  6796  6796 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-12 13:56:46.321  1018  1487 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-12 13:56:46.321  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-12 13:56:46.321  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:46.321  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:46.321  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 13:56:46.331  6796  6796 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,09-12 13:56:46.331  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-12 13:56:46.331  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.331  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.331  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.331  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.331  6796  6796 D elm:15121: ElmAgentService : onCreate()
,09-12 13:56:46.331  6796  6813 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,09-12 13:56:46.341  6815  6815 E Zygote  : MountEmulatedStorage(),
,09-12 13:56:46.341  6815  6815 E Zygote  : v2
09-12 13:56:46.341  6815  6815 I libpersona: KNOX_SDCARD checking this for 10130
09-12 13:56:46.341  6815  6815 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:56:46.341  6815  6815 I libpersona: KNOX_SDCARD not a persona,
,09-12 13:56:46.351  6815  6815 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:46.351  6815  6815 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-12 13:56:46.351  1018  1031 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6815 uid=10130 gids={50130, 9997} abi=armeabi-v7a
09-12 13:56:46.351  6796  6813 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,09-12 13:56:46.361  6796  6796 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,09-12 13:56:46.361  6796  6796 D elm:15121: ModuleBase.ModifySetAlarm()
09-12 13:56:46.361  6796  6796 D elm:15121: MDMBridge.getInstance(),
09-12 13:56:46.361  6796  6796 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:56:46.361  6796  6796 D elm:15121: ElmAgentService : onDestroy().
,09-12 13:56:46.361  1018  1308 I ActivityManager: Killing 6406:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-12 13:56:46.371  6815  6815 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:46.371  6815  6815 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.391  6815  6815 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:56:46.391  6815  6815 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-12 13:56:46.401  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-12 13:56:46.401  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.401  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.401  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.401  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.421  6830  6830 E Zygote  : MountEmulatedStorage()
09-12 13:56:46.421  6830  6830 E Zygote  : v2
09-12 13:56:46.421  6830  6830 I libpersona: KNOX_SDCARD checking this for 10131
09-12 13:56:46.421  6830  6830 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:46.421  6830  6830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:46.421  6830  6830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:46.421  1018  1954 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6830 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-12 13:56:46.421  6830  6830 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-12 13:56:46.421  1018  1954 I ActivityManager: Killing 6429:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-12 13:56:46.431  6830  6830 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:46.441  6830  6830 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.461  6830  6830 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:56:46.461  6830  6830 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:56:46.461  6830  6830 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:56:46.481  6625  6774 W jxcore-log: Initializing JXcore engine
09-12 13:56:46.481  6625  6774 W jxcore-log: JXcore engine is ready
,09-12 13:56:46.501  2671  2683 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-12 13:56:46.511  1018  1954 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 13:56:46.511  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-12 13:56:46.511  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:46.511  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:46.511  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:46.531  1018  1488 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 13:56:46.531  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-12 13:56:46.531  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:46.531  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:46.531  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:46.531  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,09-12 13:56:46.541  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.541  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.541  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.541  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.541  1896  1896 E audit   : type=1400 msg=audit(1473681406.541:205): avc:  denied  { ioctl } for  pid=6774 comm="Thread-1241" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 13:56:46.541  1896  1896 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:46.541  1896  1896 E audit   : type=1300 msg=audit(1473681406.541:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f6898f8 items=0 ppid=309 ppcomm=main pid=6774 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1241" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 13:56:46.541  1896  1896 E audit   : type=1320 msg=audit(1473681406.541:205): 
,09-12 13:56:46.551  6625  6774 W jxcore-log: Starting JXcore engine
,09-12 13:56:46.561  6851  6851 E Zygote  : MountEmulatedStorage()
,09-12 13:56:46.561  6851  6851 E Zygote  : v2
09-12 13:56:46.561  6851  6851 I libpersona: KNOX_SDCARD checking this for 10037
09-12 13:56:46.561  6851  6851 I libpersona: KNOX_SDCARD not a persona,
09-12 13:56:46.561  1018  1030 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6851 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:46.561  1018  1308 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-12 13:56:46.561  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:46.561  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 13:56:46.561  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.561  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 13:56:46.561  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.561  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.561  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.581  6861  6861 E Zygote  : MountEmulatedStorage()
09-12 13:56:46.581  6861  6861 E Zygote  : v2
09-12 13:56:46.581  6861  6861 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:56:46.581  6861  6861 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:46.581  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:46.591  1018  1308 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6861 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 13:56:46.591  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:46.591  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:56:46.601  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:46.601  6851  6851 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.611   309   309 I art     : Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 657us total 25.051ms
,09-12 13:56:46.621  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:46.621  6861  6861 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.631   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 18.814ms
09-12 13:56:46.641  6851  6851 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
09-12 13:56:46.651   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 16.838ms
,09-12 13:56:46.661  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:56:46.661  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:56:46.661  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:56:46.671  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,09-12 13:56:46.671  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.671  6851  6851 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-12 13:56:46.671  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.671  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.671  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.681  6625  6774 W jxcore-log: Platform android,
09-12 13:56:46.681  6625  6774 W jxcore-log: 
09-12 13:56:46.681  6625  6774 W jxcore-log: Process ARCH arm
09-12 13:56:46.681  6625  6774 W jxcore-log: 
,09-12 13:56:46.681  6882  6882 E Zygote  : MountEmulatedStorage(),
09-12 13:56:46.681  6882  6882 E Zygote  : v2
,09-12 13:56:46.691  6882  6882 I libpersona: KNOX_SDCARD checking this for 10153
,09-12 13:56:46.691  6882  6882 I libpersona: KNOX_SDCARD not a persona
09-12 13:56:46.691  1018  1137 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6882 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,09-12 13:56:46.691  6882  6882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:46.691  6882  6882 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:56:46.691  1018  1137 I ActivityManager: Killing 6463:com.sec.pcw.device/1000 (adj 15): empty #21
09-12 13:56:46.691  6882  6882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:56:46.711  6882  6882 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:56:46.711  6882  6882 D ActivityThread: Added TimaKeyStore provider,
,09-12 13:56:46.831  1018  1454 I art     : Explicit concurrent mark sweep GC freed 19591(1117KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.582ms total 142.029ms
,09-12 13:56:46.851  6882  6882 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:56:46.861  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,09-12 13:56:46.861  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.861  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.861  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:46.861  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:46.871  1018  1487 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6898 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:56:46.871  6898  6898 E Zygote  : MountEmulatedStorage()
09-12 13:56:46.871  6898  6898 E Zygote  : v2
09-12 13:56:46.871  6898  6898 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:56:46.871  6898  6898 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:46.871  6898  6898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:56:46.871  1018  1487 I ActivityManager: Killing 5761:com.android.vending/u0a26 (adj 15): empty #21
,09-12 13:56:46.881  6898  6898 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:56:46.881  6898  6898 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:56:46.891  6898  6898 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:46.891  6898  6898 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:46.901  6625  6774 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:56:46.901  6625  6774 I jxcore-log: 
,09-12 13:56:46.901  6625  6774 W jxcore-log: JXcore engine is started
,09-12 13:56:46.911  6625  6731 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:56:46.911  6625  6625 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:56:46.921  1018  1954 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar,
09-12 13:56:46.921  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-12 13:56:46.921  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:46.921  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:46.921  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 13:56:46.941  6898  6898 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473681406953
09-12 13:56:46.941  6898  6898 D         : TimeServiceNative: User Time to be set is 1473681406954
09-12 13:56:46.941  6898  6898 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-12 13:56:46.941  6898  6898 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-12 13:56:46.941  6898  6898 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473681406954
,09-12 13:56:46.941   322   562 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-12 13:56:46.941  6898  6898 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473681406954
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473681406954, operation = 0
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/10/71 5:39:26
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:Value read from RTC seconds = 37431566000
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:new time 1473681406954 
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon: delta 1436249840954 genoff 1436249840954 
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249840954 to memory
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-12 13:56:46.941   322  6917 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-12 13:56:46.971   322  6917 D QC-time-services: Updating the TOD offset
09-12 13:56:46.971   322  6917 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249840954 to memory
09-12 13:56:46.971   322  6917 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-12 13:56:46.971   322  6917 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-12 13:56:46.971   322  6917 E QC-time-services: Daemon:Update to modem bit set
09-12 13:56:46.971   322  6917 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-12 13:56:46.971   322  6917 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285040954
,09-12 13:56:46.971  6898  6898 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-12 13:56:46.971   322   559 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,09-12 13:56:46.971   322   562 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
09-12 13:56:46.971  1018  1487 I ActivityManager: Killing 6380:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-12 13:56:46.981  1018  1454 I ActivityManager: Killing 6513:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-12 13:56:46.981  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-12 13:56:46.981  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-12 13:56:46.981  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-12 13:56:46.991  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-12 13:56:46.991  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-12 13:56:47.001  2671  2671 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,09-12 13:56:47.001  2671  2671 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-12 13:56:47.001  2671  2671 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,09-12 13:56:47.001  2671  2671 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,09-12 13:56:47.001  2671  2671 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-12 13:56:47.001  2671  2671 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,09-12 13:56:47.001  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-12 13:56:47.001  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,09-12 13:56:47.011  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-12 13:56:47.011  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-12 13:56:47.011  2671  2671 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,09-12 13:56:47.011  2671  2671 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-12 13:56:47.011  2671  2671 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,09-12 13:56:47.021  2671  2671 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,09-12 13:56:47.021  2671  2671 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,09-12 13:56:47.281   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a417c8,
09-12 13:56:47.281   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-12 13:56:47.281   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
,09-12 13:56:47.281   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197205368)
,09-12 13:56:47.321   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
09-12 13:56:47.321   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,09-12 13:56:47.321   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197205368) wakelock released: 1, error no: 0
09-12 13:56:47.321   272   338 I rmt_storage: 
,09-12 13:56:47.321   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8a417c8
,09-12 13:56:47.931  6851  6851 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-12 13:56:47.931  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:47.931  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:47.931  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-12 13:56:47.941  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-12 13:56:47.941  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:47.941  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:47.941  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 13:56:47.941  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:47.941  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:47.941  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:47.951  1018  1030 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 13:56:47.951  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-12 13:56:47.951  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:47.951  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:47.951  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:47.961  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:47.961  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:56:47.961  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:47.961  1018  1954 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-12 13:56:47.961  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-12 13:56:47.961  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:47.961  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:56:47.961  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 13:56:47.971  1018  1489 I ActivityManager: Killing 6533:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-12 13:56:48.071   287   287 E SMD     : DCD OFF
,09-12 13:56:48.931  1698  1698 I ConfigService: onDestroy
,09-12 13:56:51.071   287   287 E SMD     : DCD OFF
,09-12 13:56:52.511  1018  2857 D SSRM:n  : SIOP:: AP = 420
,09-12 13:56:54.081   287   287 E SMD     : DCD OFF,
,09-12 13:56:54.081  1018  1058 D PackageManager: [MSG] MCS_UNBIND
,09-12 13:56:54.091  1018  1489 I ActivityManager: Killing 6548:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-12 13:56:54.241  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-12 13:56:56.211  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:56:56.211  1018  1137 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 13:56:56.221  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-12 13:56:56.221  1018  1137 D BatteryService: stay LED for charging
09-12 13:56:56.221  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:56:56.221  1018  1018 I MotionRecognitionService: Plugged
,09-12 13:56:56.221  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:56:56.221  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:56:56.221  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:56:56.221  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:56:56.221  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 13:56:56.241  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:56:56.241  2778  2889 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:56:56.251  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:56.251  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:56.251  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:56:57.081   287   287 E SMD     : DCD OFF
,09-12 13:56:57.541  1018  1096 V AlarmManager: waitForAlarm result :4,
09-12 13:56:57.541  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-12 13:56:57.541  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:56:57.541  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:57.541  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:56:57.541  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:56:57.561  6924  6924 E Zygote  : MountEmulatedStorage(),
09-12 13:56:57.561  1018  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6924 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:56:57.561  6924  6924 E Zygote  : v2
09-12 13:56:57.561  6924  6924 I libpersona: KNOX_SDCARD checking this for 10026
09-12 13:56:57.561  6924  6924 I libpersona: KNOX_SDCARD not a persona
,09-12 13:56:57.561  6924  6924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:56:57.561  6924  6924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:56:57.561  6924  6924 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-12 13:56:57.591  6924  6924 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:56:57.591  6924  6924 D ActivityThread: Added TimaKeyStore provider
,09-12 13:56:57.611  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{1fe90b51 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,09-12 13:56:57.661  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.671  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.711  6924  6924 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 13:56:57.711  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.811  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.811  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.821  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.821  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.831  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.831  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.831  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.831  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.831  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.841  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.851  6924  6924 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-12 13:56:57.861  6924  6924 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 13:56:57.861  6924  6924 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 13:56:57.891  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.891  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.891  6924  6924 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-12 13:56:57.921  6924  6960 D Ads     : Skipping gmscore version check
,09-12 13:56:57.921  6924  6924 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-12 13:56:57.931  1018  1137 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-12 13:56:57.931  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-12 13:56:57.931  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:56:57.931  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:57.931  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-12 13:56:57.941  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:56:57.941  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:56:57.941  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:56:57.941  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-12 13:56:57.951  6924  6924 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-12 13:56:57.961  6924  6924 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 13:56:57.981  1018  1307 E Watchdog: !@Sync 3
,09-12 13:56:58.131  6924  6957 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-12 13:56:58.131  6924  6924 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-12 13:56:58.141  1018  1030 I ActivityManager: Killing 6569:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-12 13:56:59.101   319   319 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-12 13:56:59.101   319   319 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 13:56:59.271  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:56:59.271  6625  6774 I jxcore-log: 
,09-12 13:56:59.271  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:56:59.271  6625  6774 I jxcore-log: 
,09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:56:59.281  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:56:59.281  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:56:59.291  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:56:59.291  6625  6774 I jxcore-log: 
,09-12 13:56:59.291  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:56:59.291  6625  6774 I jxcore-log: 
,09-12 13:56:59.951  6625  6774 I jxcore-log: Unit Test app is loaded
09-12 13:56:59.951  6625  6774 I jxcore-log: 
,09-12 13:56:59.961  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:56:59.961  6625  6774 I jxcore-log: 
,09-12 13:56:59.961  6625  6625 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 13:56:59.971  6625  6774 D executeNativeTests: Running unit tests
,09-12 13:56:59.971  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:56:59.971  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdcc324 added. We now have 2 listener(s)
,09-12 13:56:59.971  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:56:59.971  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:56:59.971  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:56:59.971  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:56:59.971  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@324c3e8d added. We now have 2 listener(s)
09-12 13:56:59.971  6625  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:56:59.971  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:56:59.971  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:56:59.981  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:56:59.981  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:56:59.981  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:56:59.981  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:56:59.981  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:56:59.981  1018  1096 V AlarmManager: waitForAlarm result :8
,09-12 13:57:00.081   287   287 E SMD     : DCD OFF,
,09-12 13:57:02.321  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-12 13:57:02.551  1018  2857 D SSRM:n  : SIOP:: AP = 400,
,09-12 13:57:03.091   287   287 E SMD     : DCD OFF
,09-12 13:57:04.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:05.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:05.751  1018  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-12 13:57:06.081   287   287 E SMD     : DCD OFF,
,09-12 13:57:06.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:06.271  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-12 13:57:06.271  1018  1137 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 13:57:06.271  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-12 13:57:06.271  1018  1137 D BatteryService: stay LED for charging,
,09-12 13:57:06.271  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:57:06.281  1018  1018 I MotionRecognitionService: Plugged
,09-12 13:57:06.281  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:57:06.281  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-12 13:57:06.281  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:57:06.281  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:57:06.281  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 13:57:06.301  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:57:06.301  2778  2889 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:57:06.311  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:06.311  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:06.311  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:06.801  5917  5917 D FactoryTest: Not factory mode
,09-12 13:57:06.801  5917  5917 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 13:57:06.801  5917  5917 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-12 13:57:06.801  5917  5917 D MTPRx   : still no open session command from host, so toast
,09-12 13:57:06.801  5917  5917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
09-12 13:57:06.801  5917  5917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-12 13:57:06.811  5917  5917 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116559,
09-12 13:57:06.811  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
09-12 13:57:06.811  1018  1030 I PersonaManagerService: PersonaId don't exist
09-12 13:57:06.811  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 13:57:06.811  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-12 13:57:06.811  1018  1030 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:06.811  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:06.811  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,09-12 13:57:06.821  1018  1030 W ActivityManager: mDVFSHelper.acquire(),
,09-12 13:57:06.841  1018  1030 D PersonaManager: isKioskContainerExistOnDevice,
,09-12 13:57:06.841  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:57:06.841  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-12 13:57:06.841  1018  1030 D InputDispatcher: Focused application set to: xxxx
,09-12 13:57:06.841  1018  1030 D InputDispatcher: Focus left window: 6625
,09-12 13:57:06.851  5917  5917 E MTPRx   : started activity for popup
,09-12 13:57:06.851  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:57:06.851  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:57:06.871  5917  5917 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:57:06.901  5917  5917 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 13:57:06.901  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 13:57:06.901  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:57:06.901  1018  1487 D InputDispatcher: Focused application set to: xxxx
,09-12 13:57:06.901  1018  1487 D InputDispatcher: Focus entered window: 6625
,09-12 13:57:06.901  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:57:06.901  1018  1308 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:57:06.911  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:57:06.911  1018  1308 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@28f9a53c attribute=null, token = android.os.BinderProxy@11a6d798
,09-12 13:57:06.941  5917  5917 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-12 13:57:06.941  5917  5917 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-12 13:57:06.941  5917  5917 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 13:57:06.961  6625  6625 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:57:06.961  6625  6625 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-12 13:57:06.961  6625  6625 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 13:57:06.961  6625  6625 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 13:57:06.971  1018  1952 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 13:57:06.971  1018  1952 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-12 13:57:06.971  1018  1952 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 13:57:06.971  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:57:06.971  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:57:06.981  6625  6625 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:57:06.981  6625  6625 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 13:57:06.981  6625  6625 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8c451f2 time:116737
,09-12 13:57:06.981  6625  6625 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@30cd728e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1fc9053, 16908290=android.view.AbsSavedState$1@1fc9053}, android:focusedViewId=100}]}]
09-12 13:57:06.981  6625  6625 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 13:57:06.981  6625  6625 V ActivityThread: updateVisibility : ActivityRecord{929cff9 token=android.os.BinderProxy@8c451f2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 13:57:06.981  6625  6625 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:57:06.981  6625  6625 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 13:57:06.991  1018  1488 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:57:07.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:08.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:09.091   287   287 E SMD     : DCD OFF
,09-12 13:57:09.111   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-12 13:57:09.831  1018  1043 W ActivityManager: mDVFSHelper.release(),
,09-12 13:57:10.091  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:57:10.091  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 added. We now have 3 listener(s)
,09-12 13:57:10.101  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 13:57:10.101  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:10.101  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:57:10.101  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:10.101  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 added. We now have 3 listener(s)
,09-12 13:57:10.101  6625  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:57:10.101  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:57:10.101  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:10.101  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:10.111  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:10.111  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:10.111  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:10.111  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:10.111  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:57:10.121  6625  6774 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 13:57:10.121  6625  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 13:57:10.121  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:57:10.121  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:10.121  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:10.121  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:10.121  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 removed from the list
09-12 13:57:10.121  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:10.121  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 removed from the list
09-12 13:57:10.121  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:57:10.121  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 13:57:10.131  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:10.131  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:10.131  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:10.131  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:10.131  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:10.131  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:10.131  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:10.131  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:57:10.131  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:10.131  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:10.131  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:10.131  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:10.131  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:10.131  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:10.131  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:10.131  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:10.131  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:10.141  6625  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-12 13:57:10.141  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:10.141  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:10.141  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:10.141  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:10.151  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-12 13:57:10.151  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:10.151  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:10.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:10.151  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:10.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-12 13:57:10.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:10.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:57:10.151  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:10.151  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:57:10.161  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:10.161  6625  6968 D BluetoothSocket: bindListen(): myUserId = 0,
09-12 13:57:10.161  6625  6968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:10.171  6625  6968 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-12 13:57:10.171  6625  6968 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:10.171  6625  6968 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:10.171  6625  6968 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ff2b6b5
09-12 13:57:10.171  6625  6968 D BluetoothSocket: channel: 6
09-12 13:57:10.171  6625  6968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:57:10.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:10.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:10.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-12 13:57:10.181  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:57:10.181  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 75 41
,09-12 13:57:10.181  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:57:10.181  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:10.181  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:10.191  2778  2788 D BtGatt.GattService: registerClient() - UUID=fdb39cf1-d5f1-43d1-8966-017bce322497
,09-12 13:57:10.231  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=fdb39cf1-d5f1-43d1-8966-017bce322497, clientIf=6
,09-12 13:57:10.231  6625  6639 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:10.241  2778  2887 D BtGatt.AdvertiseManager: message : 0
,09-12 13:57:10.241  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0
,09-12 13:57:10.241  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:10.241  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:10.241  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:10.251  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:10.261  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:10.261  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:10.261  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:10.261  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:10.271  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
09-12 13:57:10.271  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:10.271  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:10.271  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:10.281  6625  6774 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:57:10.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:10.281  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:57:10.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:57:10.281  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:57:10.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:10.281  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:10.291  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:10.781  6625  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:57:10.781  6625  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:57:10.781  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-12 13:57:10.781  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:57:10.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:10.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:10.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:10.781  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8dbe8bb, channel: 6, state: LISTENING
09-12 13:57:10.781  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8dbe8bb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ff2b6b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22d41d8mSocket: android.net.LocalSocket@3c650931 impl:android.net.LocalSocketImpl@cb80816 fd:FileDescriptor[105]
09-12 13:57:10.781  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c650931 impl:android.net.LocalSocketImpl@cb80816 fd:FileDescriptor[105]
09-12 13:57:10.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:57:10.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:10.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:57:10.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:10.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:10.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:57:10.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:10.781  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 13:57:10.781  6625  6968 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8dbe8bb, channel: 6, state: CLOSED
,09-12 13:57:10.781  6625  6968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:10.781  6625  6968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:10.781  6625  6968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:10.781  6625  6774 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:57:10.791  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:10.791  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:57:10.791  2778  2887 D BtGatt.AdvertiseManager: message : 1
,09-12 13:57:10.791  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-12 13:57:10.791  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-12 13:57:10.791  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-12 13:57:10.791  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-12 13:57:10.791  2778  2837 D BtGatt.GattService: Client app is not null!
,09-12 13:57:10.791  2778  2792 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:10.801  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:10.801  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:57:10.801  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:57:10.801  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:57:10.801  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:57:10.801  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:10.801  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:57:10.801  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:10.811  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:10.811  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:57:10.811  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:57:10.811  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:10.811  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:10.811  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:10.811  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-12 13:57:10.811  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:10.811  6625  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-12 13:57:10.811  6625  6774 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-12 13:57:10.811  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-12 13:57:10.811  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-12 13:57:10.811  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:10.811  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:10.811  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:10.811  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:10.821  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:10.821  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 13:57:10.821  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 13:57:10.821  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
09-12 13:57:10.821  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:10.821  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:10.821  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:10.821  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:57:10.821  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:57:10.831  6625  6972 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:57:10.831  6625  6972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:10.831  6625  6972 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-12 13:57:10.831  6625  6972 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:10.831  6625  6972 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:10.831  6625  6972 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd0076d
09-12 13:57:10.831  6625  6972 D BluetoothSocket: channel: 6
09-12 13:57:10.831  6625  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:57:10.831  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:10.831  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:10.841  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:57:10.841  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:57:10.841  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 75 41
09-12 13:57:10.841  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:10.841  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:57:10.841  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:10.841  2778  2788 D BtGatt.GattService: registerClient() - UUID=7933593f-d704-4ea7-8b79-8a1d32330d30
,09-12 13:57:10.881  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=7933593f-d704-4ea7-8b79-8a1d32330d30, clientIf=6
,09-12 13:57:10.881  6625  6639 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:10.881  2778  2887 D BtGatt.AdvertiseManager: message : 0
,09-12 13:57:10.891  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0
09-12 13:57:10.891  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:10.891  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:10.891  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:10.901  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:10.901  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:10.901  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:10.901  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:10.901  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:10.901  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:57:10.901  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:10.911  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:10.911  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:10.911  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:10.911  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-12 13:57:10.911  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:57:10.911  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:57:10.911  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:10.921  6625  6774 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:57:10.921  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:10.921  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:11.421  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-12 13:57:11.421  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1fa0b433, channel: 6, state: LISTENING
09-12 13:57:11.421  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1fa0b433, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd0076d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c673f0mSocket: android.net.LocalSocket@2772ad69 impl:android.net.LocalSocketImpl@4e003ee fd:FileDescriptor[105]
09-12 13:57:11.421  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2772ad69 impl:android.net.LocalSocketImpl@4e003ee fd:FileDescriptor[105]
09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:57:11.421  6625  6972 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1fa0b433, channel: 6, state: CLOSED
09-12 13:57:11.421  6625  6972 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:11.421  6625  6972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:11.421  6625  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:11.421  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:11.421  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:11.421  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:11.421  6625  6774 D BluetoothLeScanner: could not find callback wrapper
09-12 13:57:11.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-12 13:57:11.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 13:57:11.421  2778  2887 D BtGatt.AdvertiseManager: message : 1
09-12 13:57:11.421  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
09-12 13:57:11.421  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-12 13:57:11.431  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-12 13:57:11.431  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-12 13:57:11.431  2778  2837 D BtGatt.GattService: Client app is not null!
09-12 13:57:11.431  2778  2788 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:57:11.431  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:57:11.431  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:57:11.431  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:11.431  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:57:11.431  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.431  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:11.431  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
,09-12 13:57:11.431  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.431  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 13:57:11.441  6625  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-12 13:57:11.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:11.441  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:11.451  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:11.451  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:11.451  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.451  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.451  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-12 13:57:11.451  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-12 13:57:11.461  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:11.461  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:11.461  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:11.461  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,09-12 13:57:11.461  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
09-12 13:57:11.461  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:57:11.471  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:11.471  6625  6977 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:57:11.471  6625  6977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:11.471  6625  6977 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-12 13:57:11.471  6625  6977 D BluetoothSocket: bindListen(), new LocalSocket 
,09-12 13:57:11.471  6625  6977 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-12 13:57:11.471  6625  6977 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26cc70fa
09-12 13:57:11.471  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:11.471  6625  6977 D BluetoothSocket: channel: 6
09-12 13:57:11.471  6625  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:57:11.471  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:11.481  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:57:11.481  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 13:57:11.481  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 75 41
,09-12 13:57:11.481  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:57:11.481  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:57:11.481  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:11.481  2778  2788 D BtGatt.GattService: registerClient() - UUID=40e14e36-31e2-4fa9-ae33-0f438d3f45a0
,09-12 13:57:11.531  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=40e14e36-31e2-4fa9-ae33-0f438d3f45a0, clientIf=6
,09-12 13:57:11.531  6625  6633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:11.531  2778  2887 D BtGatt.AdvertiseManager: message : 0
,09-12 13:57:11.531  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0
,09-12 13:57:11.531  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:11.531  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:11.531  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:11.541  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:11.541  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:11.541  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:11.551  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:11.551  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:11.551  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-12 13:57:11.551  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:11.551  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:11.551  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:11.551  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:11.551  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:57:11.551  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:57:11.551  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:57:11.551  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:11.561  6625  6774 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:57:11.561  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:11.561  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:11.561  6625  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:57:11.561  6625  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:57:11.561  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 13:57:11.561  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:57:11.561  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 13:57:11.561  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:11.561  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
09-12 13:57:11.561  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2be0d108, channel: 6, state: LISTENING
,09-12 13:57:11.571  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2be0d108, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26cc70fa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2299a0a1mSocket: android.net.LocalSocket@27e0a2c6 impl:android.net.LocalSocketImpl@1761d287 fd:FileDescriptor[105]
09-12 13:57:11.571  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27e0a2c6 impl:android.net.LocalSocketImpl@1761d287 fd:FileDescriptor[105]
,09-12 13:57:11.571  6625  6977 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2be0d108, channel: 6, state: CLOSED
09-12 13:57:11.571  6625  6977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:11.571  6625  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:11.571  6625  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:11.571  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:11.571  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left,
09-12 13:57:11.571  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:11.571  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:57:11.571  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:11.571  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:11.571  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-12 13:57:11.571  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:11.571  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:11.571  6625  6774 D BluetoothLeScanner: could not find callback wrapper,
09-12 13:57:11.571  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:11.571  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:57:11.571  2778  2887 D BtGatt.AdvertiseManager: message : 1
09-12 13:57:11.571  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-12 13:57:11.571  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-12 13:57:11.571  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-12 13:57:11.591  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-12 13:57:11.591  2778  2837 D BtGatt.GattService: Client app is not null!
,09-12 13:57:11.591  2778  2788 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:57:11.591  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:57:11.591  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:57:11.591  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:11.591  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:57:11.591  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:57:11.591  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.591  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.591  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:11.591  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.591  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:11.591  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.591  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.591  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.591  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.591  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.601  6625  6774 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
,09-12 13:57:11.601  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.601  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.601  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.601  6625  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.601  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.601  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.601  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.601  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.601  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.611  6625  6774 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.611  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.611  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.611  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.611  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 13:57:11.611  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.611  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:11.611  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.611  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.611  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.611  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.611  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.611  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.611  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.611  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:11.611  6625  6774 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 13:57:11.611  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:11.611  6625  6774 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:57:11.611  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:57:11.611  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:57:11.611  6625  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:57:11.611  6625  6774 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:57:11.611  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 13:57:11.611  6625  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:57:11.611  6625  6774 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:57:11.611  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:11.611  6625  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-12 13:57:11.611  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:57:11.621  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-12 13:57:11.621  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 13:57:11.621  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 13:57:11.621  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55,
09-12 13:57:11.621  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:57:11.621  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:57:11.621  6625  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:57:11.621  6625  6774 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1341)
09-12 13:57:11.631  6625  6774 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.631  6625  6982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1341
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:57:11.631  6625  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:11.631  6625  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:57:11.631  6625  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:11.631  6625  6774 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-12 13:57:11.631  6625  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:11.631  6625  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.631  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.631  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.631  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.631  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.631  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.631  6625  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-12 13:57:11.641  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.641  6625  6981 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null,
09-12 13:57:11.641  6625  6981 D BluetoothSocket: connect(): myUserId = 0
09-12 13:57:11.641  6625  6981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,09-12 13:57:11.641  2778  2788 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-12 13:57:11.641  6625  6981 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:11.641  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:11.651  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:11.651  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:11.651  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-12 13:57:11.651  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:11.651  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:11.651  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:11.651  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:57:11.651  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:11.651  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:57:11.651  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.661  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:11.661  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.661  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:57:11.661  6625  6983 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:57:11.661  6625  6983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:11.661  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:11.661  6625  6983 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-12 13:57:11.661  6625  6983 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:11.661  6625  6983 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:11.661  6625  6983 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7f1023
09-12 13:57:11.661  6625  6983 D BluetoothSocket: channel: 6
09-12 13:57:11.661  6625  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:57:11.661  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:11.671  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-12 13:57:11.671  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:57:11.671  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 75 41
09-12 13:57:11.671  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:11.671  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:11.671  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:11.671  2778  2788 D BtGatt.GattService: registerClient() - UUID=39169371-eb68-442a-b1b4-7593c4b887aa,
,09-12 13:57:11.711  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=39169371-eb68-442a-b1b4-7593c4b887aa, clientIf=6,
09-12 13:57:11.711  6625  6633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:11.711  2778  2887 D BtGatt.AdvertiseManager: message : 0,
,09-12 13:57:11.711  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0,
,09-12 13:57:11.711  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:11.721  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:11.721  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:11.721  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:11.721  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:11.721  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:11.721  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:11.731  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:11.731  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-12 13:57:11.731  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:11.731  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:11.731  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:11.731  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:11.731  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:57:11.731  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:57:11.731  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:57:11.731  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:11.741  6625  6774 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:57:11.741  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:57:11.741  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:11.741  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fd4c2d9, channel: 6, state: LISTENING
09-12 13:57:11.741  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fd4c2d9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7f1023, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dcb449emSocket: android.net.LocalSocket@2ea88b7f impl:android.net.LocalSocketImpl@1b7e474c fd:FileDescriptor[105]
09-12 13:57:11.741  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ea88b7f impl:android.net.LocalSocketImpl@1b7e474c fd:FileDescriptor[105]
,09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:11.741  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:11.741  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 13:57:11.741  6625  6983 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fd4c2d9, channel: 6, state: CLOSED
09-12 13:57:11.741  6625  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:11.741  6625  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:11.741  6625  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:11.741  6625  6774 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:57:11.741  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:11.741  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:57:11.741  2778  2887 D BtGatt.AdvertiseManager: message : 1
,09-12 13:57:11.741  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-12 13:57:11.741  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-12 13:57:11.751  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-12 13:57:11.751  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-12 13:57:11.751  2778  2837 D BtGatt.GattService: Client app is not null!
,09-12 13:57:11.751  2778  2788 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:11.751  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:11.751  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:57:11.751  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:57:11.751  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:57:11.751  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-12 13:57:11.751  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:11.761  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.761  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.761  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:11.761  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:11.761  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.761  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.761  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.761  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:11.761  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.761  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:57:11.761  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:11.761  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:11.761  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
,09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:11.761  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:11.761  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:11.761  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.771  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:11.771  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 13:57:11.771  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
,09-12 13:57:11.771  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 13:57:11.771  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.771  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 13:57:11.771  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.771  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:11.771  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:11.771  6625  6987 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:57:11.771  6625  6987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:11.771  6625  6774 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage,
09-12 13:57:11.771  6625  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:57:11.771  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-12 13:57:11.771  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:57:11.771  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:57:11.771  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:11.771  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:11.771  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.771  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.771  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 13:57:11.771  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.771  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.771  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:11.771  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.771  6625  6987 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
09-12 13:57:11.771  6625  6987 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:11.771  6625  6987 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-12 13:57:11.771  6625  6987 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7a30caa
09-12 13:57:11.771  6625  6987 D BluetoothSocket: channel: 6
09-12 13:57:11.771  6625  6987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23c4609b, channel: 6, state: LISTENING
09-12 13:57:11.771  6625  6987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23c4609b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7a30caa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22ee8c38mSocket: android.net.LocalSocket@399af411 impl:android.net.LocalSocketImpl@137d4976 fd:FileDescriptor[107]
,09-12 13:57:11.771  6625  6987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@399af411 impl:android.net.LocalSocketImpl@137d4976 fd:FileDescriptor[107]
09-12 13:57:11.771  6625  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:11.771  6625  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:11.771  6625  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:11.771  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:11.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.781  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:11.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.781  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 13:57:11.781  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.781  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:57:11.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:57:11.781  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.781  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e6dac0 not in the list
09-12 13:57:11.781  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:11.781  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2471d3f9 not in the list
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:11.781  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:11.781  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:57:11.781  6625  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:11.781  6625  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:57:11.781  6625  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 13:57:11.781  6625  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:57:11.781  6625  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:57:11.781  6625  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:57:11.781  6625  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 13:57:11.791  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:57:11.791  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ffe6b77 added. We now have 3 listener(s)
,09-12 13:57:11.791  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:57:11.791  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:11.791  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-12 13:57:11.791  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:57:11.791  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191c33e4 added. We now have 3 listener(s)
09-12 13:57:11.791  6625  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:11.791  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:57:11.791  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:11.791  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:11.801  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:11.801  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:11.801  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.801  6625  6774 D BluetoothAdapter: enable()
,09-12 13:57:11.801  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:11.801  6625  6774 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 13:57:11.801  1018  1954 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-12 13:57:11.801  1018  1954 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:11.801  1018  1954 D SecContentProvider2: mCursor = null
09-12 13:57:11.801  1018  1954 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:11.811  1018  1954 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,09-12 13:57:11.811  1018  1954 W WifiService: Failed getting userId using ActivityManagerNative,
09-12 13:57:11.811  1018  1954 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:11.811  1018  1954 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:11.811  1018  1954 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:11.811  1018  1954 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:11.811  1018  1954 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:11.811  1018  1954 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:11.811  1018  1954 D SettingsProvider: name = wifi_on
,09-12 13:57:11.821  1018  1454 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:11.821  1018  1454 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:11.821  1018  1454 D SecContentProvider2: mCursor = null
,09-12 13:57:11.821  1018  1454 D WifiService: setWifiEnabled: false pid=6625, uid=10170
,09-12 13:57:11.821  1018  1454 D SettingsProvider: name = wifi_on
,09-12 13:57:11.831  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:57:11.831  1382  1382 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:57:11.831  1382  1382 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 13:57:11.831  1382  1382 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:57:11.831  1382  1382 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:57:11.831  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:57:11.861  1018  1127 E WifiNative-wlan0: do suspend true,
,09-12 13:57:12.011  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
09-12 13:57:12.011  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-12 13:57:12.021  1382  1382 I wpa_supplicant: nl80211: Received scan results (17 BSSes),
,09-12 13:57:12.021  1018  1126 D WifiP2pService: InactiveState{ what=147461 },
09-12 13:57:12.021  1018  1126 D WifiP2pService: P2pEnabledState{ what=147461 },
09-12 13:57:12.021  1018  1126 D WifiP2pService: DefaultState{ what=147461 }
,09-12 13:57:12.031  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:57:12.031  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:57:12.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.031   277  1017 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:12.031  1698  2532 V NativeCrypto: Read error: ssl=0xb784bb10: I/O error during system call, Connection timed out
,09-12 13:57:12.041  1698  2532 V NativeCrypto: SSL shutdown failed: ssl=0xb784bb10: I/O error during system call, Broken pipe
09-12 13:57:12.041  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:12.041  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:12.041  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:12.041  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-12 13:57:12.051  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:57:12.051  1018  1329 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011,
,09-12 13:57:12.061  1018  1126 D WifiP2pService: InactiveState{ what=131204 },
09-12 13:57:12.061  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:57:12.071  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 13:57:12.081  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1,
09-12 13:57:12.081  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-12 13:57:12.081  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:12.081  1018  1153 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:12.081  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-21ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:12.081  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:12.081  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-21ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:12.081  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:57:12.081  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:57:12.081  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:12.081  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-12 13:57:12.081   287   287 E SMD     : DCD OFF
,09-12 13:57:12.081  1018  1758 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 13:57:12.091  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:12.091  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:12.091  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:12.091  1018  1758 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.091  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.091  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:57:12.091  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:57:12.091  1018  1758 I qtaguid : Untagging socket 352
09-12 13:57:12.101  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:57:12.091  1018  1758 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 13:57:12.101  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:57:12.091  1625  1625 I Hs20UtilService: Starting #8
,09-12 13:57:12.101  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:12.101  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 13:57:12.111  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:57:12.111  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:57:12.111  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:57:12.111  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:57:12.111  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:12.111  1018  1048 D WifiDisplayController: disconnect
09-12 13:57:12.111  1018  1048 D WifiDisplayController: updateConnection
09-12 13:57:12.111  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:12.111  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:57:12.111  1018  1126 D WifiP2pService: P2pDisablingState
,09-12 13:57:12.111  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:12.111  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:12.111  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:57:12.111  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:57:12.111  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:57:12.111  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:57:12.121  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:57:12.121  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-12 13:57:12.121  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:12.121  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:57:12.121  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:12.121  1018  1329 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:57:12.121  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:57:12.131  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:57:12.131  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:57:12.131  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:57:12.131  1018  1126 D WifiP2pService: p2p socket connection lost
09-12 13:57:12.131  1018  1127 E WifiNative-wlan0: do suspend true
,09-12 13:57:12.131  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:57:12.131  1018  1126 D WifiP2pService: P2pDisabledState
,09-12 13:57:12.131  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-12 13:57:12.131  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:12.131  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:57:12.131  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 13:57:12.131  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 13:57:12.131  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.131  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.131  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:12.131  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.151  6994  6994 E Zygote  : MountEmulatedStorage()
09-12 13:57:12.151  6994  6994 E Zygote  : v2
09-12 13:57:12.151  6994  6994 I libpersona: KNOX_SDCARD checking this for 10064
09-12 13:57:12.151  6994  6994 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:12.151  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:12.151  1018  1952 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6994 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-12 13:57:12.151  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:12.151  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:12.161  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 13:57:12.161  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.171  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.171  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:12.171   277  1017 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:12.171   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:12.171   277  1013 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-12 13:57:12.171  6994  6994 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:12.171  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.171  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-12 13:57:12.171  1018  1129 V NetworkStats: updateIfacesLocked()
09-12 13:57:12.181  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:12.171  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:12.181  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:57:12.181  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-12 13:57:12.181  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 13:57:12.181  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:57:12.181  1382  1382 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:57:12.181  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.181  1018  1129 V NetworkStats: performPollLocked() took 8ms
,09-12 13:57:12.191  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-12 13:57:12.191  1018  1758 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:12.191  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:57:12.191  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:57:12.191  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.191  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.191  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:12.191  1018  1127 D SecContentProvider2: mCursor = null
09-12 13:57:12.191  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:57:12.191  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 13:57:12.191  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 13:57:12.191  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 13:57:12.191  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:57:12.191  1459  1459 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:57:12.191  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.201  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.201  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.201  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:12.201  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.201  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 13:57:12.211  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.211  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.211  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.211  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:12.211  6994  6994 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:57:12.211  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-12 13:57:12.211  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 13:57:12.211  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:57:12.211  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:12.211  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:57:12.211  1018  1124 V NetworkStats: updateIfacesLocked()
09-12 13:57:12.211  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.211  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:12.211  1176  1176 D HotspotTile: onReceive : 0, 0
,09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:12.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:12.211  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:12.211  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:12.221  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
,09-12 13:57:12.221  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 13:57:12.221  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:12.221  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:57:12.221  1018  1129 E ConnectivityService: updateNetworkInfo()
,09-12 13:57:12.221  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 13:57:12.221  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.221  1018  1124 V NetworkStats: performPollLocked() took 7ms
09-12 13:57:12.221  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:12.221  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.221  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.221  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.221  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:12.221  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:12.231  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:12.231  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-12 13:57:12.231  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.231  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.231  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:12.231  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 13:57:12.241  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:57:12.241  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:57:12.241  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:57:12.241  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:12.241  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:12.241  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 13:57:12.241  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:57:12.251  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:12.251  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:57:12.251  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 13:57:12.251  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 13:57:12.251  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.261  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:12.261  1382  1382 I wpa_supplicant: Blacklist: Clear (all) ,
,09-12 13:57:12.271  6994  6994 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:57:12.271  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:57:12.281  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 13:57:12.281  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.281  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.281  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:12.281  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.291  1018  1043 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7012 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:57:12.291  7012  7012 E Zygote  : MountEmulatedStorage()
09-12 13:57:12.291  7012  7012 I libpersona: KNOX_SDCARD checking this for 10065
09-12 13:57:12.291  7012  7012 E Zygote  : v2
09-12 13:57:12.291  7012  7012 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:12.291  7012  7012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:12.291  1018  1954 I ActivityManager: Killing 6591:com.wsomacp/u0a23 (adj 15): empty #21
,09-12 13:57:12.291  7012  7012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:12.301  7012  7012 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:12.321  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:57:12.321  1382  1382 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 13:57:12.321  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:12.321  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:12.321  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:12.321  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:57:12.321  7012  7012 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:12.321  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:57:12.321  7012  7012 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:12.321  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.331  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.331  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.331  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.331  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.331  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.331  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.331  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.341  1018  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:57:12.341  1018  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:12.341  1018  1489 D SecContentProvider2: mCursor = null
09-12 13:57:12.341  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.341  1018  1489 D WifiService: setWifiEnabled: true pid=6625, uid=10170
09-12 13:57:12.341  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:57:12.341  1018  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:12.341  1018  1489 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:12.341  1018  1489 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:12.341  1018  1489 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:12.341  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:12.341  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:12.341  1018  1489 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:12.341  1018  1489 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:12.341  1018  1489 D SettingsProvider: name = wifi_on
,09-12 13:57:12.341  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.341  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.341  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.341  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.351  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.351  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.351  7012  7012 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:12.351  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:57:12.351  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.351  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.351  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.351  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:57:12.351  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.361  1018  1329 I ActivityManager: Killing 6609:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-12 13:57:12.361  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.361  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:57:12.361  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:57:12.361  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:57:12.361  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:12.361  1018  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:12.361  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-12 13:57:12.361  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-12 13:57:12.361  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-12 13:57:12.361  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:12.361  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:12.361  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:12.361  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:12.371  7044  7044 E Zygote  : MountEmulatedStorage()
09-12 13:57:12.371  7044  7044 E Zygote  : v2
09-12 13:57:12.371  7044  7044 I libpersona: KNOX_SDCARD checking this for 10102
09-12 13:57:12.371  7044  7044 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:12.381  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:12.381  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:12.381  1018  1329 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7044 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 13:57:12.381  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:57:12.401  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:12.401  7044  7044 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:12.421  7044  7044 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 13:57:12.491  1382  1382 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-12 13:57:12.491  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.491  1382  1382 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 13:57:12.491  1382  1382 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 13:57:12.491  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.491  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:12.491  1382  1382 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 13:57:12.491  1382  1382 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:57:12.501  1018  1132 D Tethering: InitialState.processMessage what=4
,09-12 13:57:12.501  1018  1132 E Tethering: No numeric data
,09-12 13:57:12.511  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:57:12.511  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.511  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:57:12.511  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.511  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.511  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:57:12.511  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:12.511  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.511  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:12.511  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:12.521  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:12.521  1018  1132 D Tethering: clearTetheredNotification()
,09-12 13:57:12.521  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:12.521  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:57:12.521  1018  1124 V NetworkStats: performPollLocked() took 7ms
,09-12 13:57:12.521  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.521  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.521  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:12.561  1018  2857 D SSRM:n  : SIOP:: AP = 360
,09-12 13:57:12.651  7044  7064 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 13:57:12.651  7044  7064 I Babel_SMS: MmsConfig.loadMmsSettings
,09-12 13:57:12.651  7044  7064 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 13:57:12.651  7044  7064 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 13:57:12.681  7044  7064 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-12 13:57:12.681  7044  7064 I Babel_SMS: MmsConfig.loadFromResources
,09-12 13:57:12.691  7044  7064 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull,
09-12 13:57:12.691  7044  7064 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 13:57:12.701  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:57:12.701  1018  1454 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-12 13:57:12.711  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 13:57:12.711  1018  1454 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:12.711  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:57:12.711  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:12.711  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:57:12.721  1018  1018 I ApplicationPolicy: updateDataUsageMap
,09-12 13:57:12.731  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:12.731  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:12.741  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:12.741  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:57:12.741  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:12.741  1382  1382 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 13:57:12.741  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:12.741  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 13:57:12.741  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:57:12.751  7044  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:12.751  7044  7044 I Babel_Crash: startup - clean
,09-12 13:57:12.751  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:12.761  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:12.761  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:12.761  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.761  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:12.761  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.761  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.761  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:12.761  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:12.761  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 13:57:12.761  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:57:12.761  1176  1176 D HotspotTile: onReceive : 1, 0
,09-12 13:57:12.761  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:12.761  1679  2177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:12.761  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:12.771  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:12.771  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:12.791  1018  1442 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:12.791  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:12.791  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:12.791  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:12.791  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:12.801  1625  1625 I Hs20UtilService: Starting #9
,09-12 13:57:12.801  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:57:12.801  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:12.801  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:12.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:12.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:57:12.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:12.801  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:57:12.801  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:12.811  7044  7044 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:57:12.811  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:12.811  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:12.811  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:12.811  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:12.811  7044  7044 W AudioCapabilities: Unsupported mime audio/evrc
09-12 13:57:12.811  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:12.821  1625  1625 I Hs20UtilService: Starting #10
,09-12 13:57:12.821  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:12.821  7044  7044 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:57:12.821  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:57:12.821  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:57:12.821  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:57:12.821  7044  7044 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-12 13:57:12.821  7044  7044 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 13:57:12.821  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:12.831  7044  7044 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 13:57:12.831  7044  7044 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 13:57:12.831  7044  7044 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:57:12.831  7044  7044 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:57:12.831  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:12.831  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:12.841  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:12.841  7044  7044 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:57:12.841  7044  7044 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:57:12.851  1018  1454 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:12.851  1018  1454 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 13:57:12.851  1018  1454 D SecContentProvider2: mCursor = null
,09-12 13:57:12.851  1018  1454 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:12.851  1018  1454 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:12.851  1018  1454 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:12.851  1018  1454 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:12.851  1018  1454 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:12.851  1018  1454 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:12.851  1018  1454 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:12.851  1018  1454 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:12.851  1018  1454 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:57:12.851  1018  1454 D SettingsProvider: name = wifi_on
,09-12 13:57:12.851  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:12.861  7044  7044 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-12 13:57:12.861  7044  7044 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:57:12.861  7044  7044 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:57:12.861  7044  7044 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 13:57:12.861  7044  7044 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 13:57:12.871  7044  7044 W VideoCapabilities: Unsupported mime video/mp43
,09-12 13:57:12.871  7044  7044 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 13:57:12.871  7044  7044 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 13:57:12.891  7044  7044 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 13:57:12.911  7044  7044 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:57:12.911  7044  7044 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:57:12.911  7044  7044 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:57:12.921  7044  7044 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:57:12.921  1018  1952 I ActivityManager: Killing 6642:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-12 13:57:12.921  7044  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:57:12.921  7044  7044 I vclib   : onServiceConnected
,09-12 13:57:13.011  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.011  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.011  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.011  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.011  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.011  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.021  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.021  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.021  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.021  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.031  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.031  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.031  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.031  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.041  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.041  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.041  1018  1018 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 13:57:13.041  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:57:13.041  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
,09-12 13:57:13.051  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.051  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.051  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.051  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.061  7067  7067 E Zygote  : MountEmulatedStorage()
,09-12 13:57:13.061  7067  7067 E Zygote  : v2
09-12 13:57:13.061  7067  7067 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:13.061  7067  7067 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:13.061  7067  7067 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:13.071  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:13.071  7067  7067 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:13.071  7067  7067 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:57:13.091  7067  7067 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.091  7067  7067 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.121  7067  7067 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 13:57:13.121  7067  7067 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-12 13:57:13.121  7067  7067 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 13:57:13.131  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:13.131  7067  7067 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-12 13:57:13.131  7067  7067 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-12 13:57:13.131  7067  7067 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 13:57:13.131  7067  7067 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:13.141  1018  1454 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-12 13:57:13.141  1018  1454 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-12 13:57:13.141  1018  1454 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-12 13:57:13.141  1018  1454 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-12 13:57:13.141  1018  1454 I ActivityManager: Killing 6689:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-12 13:57:13.141  7067  7082 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 13:57:13.151  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-12 13:57:13.151  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-12 13:57:13.151  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-12 13:57:13.151  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-12 13:57:13.151  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,09-12 13:57:13.161  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-12 13:57:13.161  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 13:57:13.161  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,09-12 13:57:13.161  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:57:13.161  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:57:13.161  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.161  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.171  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:57:13.171  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-12 13:57:13.171  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,09-12 13:57:13.181  7084  7084 E Zygote  : MountEmulatedStorage(),
,09-12 13:57:13.181  7084  7084 E Zygote  : v2
,09-12 13:57:13.181  7084  7084 I libpersona: KNOX_SDCARD checking this for 10001
09-12 13:57:13.181  7084  7084 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:13.181  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:13.181  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7084 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:13.191  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:13.191  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:13.221  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:57:13.221  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.221  7084  7084 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.231  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:57:13.231  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:57:13.251  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:57:13.281  1018  1308 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 13:57:13.291  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.291  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.291  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.291  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.291  1018  1045 D Tethering: interfaceRemoved wlan0
,09-12 13:57:13.291  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 13:57:13.301  1018  1308 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:13.311  7102  7102 E Zygote  : MountEmulatedStorage()
09-12 13:57:13.311  7102  7102 E Zygote  : v2
09-12 13:57:13.311  7102  7102 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:13.311  7102  7102 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:13.311  1018  1308 I ActivityManager: Killing 6713:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-12 13:57:13.311  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:13.311  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:13.311  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:13.331  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.331  7102  7102 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.351  1018  1952 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:13.351  1018  1952 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 13:57:13.361  1018  1952 D SecContentProvider2: mCursor = null
,09-12 13:57:13.361  1018  1952 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:13.361  1018  1952 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:13.361  1018  1952 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:13.361  1018  1952 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:13.361  1018  1952 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:13.361  1018  1952 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:13.361  1018  1952 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:13.361  1018  1952 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:13.361  1018  1952 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:57:13.361  1018  1952 D SettingsProvider: name = wifi_on
,09-12 13:57:13.361  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:13.381  7102  7102 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 13:57:13.431  1018  1045 D Tethering: interfaceRemoved p2p0
,09-12 13:57:13.431  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:57:13.491  7102  7102 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 13:57:13.501  7102  7102 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-12 13:57:13.501  7102  7102 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:13.501  7102  7102 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 13:57:13.501  7102  7102 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-12 13:57:13.511  7102  7102 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-12 13:57:13.511  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-12 13:57:13.511  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.511  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.511  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.511  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.521  7117  7117 E Zygote  : MountEmulatedStorage(),
09-12 13:57:13.521  1018  1454 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7117 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:57:13.521  7117  7117 E Zygote  : v2
,09-12 13:57:13.521  7117  7117 I libpersona: KNOX_SDCARD checking this for 10008
09-12 13:57:13.521  7117  7117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:13.521  7117  7117 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:13.521  1018  1454 I ActivityManager: Killing 6741:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-12 13:57:13.531  7117  7117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:13.531  7117  7117 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 13:57:13.541  7117  7117 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.541  7117  7117 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.601  1018  1308 I ActivityManager: Killing 6330:com.android.mms/u0a41 (adj 15): empty #21
,09-12 13:57:13.611  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 13:57:13.611  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 13:57:13.611  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.611  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:13.611  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 13:57:13.621  1900  1900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:57:13.621  1900  4765 I iu.UploadsManager: num queued entries: 0
,09-12 13:57:13.621  1900  4765 I iu.UploadsManager: num updated entries: 0
,09-12 13:57:13.621  1900  4765 I iu.SyncManager: NEXT; no task
,09-12 13:57:13.621  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:57:13.621  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-12 13:57:13.621  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:13.621  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:13.621  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:13.631  1900  1900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:57:13.631  1900  1900 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-12 13:57:13.641  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:57:13 GMT+02:00 2016
,09-12 13:57:13.641  1018  1308 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 13:57:13.641  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:57:13.641  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.641  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:13.641  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:57:13.641  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:57:13.651  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 13:57:13.651  2931  2931 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:57:13.651  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 13:57:13.651  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.651  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.651  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.651  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.651  2931  2931 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:57:13.661  2931  7133 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 13:57:13.671  7134  7134 E Zygote  : MountEmulatedStorage()
09-12 13:57:13.671  7134  7134 I libpersona: KNOX_SDCARD checking this for 10031
09-12 13:57:13.671  7134  7134 E Zygote  : v2
09-12 13:57:13.671  7134  7134 I libpersona: KNOX_SDCARD not a persona,
09-12 13:57:13.671  2931  7133 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-12 13:57:13.671  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:13.671  1018  1954 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7134 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-12 13:57:13.671  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:13.671  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:13.681  2931  7133 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-12 13:57:13.681  2931  7133 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END,
,09-12 13:57:13.681  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 13:57:13.691   309   309 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 20.131ms
,09-12 13:57:13.701  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 13:57:13.701  7134  7134 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.711   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.323ms
,09-12 13:57:13.721   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.345ms
,09-12 13:57:13.731  7134  7134 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 13:57:13.731  1018  1031 I ActivityManager: Killing 6764:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-12 13:57:13.751  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 13:57:13.751  3509  7149 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 13:57:13.751  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.751  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.751  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.751  3509  7149 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-12 13:57:13.751  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.751  3509  7149 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
,09-12 13:57:13.761  3509  7149 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-12 13:57:13.761  3509  7149 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 13:57:13.761  7150  7150 E Zygote  : MountEmulatedStorage()
,09-12 13:57:13.761  7150  7150 I libpersona: KNOX_SDCARD checking this for 10032
09-12 13:57:13.761  7150  7150 E Zygote  : v2
09-12 13:57:13.761  7150  7150 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:13.771  7150  7150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:13.771  1018  1329 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7150 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:13.771  7150  7150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:13.771  7150  7150 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 13:57:13.791  7150  7150 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.801  7150  7150 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.811  1018  1030 D CountryDetector: No listener is left
,09-12 13:57:13.851  7150  7165 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 13:57:13.851  7150  7165 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-12 13:57:13.851  7150  7150 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 13:57:13.851  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-12 13:57:13.861  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.861  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.861  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:13.861  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:13.861  1018  1137 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:13.861  1018  1137 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:13.861  1018  1137 D WifiService: setWifiEnabled: true pid=6625, uid=10170
09-12 13:57:13.861  1018  1137 D SecContentProvider2: mCursor = null
,09-12 13:57:13.861  1018  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:13.861  1018  1137 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:13.861  1018  1137 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:13.861  1018  1137 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:13.861  1018  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:13.861  1018  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:13.861  1018  1137 W WifiService: 	,at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:13.861  1018  1137 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:57:13.861  1018  1137 D SettingsProvider: name = wifi_on
09-12 13:57:13.871  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:13.871  7150  7165 D SPPClientService: PushLog.txt file is not deleted.
,09-12 13:57:13.871  7150  7165 D SPPClientService: PushLog.txt file is not deleted.
,09-12 13:57:13.871  7150  7165 D SPPClientService: ============PushLog. stop!
,09-12 13:57:13.871  7167  7167 E Zygote  : MountEmulatedStorage()
09-12 13:57:13.871  7167  7167 E Zygote  : v2
09-12 13:57:13.871  7167  7167 I libpersona: KNOX_SDCARD checking this for 10036
09-12 13:57:13.871  7167  7167 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:13.881  1018  1488 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7167 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:13.881  7167  7167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:13.881  1018  1488 I ActivityManager: Killing 6150:com.samsung.android.sm/1000 (adj 15): empty #21
,09-12 13:57:13.881  1018  1454 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-12 13:57:13.881  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-12 13:57:13.881  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:13.881  1018  1454 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 13:57:13.881  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-12 13:57:13.881  7167  7167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:13.881  7167  7167 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-12 13:57:13.901  7167  7167 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:13.901  7167  7167 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:13.911  7150  7174 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-12 13:57:13.931  7167  7167 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1f8426e1
,09-12 13:57:13.941  7167  7167 I SA      : [SSP] onCreated
,09-12 13:57:13.951  7167  7167 I SA      : [TPM] There is no property file
,09-12 13:57:13.951  7167  7167 I SA      : [SCU] isHaveSA() - false
,09-12 13:57:13.961  7167  7167 I SA      : [TPM] getModelProperty : null
,09-12 13:57:13.961  7167  7167 I SA      : [TPM] getCSCProperty : null
,09-12 13:57:13.961  7167  7167 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-12 13:57:13.961  7167  7167 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-12 13:57:13.961  7167  7167 I SA      : [DM] TFT FEATURE: false
,09-12 13:57:13.961  7167  7167 I SA      : [DM] init START
,09-12 13:57:13.971  7167  7167 I SA      : [DM] This device is not a Vodafone
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-12 13:57:13.971  7167  7167 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 13:57:13.971  7167  7167 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75),
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75),
09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-12 13:57:13.981  7167  7167 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-12 13:57:13.981  7167  7167 I SA      : [SCU] isHaveSA() - false,
09-12 13:57:13.981  7167  7167 I SA      : support phone number id : false
,09-12 13:57:13.981  7167  7167 I SA      : [DM] Supports Ref Jpn : true
09-12 13:57:13.991  7167  7167 I SA      : [DM] init END
,09-12 13:57:13.991  7167  7167 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-12 13:57:13.991  7167  7167 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
09-12 13:57:13.991  7167  7167 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,09-12 13:57:13.991  7167  7167 I SA      : [SLFUCHKMGR] constructor called
,09-12 13:57:14.001  7167  7167 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-12 13:57:14.001  7167  7167 I SA      : [OR] == isSIMCardReady false ==
,09-12 13:57:14.001  7167  7167 I SA      : [SCU] == networkStateCheck == false
09-12 13:57:14.001  7167  7167 I SA      : [OR] onReceive END
,09-12 13:57:14.001  1018  1442 I ActivityManager: Killing 6781:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-12 13:57:14.001  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:14.011  1775  1775 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:14.021  2671  5296 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-12 13:57:14.021  1775  1775 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-12 13:57:14.021  1775  1775 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-12 13:57:14.021  1775  1775 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-12 13:57:14.021  1775  1775 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:14.031  1775  1775 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:14.031  1775  1775 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-12 13:57:14.031  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 13:57:14.031  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.031  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.031  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.031  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.051  7189  7189 E Zygote  : MountEmulatedStorage()
,09-12 13:57:14.051  7189  7189 E Zygote  : v2
09-12 13:57:14.051  7189  7189 I libpersona: KNOX_SDCARD checking this for 10077,
09-12 13:57:14.051  7189  7189 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:14.051  7189  7189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 13:57:14.051  1018  1137 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7189 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:14.051  7189  7189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:14.051  7189  7189 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-12 13:57:14.071  7189  7189 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:14.071  7189  7189 D ActivityThread: Added TimaKeyStore provider,
,09-12 13:57:14.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:57:14.151  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:57:14.151  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 13:57:14.181  1018  1308 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-12 13:57:14.181  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 13:57:14.181  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:14.181  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:14.181  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:57:14.181  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 13:57:14.191  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.191  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.191  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.191  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.201  7207  7207 E Zygote  : MountEmulatedStorage()
09-12 13:57:14.201  7207  7207 E Zygote  : v2
09-12 13:57:14.201  7207  7207 I libpersona: KNOX_SDCARD checking this for 10110
09-12 13:57:14.201  7207  7207 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:14.201  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:14.201  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:14.211  1018  1329 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7207 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:14.211  1018  1954 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-12 13:57:14.211  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 13:57:14.211  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:14.211  1018  1954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:14.211  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:57:14.211  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:57:14.211  7044  7206 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 13:57:14.221  1018  1487 I ActivityManager: Killing 6796:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-12 13:57:14.231  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:14.231  7207  7207 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:14.281  1018  1952 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 13:57:14.351   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:57:14.351   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:14.351  7207  7225 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:57:14.351  7207  7207 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 13:57:14.351  7207  7207 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 13:57:14.351  7207  7207 I GAv4    :   adb logcat -s GAv4
,09-12 13:57:14.351   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:57:14.351   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:14.361  7207  7225 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:57:14.371  1018  1488 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:57:14.371  1018  1488 D WifiService: setWifiEnabled: true pid=6625, uid=10170
09-12 13:57:14.371  1018  1488 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:14.371  1018  1488 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:14.371  1018  1488 D SecContentProvider2: mCursor = null
09-12 13:57:14.371  1018  1488 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:14.371  1018  1488 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:14.371  1018  1488 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:14.371  1018  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:14.371  1018  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:14.371  1018  1488 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:14.371  1018  1488 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:14.371  1018  1488 D SettingsProvider: name = wifi_on
09-12 13:57:14.371  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:14.401   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:57:14.401   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:14.401  7207  7228 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:57:14.401   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:57:14.401   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:14.401  7207  7228 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:57:14.401  7207  7207 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:57:14.401  1018  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 13:57:14.421  7207  7207 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:57:14.431  7207  7234 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:57:14.531  1018  1045 D Tethering: interfaceAdded wlan0
,09-12 13:57:14.531  1018  1132 E Tethering: No numeric data
,09-12 13:57:14.541  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:57:14.541  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:14.541  1018  1132 D Tethering: clearTetheredNotification()
09-12 13:57:14.541  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:14.541  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:14.541  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:14.541  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:14.541  1176  1176 D HotspotTile: updateTetherState():false, false
09-12 13:57:14.541  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.541  1018  1124 V NetworkStats: performPollLocked() took 5ms
09-12 13:57:14.541  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:14.541  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:57:14.541  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.541  1018  1132 D Tethering: InitialState.processMessage what=4
09-12 13:57:14.551  1018  1045 D Tethering: interfaceAdded p2p0
09-12 13:57:14.551  1018  1132 E Tethering: No numeric data
09-12 13:57:14.551  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
09-12 13:57:14.551  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:14.551  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.551  1018  1132 D Tethering: clearTetheredNotification()
09-12 13:57:14.551  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:14.551  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:14.551  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:14.551  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:57:14.551  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:14.551  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:57:14.561  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.561  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:14.561  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:14.561  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:14.561   277  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:57:14.561   277  1017 D SoftapController: Softap fwReload - Ok
09-12 13:57:14.561  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.561  1018  1124 V NetworkStats: performPollLocked() took 7ms
,09-12 13:57:14.571   277  1017 D CommandListener: Setting iface cfg,
09-12 13:57:14.571   277  1017 D CommandListener: Trying to bring down wlan0
,09-12 13:57:14.571  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:14.571  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 13:57:14.571   277  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:57:14.571  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 13:57:14.621  1018  1954 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:14.631  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:14.631  1018  1954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:14.631  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 13:57:14.641  7207  7207 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-12 13:57:14.641  7249  7249 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:57:14.641  7249  7249 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 13:57:14.641  7249  7249 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 13:57:14.661  7207  7207 I cr.library_loader: Time to load native libraries: 5 ms (timestamps 4410-4415)
,09-12 13:57:14.661  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-12 13:57:14.671  7207  7207 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21a72520},
09-12 13:57:14.671  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 13:57:14.671  7207  7207 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
,09-12 13:57:14.671  7249  7249 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-12 13:57:14.671   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7249
09-12 13:57:14.671   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-12 13:57:14.671  7249  7249 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:57:14.671  7249  7249 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:14.671  7249  7249 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:57:14.671  7249  7249 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-12 13:57:14.681   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7249
09-12 13:57:14.681   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-12 13:57:14.681  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 13:57:14.681  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:14.691  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:57:14.691  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:14.691  7207  7207 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-12 13:57:14.691  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:14.691  7207  7207 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:57:14.691  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:14.691  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:14.691  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:14.691  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:14.691  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 13:57:14.691  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:14.691  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:57:14.691  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:14.691  1176  1176 D HotspotTile: onReceive : 2, 0
,09-12 13:57:14.701  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:14.701  7207  7207 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:57:14.701  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 13:57:14.701  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:14.711  7207  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-12 13:57:14.711  7207  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:57:14.711  7207  7207 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:57:14.711  7207  7207 I Adreno-EGL: Local Branch: 
09-12 13:57:14.711  7207  7207 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:57:14.711  7207  7207 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:57:14.711  7207  7207 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:57:14.831   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-12 13:57:14.831  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-12 13:57:14.841  7207  7265 W cr.media: Requires BLUETOOTH permission
,09-12 13:57:14.851  7207  7207 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 13:57:14.861  7207  7207 I NSApplication: Starting up...
,09-12 13:57:14.861  1018  1454 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 13:57:14.861  1018  1137 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 13:57:14.871  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 13:57:14.871  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.871  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.871  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:14.871  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:14.881  7270  7270 E Zygote  : MountEmulatedStorage(),
09-12 13:57:14.881  7270  7270 E Zygote  : v2
09-12 13:57:14.881  7270  7270 I libpersona: KNOX_SDCARD checking this for 10117
09-12 13:57:14.881  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:57:14.881  7270  7270 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:14.881  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:14.881  1018  1030 D WifiService: setWifiEnabled: true pid=6625, uid=10170
09-12 13:57:14.881  1018  1030 D SecContentProvider2: mCursor = null,
09-12 13:57:14.881  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:14.881  7270  7270 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:14.881  1018  1030 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:14.881  1018  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:14.881  1018  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:14.881  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216),
09-12 13:57:14.881  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:14.881  1018  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:14.881  1018  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:14.881  1018  1030 D SettingsProvider: name = wifi_on
09-12 13:57:14.881  7249  7249 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:57:14.881  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 13:57:14.881  7270  7270 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:14.881  7270  7270 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-12 13:57:14.881  1018  1454 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7270 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 13:57:14.891  1018  1454 I ActivityManager: Killing 6882:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-12 13:57:14.901  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-12 13:57:14.901   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7249
09-12 13:57:14.901   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 13:57:14.901  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-12 13:57:14.901  7249  7249 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:14.901  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:57:14.901  7249  7249 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:14.901  7249  7249 E wpa_supplicant: SIM READ ERROR
09-12 13:57:14.901  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:14.901  7249  7249 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 13:57:14.901  7249  7249 E wpa_supplicant: SIM READ ERROR
09-12 13:57:14.901  7249  7249 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:57:14.901  7249  7249 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:57:14.901  7249  7249 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:57:14.901  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:14.901  7249  7249 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 13:57:14.901  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:57:14.901  7249  7249 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:57:14.911  7249  7249 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:57:14.911  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:14.911  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:14.911  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:57:14.911  7270  7270 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:14.911  7270  7270 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:14.931  7270  7270 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:14.961  7249  7249 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-12 13:57:15.081   287   287 E SMD     : DCD OFF
,09-12 13:57:15.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:15.141  7249  7249 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
09-12 13:57:15.141  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 13:57:15.161  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-12 13:57:15.161   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7249
09-12 13:57:15.161   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-12 13:57:15.161  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
09-12 13:57:15.161  7249  7249 I wpa_supplicant: ssSupport state is = 1,
,09-12 13:57:15.161  7249  7249 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 13:57:15.161  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 13:57:15.171  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-12 13:57:15.171   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7249
09-12 13:57:15.171   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 13:57:15.171  7249  7249 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 13:57:15.171  7249  7249 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:15.171  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:15.181  7249  7249 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:15.181  7249  7249 E wpa_supplicant: SIM READ ERROR
09-12 13:57:15.181  7249  7249 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:57:15.181  7249  7249 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:57:15.181  7249  7249 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:57:15.181  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:15.181  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:15.181  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:15.181  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:15.181  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:15.181  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:15.221  1018  1442 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-12 13:57:15.221  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.221  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:15.221  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.221  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.241  7294  7294 E Zygote  : MountEmulatedStorage()
09-12 13:57:15.241  7294  7294 E Zygote  : v2
09-12 13:57:15.241  7294  7294 I libpersona: KNOX_SDCARD checking this for 10121
09-12 13:57:15.241  7294  7294 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:15.241  7294  7294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:15.241  7294  7294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 13:57:15.241  1018  1442 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7294 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-12 13:57:15.241  1018  1442 I ActivityManager: Killing 6898:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-12 13:57:15.241  7294  7294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:15.261  7249  7249 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-12 13:57:15.261  7249  7249 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:57:15.261  7294  7294 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:15.261  7294  7294 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:15.281  7294  7294 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:57:15.281  7294  7294 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:57:15.281  7294  7294 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:57:15.301  7294  7294 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:15.301  7294  7294 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 13:57:15.301  7294  7294 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 13:57:15.311  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-12 13:57:15.311  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.311  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:15.311  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:15.311  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.321  7311  7311 E Zygote  : MountEmulatedStorage(),
09-12 13:57:15.321  7311  7311 E Zygote  : v2
09-12 13:57:15.321  7311  7311 I libpersona: KNOX_SDCARD checking this for 10141,
09-12 13:57:15.321  1018  1329 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7311 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-12 13:57:15.321  7311  7311 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:15.321  1018  1329 I ActivityManager: Killing 6851:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-12 13:57:15.321  7311  7311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:15.331  7311  7311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:15.331  7311  7311 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:15.331  7249  7249 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-12 13:57:15.331  7249  7249 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-12 13:57:15.331  7249  7249 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:57:15.331  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-12 13:57:15.341  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 13:57:15.341  7249  7249 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 13:57:15.341  7249  7249 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:15.341  7249  7249 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:15.341  7249  7249 E wpa_supplicant: SIM READ ERROR
09-12 13:57:15.341  7249  7249 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:57:15.351  7311  7311 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:15.361  7311  7311 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:15.361  7249  7249 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 13:57:15.371  7249  7249 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:57:15.371  1018  1127 D WifiConfigStore: Loading config and enabling all networks ,
,09-12 13:57:15.371  7311  7311 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-12 13:57:15.371  7311  7311 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:15.371  7311  7311 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:57:15.371  7311  7311 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:15.381  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:15.381  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:15.381  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:15.381  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 13:57:15.381  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:15.381  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:57:15.381  1176  1176 D HotspotTile: onReceive : 3, 0
09-12 13:57:15.381  1018  1127 E WifiConfigStore: Not a HS20
,09-12 13:57:15.391  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:15.391  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.391  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:15.391  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:15.391  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 13:57:15.391  7249  7249 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:57:15.391  7249  7249 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 13:57:15.391  7249  7249 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:57:15.391  7249  7249 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:57:15.391  7249  7249 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:57:15.391  7249  7249 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:57:15.391  7249  7249 I wpa_supplicant: First Scan Start
,09-12 13:57:15.391  7249  7249 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:57:15.401  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-12 13:57:15.401  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:15.401  1018  1127 I WifiNative-HAL: startHal
09-12 13:57:15.401  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ece188c
09-12 13:57:15.401  1018  1127 I WifiNative-HAL: Could not start hal
,09-12 13:57:15.401  7044  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.401  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:15.401  1018  1127 E WifiNative-wlan0: do suspend true
,09-12 13:57:15.401  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 13:57:15.401  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
09-12 13:57:15.401  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:57:15.401  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:15.401  1018  1152 I WifiNative-HAL: startHal
,09-12 13:57:15.401  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9d8ee9bc
09-12 13:57:15.401  1018  1152 I WifiNative-HAL: Could not start hal
,09-12 13:57:15.411  1018  1018 D RttService: SCAN_AVAILABLE : 3
09-12 13:57:15.411  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:15.411  1018  1152 E WifiScanningService: could not start HAL
09-12 13:57:15.411   277  1017 D CommandListener: Setting iface cfg
09-12 13:57:15.411   277  1017 D CommandListener: Trying to bring up p2p0
,09-12 13:57:15.411  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:57:15.411  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:15.411  1018  1126 D WifiP2pService: P2pEnablingState
09-12 13:57:15.411  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-12 13:57:15.411  1018  1126 D WifiP2pService: P2p socket connection successful
09-12 13:57:15.411  1018  1126 D WifiP2pService: P2pEnabledState
,09-12 13:57:15.411  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 13:57:15.411  1018  1129 E ConnectivityService: updateNetworkInfo()
,09-12 13:57:15.411  7249  7249 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:57:15.411  7249  7249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:57:15.421  7249  7249 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-12 13:57:15.421  1018  1127 E WifiStateMachine: Failed to set frequency band 0
09-12 13:57:15.421  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:57:15.421  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:57:15.421  1018  1127 E WifiNative-wlan0: invaild command id : 215
09-12 13:57:15.421  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:15.421  1018  1127 D SecContentProvider2: mCursor = null
09-12 13:57:15.421  6625  7329 D BluetoothAdapter: disable()
,09-12 13:57:15.421  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 13:57:15.431  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-12 13:57:15.431  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:15.431  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:15.431  1018  1127 D SecContentProvider2: mCursor = null
09-12 13:57:15.431  1018  1048 D WifiDisplayController: disconnect
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.431  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:15.431  1018  1048 D WifiDisplayController: updateConnection
,09-12 13:57:15.431  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:15.431  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:57:15.431  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 13:57:15.431  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-12 13:57:15.431  1018  1489 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:15.431  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:57:15.431  1018  1048 D WifiDisplayAdapter: onP2pDisconnected,
09-12 13:57:15.431  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-12 13:57:15.431  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:57:15.441  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:15.441  1018  1454 D SettingsProvider: name = bluetooth_on
09-12 13:57:15.441  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:57:15.441  1018  1442 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:57:15.441  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 13:57:15.441  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
09-12 13:57:15.441  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  secondary type: null
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  wps: 0
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  grpcapab: 0
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  devcapab: 0
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  status: 3
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  wfdInfo: null
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-12 13:57:15.441  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-12 13:57:15.451  1018  1952 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:15.451  2778  2834 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-12 13:57:15.451  2778  2834 D BluetoothAdapterProperties: Setting state to 13
09-12 13:57:15.451  2778  2834 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:57:15.451  2778  2834 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:57:15.451  2778  2834 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 13:57:15.451  1018  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:15.451  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-12 13:57:15.451  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:15.451  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.451  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.451  2778  2778 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-12 13:57:15.451  2778  2834 D BluetoothAdapterService: Autoconnection is available 
09-12 13:57:15.451  2778  2834 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 13:57:15.451  2778  2834 D BluetoothAdapterService: terminating service from this receiver
09-12 13:57:15.451  2778  2778 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@183abed9, channel: 19, state: LISTENING
09-12 13:57:15.451  2778  2778 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@183abed9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6ffbd08, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bff909emSocket: android.net.LocalSocket@1214e77f impl:android.net.LocalSocketImpl@1ca9734c fd:FileDescriptor[80]
09-12 13:57:15.451  2778  2778 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1214e77f impl:android.net.LocalSocketImpl@1ca9734c fd:FileDescriptor[80]
09-12 13:57:15.461  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.461  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:15.461  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.461  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.461  2778  2834 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:57:15.461  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:15.461  2778  2834 D BluetoothAdapterProperties: mDiscovering is false
09-12 13:57:15.461  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
09-12 13:57:15.461  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:57:15.461  2778  2834 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 13:57:15.471  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:57:15.471  1869  1869 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:57:15.471  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:57:15.481  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:15.481  1176  1176 D BluetoothTile:  getBluetoothState : 13
,09-12 13:57:15.481  4492  4492 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:15.491  1018  1952 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:57:15.491  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:57:15.491  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
09-12 13:57:15.491  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 13:57:15.491  1018  1308 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:57:15.491  2778  2837 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:57:15.491  2778  2837 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:57:15.501  1018  1126 D WifiP2pService: InactiveState
,09-12 13:57:15.501  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
09-12 13:57:15.501  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:57:15.501  7249  7249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:57:15.501  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.501  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:15.501  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:57:15.501  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:57:15.501  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
09-12 13:57:15.501  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
09-12 13:57:15.501  2778  2834 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 13:57:15.511  4492  4492 D BluetoothPbap: Proxy object disconnected
09-12 13:57:15.511  2778  2834 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 13:57:15.511  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:15.511  2778  2834 E bt-btif : cmd socket is not created
,09-12 13:57:15.511  6625  6981 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35ec8702, channel: -1, state: INIT
09-12 13:57:15.511  6625  6981 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35ec8702, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34644813, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e5aaa50mSocket: android.net.LocalSocket@265f1449 impl:android.net.LocalSocketImpl@820114e fd:FileDescriptor[106]
09-12 13:57:15.511  6625  6981 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@265f1449 impl:android.net.LocalSocketImpl@820114e fd:FileDescriptor[106]
09-12 13:57:15.511  4492  4492 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:57:15.511  6625  6981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1341)
,09-12 13:57:15.511  2778  2838 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-12 13:57:15.511  2778  5261 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:57:15.511  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:15.511  2778  2834 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:57:15.511  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:57:15.521  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:15.521  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:15.521  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:15.521  2778  2838 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-12 13:57:15.521  2778  2838 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
09-12 13:57:15.521  2778  2838 W bt-btif : invalid rfc slot id: 7
09-12 13:57:15.521  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:15.521  6625  6625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:57:15.521  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:15.521  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.531  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:15.531  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.541  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:57:15.541  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 13:57:15.541  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:57:15.541  2778  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:57:15.641  1018  1488 I art     : Explicit concurrent mark sweep GC freed 76206(4MB) AllocSpace objects, 17(320KB) LOS objects, 33% free, 23MB/34MB, paused 2.379ms total 170.448ms
,09-12 13:57:15.651  2778  2778 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e0f6f95, channel: 5, state: LISTENING
09-12 13:57:15.651  2778  2778 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e0f6f95, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22ac1ca1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12d018aamSocket: android.net.LocalSocket@279a7c9b impl:android.net.LocalSocketImpl@29a07838 fd:FileDescriptor[82]
09-12 13:57:15.651  2778  2778 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@279a7c9b impl:android.net.LocalSocketImpl@29a07838 fd:FileDescriptor[82]
,09-12 13:57:15.651  1018  1489 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:15.651  2778  2778 I BtOppRfcommListener: stopping Accept Thread
09-12 13:57:15.651  2778  2778 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11447011, channel: 12, state: LISTENING
09-12 13:57:15.651  2778  2778 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11447011, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69dac23, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@326f1576mSocket: android.net.LocalSocket@211a4777 impl:android.net.LocalSocketImpl@1700dfe4 fd:FileDescriptor[87]
09-12 13:57:15.651  2778  2778 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@211a4777 impl:android.net.LocalSocketImpl@1700dfe4 fd:FileDescriptor[87]
,09-12 13:57:15.651  2778  5261 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:57:15.651  2778  2778 V BluetoothOppManager: cleanUp...
,09-12 13:57:15.691  1018  1454 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-12 13:57:15.691  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.691  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:15.691  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.691  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.701  7339  7339 E Zygote  : MountEmulatedStorage()
09-12 13:57:15.701  7339  7339 E Zygote  : v2
,09-12 13:57:15.701  7339  7339 I libpersona: KNOX_SDCARD checking this for 10068
09-12 13:57:15.701  7339  7339 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:15.701  7339  7339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:15.711  1018  1454 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7339 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-12 13:57:15.711  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:15.711  7339  7339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:15.711  7339  7339 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 13:57:15.711  2778  2834 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 13:57:15.711  2778  2834 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:57:15.711  2778  2834 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 13:57:15.711  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-12 13:57:15.711  2778  2834 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-12 13:57:15.711  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:57:15.711  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 13:57:15.711  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:57:15.711  1018  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:15.711  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.711  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.711  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.711  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:57:15.711  1018  1952 D RCPManagerService: exchangeData() failure , invalid userId
09-12 13:57:15.721  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:57:15.721  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:57:15.721  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:57:15.721  2778  2778 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:57:15.721  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:15.721  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.721  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.721  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:15.721  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.721  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.721  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 13:57:15.721  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 13:57:15.721  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:57:15.721  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:57:15.721  1018  1952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:15.731  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.731  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.731  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.731  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.731  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:57:15.731  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 13:57:15.731  4492  4492 D HeadsetProfile: Bluetooth service disconnected
,09-12 13:57:15.731  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:57:15.731  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:15.731  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.731  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.731  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.731  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.731  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 13:57:15.731  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:57:15.731  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:57:15.731  1018  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:15.731  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.741  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.741  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.741  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.741  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.741  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:57:15.741  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:57:15.741  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:15.741  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.741  7339  7339 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:15.741  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.741  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.741  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.741  7339  7339 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:15.741  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:57:15.741  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:57:15.751  1018  1952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:15.751  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.751  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:15.751  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.751  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:15.751  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:15.751  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:57:15.751  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-12 13:57:15.751  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:57:15.751  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 13:57:15.761  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-12 13:57:15.761  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-12 13:57:15.761  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:57:15.761  2778  2778 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 13:57:15.761  2778  2834 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 13:57:15.761  2778  2778 D A2dpService: Received stop request...Stopping profile...
,09-12 13:57:15.761  2778  2901 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:57:15.761  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:15.761  1018  1442 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-12 13:57:15.761  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.761  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.761  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:15.761  1018  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:15.781  7355  7355 E Zygote  : MountEmulatedStorage(),
,09-12 13:57:15.781  7355  7355 E Zygote  : v2
09-12 13:57:15.781  7339  7339 D BadgeProvider: onCreate
,09-12 13:57:15.781  7355  7355 I libpersona: KNOX_SDCARD checking this for 10009
09-12 13:57:15.781  7355  7355 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:15.781  7339  7339 D BadgeProvider: DatabaseHelper
,09-12 13:57:15.781  7355  7355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:15.781  7355  7355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:15.791  1018  1442 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7355 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-12 13:57:15.791  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:15.791  1018  1030 I ActivityManager: Killing 6830:com.android.calendar/u0a131 (adj 15): empty #21
09-12 13:57:15.791  7355  7355 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 13:57:15.791  1018  1030 I ActivityManager: Killing 6815:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
,09-12 13:57:15.811  1018  1018 D BluetoothA2dp: Proxy object disconnected
09-12 13:57:15.811  4492  4492 D BluetoothA2dp: Proxy object disconnected
09-12 13:57:15.811  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 13:57:15.811  4492  4492 D A2dpProfile: Bluetooth service disconnected
,09-12 13:57:15.811  7339  7350 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-12 13:57:15.821  2778  2778 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:57:15.821  2778  2778 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:57:15.821  7355  7355 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:15.821  7355  7355 D ActivityThread: Added TimaKeyStore provider
09-12 13:57:15.821  2778  2778 D HidService: Received stop request...Stopping profile...
09-12 13:57:15.821  2778  2778 D HidService: Stopping Bluetooth HidService
09-12 13:57:15.821  2778  2778 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:57:15.821  2778  2778 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 13:57:15.821  2778  2778 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:57:15.821  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.821  4492  4492 D BluetoothInputDevice: Proxy object disconnected
09-12 13:57:15.821  2778  2778 D HealthService: Received stop request...Stopping profile...
09-12 13:57:15.821  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.821  4492  4492 D HidProfile: Bluetooth service disconnected
,09-12 13:57:15.831  2778  2778 D PanService: Received stop request...Stopping profile...
,09-12 13:57:15.831  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.831  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:57:15.831  4492  4492 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:57:15.831  4492  4492 D PanProfile: Bluetooth service disconnected
,09-12 13:57:15.831  2778  2778 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 13:57:15.841  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.841  7339  7350 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-12 13:57:15.841  7339  7350 D BadgeProvider: sendNotify, [notify] : null
09-12 13:57:15.841  7339  7350 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 13:57:15.841  1490  1490 D Launcher.Model: reloadBadges entered.
09-12 13:57:15.841  7339  7350 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:57:15.841  7339  7350 D BadgeProvider: update, [UpdateCount] : 1
,09-12 13:57:15.841  4492  4492 D BluetoothMap: Proxy object disconnected
09-12 13:57:15.841  4492  4492 D MapProfile: Bluetooth service disconnected
,09-12 13:57:15.841  2778  2778 D SapService: Received stop request...Stopping profile...
09-12 13:57:15.841  2778  2778 D SapService: Stopping Bluetooth SapService
09-12 13:57:15.841  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:15.841  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 13:57:15.841  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:57:15.841  2778  2778 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:57:15.841  2778  2778 D BluetoothA2dp: Proxy object disconnected
09-12 13:57:15.841  2778  2778 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-12 13:57:15.841  2778  2903 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:57:15.851  2778  2778 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:57:15.851  2778  2778 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-12 13:57:15.851  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 13:57:15.851  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 13:57:15.851  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 13:57:15.851  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.851  2778  2778 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:57:15.851  4492  4492 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 13:57:15.851  2778  2778 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:57:15.851  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 13:57:15.851  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 13:57:15.851  2778  2778 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:57:15.851  2778  2778 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 13:57:15.851  4492  4492 D SapProfile: Bluetooth service disconnected
,09-12 13:57:15.851  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 13:57:15.851  2778  2778 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-12 13:57:15.851  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 13:57:15.851  2778  2778 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 13:57:15.851  2778  2778 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 13:57:15.851  2778  2778 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 13:57:15.861  2778  2834 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:57:15.861  2778  2834 D BluetoothAdapterProperties: Setting state to 10
09-12 13:57:15.861  2778  2834 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:57:15.861  2778  2834 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:57:15.861  2778  2834 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 13:57:15.861  2778  2834 D BluetoothAdapterService: Autoconnection is available 
09-12 13:57:15.861  2778  2834 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 13:57:15.861  2778  2834 I BluetoothAdapterState: Entering OffState
,09-12 13:57:15.861  1459  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.861  1459  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.861  2778  2886 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.861  2778  2886 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.861  4492  4513 D Bluetoothsap: onBluetoothStateChange: up=false
,09-12 13:57:15.861  4492  4513 D Bluetoothsap: Unbinding service...
,09-12 13:57:15.871  1176  2333 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.871  1176  2333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.871  4492  4505 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:57:15.871  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:57:15.871  1446  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.871  1446  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.871  4492  4513 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.871  4492  4513 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.871  1698  1801 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.871  1698  1801 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.871  4492  4505 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:57:15.881  2778  2788 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:57:15.881  4492  4513 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:57:15.881  1679  1920 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.881  1679  1920 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.881  6625  6633 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:57:15.881  6625  6633 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.881  6625  6633 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 13:57:15.881  6625  6633 D BluetoothLeAdvertiser: Exit stop advertising
09-12 13:57:15.881  6625  6633 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 13:57:15.881  6625  6633 D BluetoothLeScanner: Exiting stopAllScan
,09-12 13:57:15.881  4492  4505 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:57:15.891  1429  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.891  1429  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.891  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:57:15.891  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:57:15.891  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:15.891  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,09-12 13:57:15.901  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:57:15.901  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:57:15.901  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-12 13:57:15.901  1176  1176 D BluetoothTile:  getBluetoothState : 10
,09-12 13:57:15.901  1869  1869 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 13:57:15.901  4492  4492 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
,09-12 13:57:15.911  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.911  1018  1952 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:57:15.911  1018  1030 I ActivityManager: Killing 6202:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-12 13:57:15.911  1018  1454 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:57:15.911  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 13:57:15.911  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.911  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.911  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-12 13:57:15.911  1018  1442 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 13:57:15.911  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.921  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 13:57:15.921  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:15.921  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:15.921  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:15.921  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.921  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:15.921  1625  1625 I Hs20UtilService: Starting #11
09-12 13:57:15.921  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:15.931  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:57:15.931  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:15.931  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:15.931  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:15.941  1018  1954 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:15.941   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:15.941  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:57:15.941   277  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-12 13:57:15.941  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:15.941  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.941  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:15.941  1625  1625 I Hs20UtilService: Starting #12
,09-12 13:57:15.941  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:15.951  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:57:15.951  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:15.951  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:15.951  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:15.951  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:15.951  6625  7374 D BluetoothAdapter: enable()
,09-12 13:57:15.961  1018  1329 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:15.961  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:15.961  1018  1329 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:15.961  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:15.961  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:15.961  1625  1625 I Hs20UtilService: Starting #13
09-12 13:57:15.961  1018  1952 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:15.961  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:15.971  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:57:15.971  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:57:15.971  1018  1127 E WifiNative-wlan0: invaild command id : 215
,09-12 13:57:15.971  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:57:15.971  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:15.971  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:15.971  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:15.971  1018  1952 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-12 13:57:15.971  1018  1952 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:15.971  1018  1952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:57:15.971  1018  1952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:57:15.971  1018  1952 D SettingsProvider: name = bluetooth_on
,09-12 13:57:15.981  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 13:57:15.981  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:15.981  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:57:15.981  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:57:15.981  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 13:57:15.981  2778  2834 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-12 13:57:15.981  2778  2834 D BluetoothAdapterProperties: Setting state to 11
09-12 13:57:15.981  2778  2834 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:57:15.981  2778  2834 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:57:15.981  2778  2834 D BluetoothAdapterService: updateAdapterState state is 11
09-12 13:57:15.981  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:15.981  2778  2834 D BluetoothAdapterService: Autoconnection is available 
09-12 13:57:15.981  2778  2834 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-12 13:57:15.981  2778  2834 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:57:15.981  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:57:15.981  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-12 13:57:15.991  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:57:15.991  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 13:57:15.991  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:57:15.991  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-12 13:57:15.991  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:57:15.991  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:57:15.991  2778  2834 W BluetoothAdapterS,ervice: Not skipping com.android.bluetooth.hfp.HeadsetService
09-12 13:57:15.991  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:15.991  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:57:15.991  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:15.991  1176  1176 D BluetoothTile:  getBluetoothState : 11
,09-12 13:57:15.991  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:57:15.991  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:57:16.001  1869  1869 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:57:16.001  4492  4492 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:16.001  1018  1489 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:57:16.001  1018  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:57:16.001  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:57:16.001  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.001  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:16.001  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:57:16.001  6994  6994 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:57:16.001  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.001  1018  1954 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:16.001  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.011  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.011  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.011  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:57:16.011  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.011  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 13:57:16.011  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:57:16.011  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:57:16.011  2778  2778 D HeadsetService: Received start request. Starting profile...
,09-12 13:57:16.011  2778  2778 D HeadsetService: start()
09-12 13:57:16.011  2778  2778 D HeadsetStateMachine: make
,09-12 13:57:16.021  2778  2778 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 13:57:16.021  1018  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:16.021  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.021  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.021  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.021  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.021  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-12 13:57:16.021  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:57:16.021  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-12 13:57:16.021  7012  7012 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:16.031  1018  1487 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 13:57:16.031  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.031  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.031  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.031  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:57:16.031  1018  1952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:16.031  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.031  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.031  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.031  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.031  1018  1329 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-12 13:57:16.031  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.031  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 13:57:16.031  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:57:16.031  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:57:16.031  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.031  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.031  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:57:16.041  2778  2778 I bluedroid: get_profile_interface handsfree
,09-12 13:57:16.041  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:16.041  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.041  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.041  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.041  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.041  4492  4492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:57:16.041  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 13:57:16.041  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:57:16.041  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:57:16.051  1018  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:57:16.051  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.051  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.051  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 13:57:16.051  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:57:16.051  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:16.051  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.051  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.051  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.051  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.061  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 13:57:16.061  2778  2778 E DualScoManager: Dual Sco Manager already instantiated
09-12 13:57:16.061  2778  2778 I DualScoManager: Set HeadsetServiceHelper
09-12 13:57:16.061  2778  2778 D BluetoothAtMessage: createCMTIContentObservers
,09-12 13:57:16.061  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:57:16.061  2778  2834 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-12 13:57:16.061  1018  1329 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 13:57:16.061  1018  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:57:16.061  1018  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:57:16.061  1018  1329 D SettingsProvider: selectionArgs: false
09-12 13:57:16.061  1018  1329 D SettingsProvider: selectionArgs: 1002
09-12 13:57:16.061  1018  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:57:16.061  1018  1329 D SettingsProvider: ret = -1
,09-12 13:57:16.061  1018  1442 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:16.061  2778  7376 D HeadsetStateMachine: Enter Disconnected: -2
09-12 13:57:16.061  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.061  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.061  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.061  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.071  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:57:16.071  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:57:16.071  2778  2834 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 13:57:16.071  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:57:16.071  2778  2778 D HeadsetService: mStartError = false
,09-12 13:57:16.071  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:16.071  2778  2778 D A2dpService: Received start request. Starting profile...
,09-12 13:57:16.071  2778  2778 D A2dpService: start()
09-12 13:57:16.071  2778  2778 I bluedroid: get_profile_interface avrcp
,09-12 13:57:16.071  1018  1952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:16.071  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.071  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.071  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:16.071  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:16.081  2778  2778 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 13:57:16.081  2778  2778 D Avrcp   : Initialize Media Controller
09-12 13:57:16.081  2778  2778 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-12 13:57:16.081  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:57:16.081  4492  4492 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:16.081  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:57:16.081  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:57:16.081  2778  2834 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:57:16.081  2778  2834 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:57:16.081  2778  2834 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 13:57:16.081  2778  7376 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 13:57:16.081  2778  7376 D HeadsetStateMachine: map size, before remove : 0
09-12 13:57:16.081  2778  7376 D HeadsetStateMachine: map size, after remove: 0
,09-12 13:57:16.081  2778  2778 E Avrcp   : getActiveSessions,
09-12 13:57:16.081  2778  2778 D Avrcp   : pick active media Controller,
09-12 13:57:16.081  2778  2778 D Avrcp   : Get the active Media Controller 
,09-12 13:57:16.091  2778  2778 I Avrcp   :  Updating now playing list upon AVRCP Start
09-12 13:57:16.091  4492  4492 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:57:16.091  2778  7379 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 13:57:16.091  2778  2778 D A2dpStateMachine: make
,09-12 13:57:16.091  2778  2778 I bluedroid: get_profile_interface a2dp
09-12 13:57:16.091  2778  7381 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:57:16.091  2778  2778 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 13:57:16.091  2778  2778 D A2dpService: mStartError = false
09-12 13:57:16.091  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:16.091  2778  2778 D HeadsetStateMachine: Try to query the phonestate on bind
09-12 13:57:16.091  1429  1455 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:57:16.091  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:16.091  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
09-12 13:57:16.091  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 13:57:16.091  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:57:16.091  1429  1455 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 13:57:16.091  2778  2778 D HidService: Received start request. Starting profile...
09-12 13:57:16.091  2778  2778 D HidService: start()
09-12 13:57:16.091  2778  2778 I bluedroid: get_profile_interface hidhost
09-12 13:57:16.091  2778  2778 D HidService: setHidService(): set to: null
09-12 13:57:16.091  2778  2778 D HidService: mStartError = false
09-12 13:57:16.091  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:16.091  2778  2778 D HeadsetStateMachine: Proxy object connected
09-12 13:57:16.091  2778  2778 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 13:57:16.091  2778  7380 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:57:16.091  2778  7376 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:57:16.101  2778  2778 D HealthService: Received start request. Starting profile...
09-12 13:57:16.101  2778  2778 D HealthService: start()
,09-12 13:57:16.101  2778  2778 I bluedroid: get_profile_interface health
,09-12 13:57:16.101  2778  2778 D HealthService: mStartError = false
09-12 13:57:16.101  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:16.101  2778  2778 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 13:57:16.101  2778  7376 D HeadsetStateMachine: Disconnected process message: 18
09-12 13:57:16.101  2778  2778 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-12 13:57:16.101  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-12 13:57:16.101  2778  2778 D PanService: Received start request. Starting profile...
09-12 13:57:16.101  2778  2778 D PanService: start()
09-12 13:57:16.101  2778  2778 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:57:16.101  2778  2778 I bluedroid: get_profile_interface pan
09-12 13:57:16.101  2778  2778 D PanService: mStartError = false
09-12 13:57:16.101  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:16.101  2778  2778 D BluetoothMapService: Received start request. Starting profile...
09-12 13:57:16.101  2778  2778 D BluetoothMapService: start()
,09-12 13:57:16.101  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:16.101  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:16.101  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:16.101  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:16.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:57:16.121  7385  7385 E Zygote  : MountEmulatedStorage()
,09-12 13:57:16.121  7385  7385 E Zygote  : v2
,09-12 13:57:16.121  1018  1329 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7385 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-12 13:57:16.121  7385  7385 I libpersona: KNOX_SDCARD checking this for 10055
09-12 13:57:16.121  7385  7385 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:16.121  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:16.121  2778  2778 D BluetoothMapService: mStartError = false
09-12 13:57:16.121  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:16.121  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 13:57:16.121  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:57:16.121  2778  7376 D HeadsetStateMachine: Disconnected process message: 10
09-12 13:57:16.121  2778  7376 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:57:16.121  2778  7376 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:57:16.121  2778  2778 D SapService: Received start request. Starting profile...
09-12 13:57:16.121  2778  2778 D SapService: start()
09-12 13:57:16.121  2778  2778 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 13:57:16.121  2778  2778 I bluedroid: get_profile_interface sap
09-12 13:57:16.121  2778  2778 D SapService: mStartError = false
09-12 13:57:16.121  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
09-12 13:57:16.121  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 13:57:16.121  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 13:57:16.121  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 13:57:16.121  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 13:57:16.121  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:16.121  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:16.131  2778  7379 D BluetoothMediaBrowser: no now playing list
09-12 13:57:16.131  2778  7379 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 13:57:16.141  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-12 13:57:16.141  2778  2778 E BluetoothAdapterService(1014110304): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 13:57:16.141  2778  2834 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 13:57:16.141  2778  2834 I bluedroid: enable
,09-12 13:57:16.141  2778  2837 E bt-btif : Calling BTA_HhEnable
09-12 13:57:16.141  2778  2837 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 13:57:16.141  2778  2837 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 13:57:16.141  2778  2837 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-12 13:57:16.141  2778  2837 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-12 13:57:16.141  2778  2837 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:57:16.141  2778  2837 I bluedroid: getModelRssiValues
09-12 13:57:16.141  2778  2837 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 13:57:16.141  2778  2837 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:57:16.141  2778  2837 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-12 13:57:16.151  1018  1018 D SettingsProvider: name = bluetooth_name
,09-12 13:57:16.151  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:16.151  7385  7385 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:16.151  2778  2837 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:57:16.151  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.151  2778  2837 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:57:16.151  2778  2837 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:57:16.151  2778  2837 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-12 13:57:16.151  2778  2837 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-12 13:57:16.151  2778  2837 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-12 13:57:16.151  2778  2837 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 13:57:16.151  2778  2837 E bt-btif : JVenable fails
,09-12 13:57:16.151  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:16.151  2778  2837 D bte_conf: Device ID record 1 : primary
09-12 13:57:16.151  2778  2837 D bte_conf:   vendorId            = 0075
09-12 13:57:16.151  2778  2837 D bte_conf:   vendorIdSource      = 0001
09-12 13:57:16.151  2778  2837 D bte_conf:   product             = 0100
09-12 13:57:16.151  2778  2837 D bte_conf:   version             = 0200
09-12 13:57:16.151  2778  2837 D bte_conf:   clientExecutableURL = 
09-12 13:57:16.151  2778  2837 D bte_conf:   serviceDescription  = 
09-12 13:57:16.151  2778  2837 D bte_conf:   documentationURL    = 
09-12 13:57:16.151  2778  2837 D bte_conf: bte_load_did_conf no section named DID2.
09-12 13:57:16.151  2778  2837 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 13:57:16.151  2778  2837 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:57:16.151  2778  2834 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 13:57:16.151  2778  2834 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:57:16.151  2778  2834 D BluetoothAdapterProperties: State =  11
09-12 13:57:16.161  1018  1442 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:57:16.161  2778  2834 D BluetoothAdapterProperties: Setting state to 12
09-12 13:57:16.161  2778  2834 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 13:57:16.161  2778  2837 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:57:16.161  2778  2837 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:57:16.161  2778  2837 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:57:16.161  1018  1329 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 13:57:16.161  1018  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:57:16.161  1018  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:57:16.161  1018  1329 D SettingsProvider: selectionArgs: false
09-12 13:57:16.161  1018  1329 D SettingsProvider: selectionArgs: 1002
09-12 13:57:16.161  1018  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:57:16.161  1018  1329 D SettingsProvider: ret = -1
,09-12 13:57:16.161  2778  2834 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:57:16.161  2778  2834 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 13:57:16.161  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:16.161  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.171  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.171  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.171  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.171  2778  2834 D BluetoothAdapterService: Autoconnection is available 
09-12 13:57:16.171  2778  2834 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 13:57:16.171  2778  2834 D BluetoothAdapterService: starting service from this receiver
,09-12 13:57:16.171  1018  1952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:57:16.171  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.171  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.171  1459  2465 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:57:16.171  1459  2465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:57:16.171  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.181  2778  2778 I BluetoothPbapService: Handler(): got msg=1
09-12 13:57:16.181  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.181  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.181  2778  2886 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.181  2778  2886 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:57:16.181  1018  1137 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:57:16.181  2778  2834 I BluetoothAdapterState: Entering On State from state = 11
,09-12 13:57:16.181  4492  4513 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 13:57:16.181  4492  4513 D Bluetoothsap: Binding service...
,09-12 13:57:16.181  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:16.181  7385  7385 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 13:57:16.191  4492  4513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 13:57:16.191  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 13:57:16.191  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.191  2778  2778 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 13:57:16.191  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.191  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.191  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.191  6625  6625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 13:57:16.191  2778  7401 V BluetoothPbapService: PBAP Service initSocket try: 0
09-12 13:57:16.191  4492  4513 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 13:57:16.191  6625  6625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 13:57:16.201  4492  4505 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.201  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:57:16.201  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:57:16.201  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.201  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.201  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.201  4492  4505 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:57:16.201  2778  7401 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:57:16.201  2778  7401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:16.201  4492  4492 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-12 13:57:16.201  4492  4492 D SapProfile: Bluetooth service connected
09-12 13:57:16.201  4492  4492 D Bluetoothsap: getConnectedDevices()
,09-12 13:57:16.201  2778  7401 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-12 13:57:16.201  2778  7401 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:16.201  2778  7401 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:16.201  2778  7401 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9d6b3ba
09-12 13:57:16.201  2778  7401 D BluetoothSocket: channel: 19
09-12 13:57:16.201  2778  7401 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.211  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.211  1429  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.211  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:57:16.211  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:57:16.211  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.211  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.211  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.211  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:16.211  1429  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:57:16.211  4492  4513 D BluetoothPan: Binding service...
09-12 13:57:16.211  4492  4492 D HeadsetProfile: Bluetooth service connected
,09-12 13:57:16.211  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 13:57:16.211  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.221  7385  7385 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 13:57:16.221  7385  7385 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 13:57:16.221  7385  7385 D UserAnalysis: Create SecureDbHelper
,09-12 13:57:16.221  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.221  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.221  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.221  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.221  1176  1189 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.221  1176  1189 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:57:16.221  4492  4513 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:57:16.221  4492  4492 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:57:16.221  4492  4492 D PanProfile: Bluetooth service connected
,09-12 13:57:16.221  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 13:57:16.221  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.221  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.221  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.221  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.221  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:57:16.231  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:57:16.231  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.231  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:57:16.231  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.231  7385  7385 D IntelligenceServiceApplication: onCreate()
09-12 13:57:16.231  4492  4492 D BluetoothInputDevice: Proxy object connected
09-12 13:57:16.231  4492  4492 D HidProfile: Bluetooth service connected
09-12 13:57:16.231  1446  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.231  1446  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:57:16.231  4492  4505 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.231  4492  4505 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:57:16.231  1698  1710 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.231  1698  1710 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:57:16.231  4492  4513 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:57:16.231  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:16.231  1018  1018 D BluetoothA2dp: Proxy object connected
,09-12 13:57:16.231  1018  1952 I ActivityManager: Killing 6924:com.android.vending/u0a26 (adj 15): empty #21
,09-12 13:57:16.241  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 13:57:16.241  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.241  7385  7385 D IntelligenceServiceApplication: no applications having user consent for prediction
09-12 13:57:16.241  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.241  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.241  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.241  2778  7336 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:57:16.241  2778  7336 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 13:57:16.241  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-12 13:57:16.241  4492  4492 D BluetoothPbap: Proxy object connected
09-12 13:57:16.241  4492  4492 D PbapServerProfile: Bluetooth service connected
,09-12 13:57:16.241  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-12 13:57:16.241  7385  7385 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 13:57:16.241  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:16.241  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:16.241  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:16.241  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:16.251  7385  7385 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 13:57:16.251  7405  7405 E Zygote  : MountEmulatedStorage()
,09-12 13:57:16.251  7405  7405 E Zygote  : v2
09-12 13:57:16.251  7405  7405 I libpersona: KNOX_SDCARD checking this for 10105
09-12 13:57:16.251  7405  7405 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:16.261  7405  7405 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:16.261  7405  7405 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:16.261  7405  7405 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:57:16.261  1018  1952 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7405 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 13:57:16.261  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:57:16.261  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.261  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.261  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.261  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.261  2778  2778 D BluetoothA2dp: Proxy object connected
09-12 13:57:16.261  2778  2778 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-12 13:57:16.271  4492  4505 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:57:16.271  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 13:57:16.271  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.271  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.271  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.271  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 13:57:16.271  1018  1047 D BluetoothPan: Binding service...
09-12 13:57:16.271  4492  4492 D BluetoothMap: Proxy object connected
09-12 13:57:16.271  4492  4492 D MapProfile: Bluetooth service connected
09-12 13:57:16.271  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:57:16.271  4492  4492 D BluetoothMap: getConnectedDevices()
09-12 13:57:16.271  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 13:57:16.271  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:57:16.271  1459  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.281  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
09-12 13:57:16.281  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:57:16.281  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.281  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.281  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-12 13:57:16.281  1459  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:57:16.281  1429  1455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 13:57:16.281  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:57:16.281  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:57:16.281  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.281  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.281  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.281  1429  1455 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:57:16.281  1429  7402 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.291  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:57:16.291  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:57:16.291  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.291  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.291  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 13:57:16.291  1429  7402 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:57:16.291   309   309 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 759us total 29.443ms
,09-12 13:57:16.291  1679  1920 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.291  1679  1920 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:57:16.291  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:57:16.291  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:57:16.291  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:57:16.291  6625  6639 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.291  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 13:57:16.291  6625  6639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:57:16.291  7405  7405 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:16.291  7405  7405 D ActivityThread: Added TimaKeyStore provider
09-12 13:57:16.291  4492  4505 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:57:16.291  4492  4505 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 13:57:16.291  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:57:16.291  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:57:16.291  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.291  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.291  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.291  1429  1455 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.291  1429  1455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:57:16.291  4492  4492 D BluetoothA2dp: Proxy object connected
09-12 13:57:16.291  4492  4492 D A2dpProfile: Bluetooth service connected
09-12 13:57:16.291  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:57:16.301  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:57:16.301  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:57:16.301  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:57:16.301  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:16.301  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
09-12 13:57:16.301  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:57:16.301   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.542ms
,09-12 13:57:16.311  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@18d43197, true
,09-12 13:57:16.311  1429  1429 D BluetoothHeadset: registerMessageListener,
09-12 13:57:16.311  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:57:16.311  1869  1869 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 13:57:16.311  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:57:16.321  1018  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:57:16.321  1018  1488 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4188, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 13:57:16.321  1018  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 13:57:16.321  1018  1488 D BatteryService: stay LED for charging
09-12 13:57:16.321  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:57:16.321  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:16.321  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:57:16.321  1176  1176 D BluetoothTile:  getBluetoothState : 12
,09-12 13:57:16.321  2778  2886 D HeadsetService: registerMessageListener
,09-12 13:57:16.321  2778  2886 D HeadsetService: registerMessageListener
09-12 13:57:16.321  2778  7376 D HeadsetStateMachine: Disconnected process message: 70
09-12 13:57:16.321  2778  7376 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1709626b
,09-12 13:57:16.331  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:16.331  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 13:57:16.331  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:57:16.331   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.826ms
,09-12 13:57:16.331  1018  1454 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:57:16.331  1018  1018 I MotionRecognitionService: Plugged
09-12 13:57:16.331  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
09-12 13:57:16.331  2778  7421 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-12 13:57:16.331  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:57:16.331  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.331  1018  1442 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 13:57:16.331  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:57:16.331  1176  1725 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:57:16.331  4492  4492 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:16.331  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:16.331  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:57:16.331  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 13:57:16.331  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 13:57:16.341  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-12 13:57:16.341  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 13:57:16.341  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 13:57:16.341  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:57:16.341  2778  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:57:16.341  4492  4492 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 13:57:16.341  2778  7376 D HeadsetStateMachine: Disconnected process message: 9
09-12 13:57:16.341  2778  7376 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-12 13:57:16.341  2778  7421 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:57:16.341  2778  7421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:57:16.351  4492  4492 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 13:57:16.351  4492  4492 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 13:57:16.351  4492  4492 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-12 13:57:16.351  2778  7421 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-12 13:57:16.351  2778  7421 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:16.351  2778  7421 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:16.351  2778  7421 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34bdb1c8
09-12 13:57:16.351  2778  7421 D BluetoothSocket: channel: 5
,09-12 13:57:16.351   282   698 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 13:57:16.351   282   698 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 13:57:16.351   282   698 V voice   : voice_set_parameters: exit with code(-2)
09-12 13:57:16.351   282   698 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 13:57:16.351   282   698 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 13:57:16.351   282   698 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 13:57:16.351   282   698 V audio_hw_primary: adev_set_parameters: exit
09-12 13:57:16.351  2778  7376 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 13:57:16.351  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:57:16.351  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 13:57:16.351  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:16.351  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:16.431   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 13:57:16.431   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:16.441  7405  7426 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 13:57:16.441   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 13:57:16.441   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:16.441  7405  7426 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 13:57:16.481  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:16.481  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:16.491  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:16.491  1018  1030 D SecContentProvider2: mCursor = null
,09-12 13:57:16.491  1018  1030 D WifiService: setWifiEnabled: false pid=6625, uid=10170
,09-12 13:57:16.491  1018  1030 D SettingsProvider: name = wifi_on
,09-12 13:57:16.521  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1,
09-12 13:57:16.521  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
09-12 13:57:16.521  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:16.521  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:57:16.521  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-12 13:57:16.521  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler },
,09-12 13:57:16.531  1018  1442 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:57:16.531  1018  1442 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:16.531  1018  1442 D SecContentProvider2: mCursor = null
,09-12 13:57:16.541  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 13:57:16.541  1018  1129 E ConnectivityService: updateNetworkInfo()
,09-12 13:57:16.541  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 13:57:16.541  1018  1129 E ConnectivityService: updateNetworkInfo()
,09-12 13:57:16.551  1018  1126 D WifiP2pService: P2pDisablingState
,09-12 13:57:16.551  1018  1442 D WifiService: setWifiEnabled: false pid=6625, uid=10170
09-12 13:57:16.551  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:57:16.551  1018  1126 D WifiP2pService: p2p socket connection lost
,09-12 13:57:16.551  1018  1126 D WifiP2pService: P2pDisabledState
,09-12 13:57:16.551  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:57:16.551  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:57:16.551  1018  1442 D SettingsProvider: name = wifi_on
09-12 13:57:16.551  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:57:16.551  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:57:16.551  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:16.561  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 13:57:16.561   277  1017 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:57:16.561  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:57:16.561  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:16.561  1018  1048 D WifiDisplayController: disconnect
09-12 13:57:16.561  1018  1048 D WifiDisplayController: updateConnection
09-12 13:57:16.561  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:16.561  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:57:16.561  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 13:57:16.561  1018  1489 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:57:16.561  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:57:16.561  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:57:16.571  7249  7249 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:16.581  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:16.581  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:16.591  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:16.591  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:16.591  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.591  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.591  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:16.591  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:16.591  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:16.591  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-12 13:57:16.591  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:57:16.591  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:16.591  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:16.591  1176  1176 D HotspotTile: onReceive : 0, 0
,09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.601  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.601  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.611  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:16.611  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:16.611  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=216 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.k.d(PG:583)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  7405  7405 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:16.671  7405  7405 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:16.671  1018  1031 I ActivityManager: Killing 7067:com.sec.pcw.device/1000 (adj 15): empty #21
09-12 13:57:16.681  4492  4492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:57:16.681  1018  1952 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:57:16.681  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-12 13:57:16.681  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.681  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.681  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-12 13:57:16.691  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:16.691  4492  4492 D DockEventReceiver: finishStartingService: stopping service
09-12 13:57:16.691  4492  4492 D BluetoothNotiBroadcastReceiver: onReceive
09-12 13:57:16.691  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:16.691  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 13:57:16.711  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.711  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:16.711  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-12 13:57:16.721  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:57:16.731  7249  7249 I wpa_supplicant: Blacklist: Clear (all) 
09-12 13:57:16.731  4492  4492 D BluetoothNotiBroadcastReceiver: onReceive
09-12 13:57:16.731  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:57:16.731  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 13:57:16.741  4492  4492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:57:16.751  1018  1442 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:57:16.751  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.751  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.751  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.751  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:57:16.751  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:57:16.761  4492  4492 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:57:16.761  4492  4492 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:57:16.761  7405  7437 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 13:57:16.771  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:57:16.771  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 13:57:16.771  2778  2778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:16.771  2778  2778 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:57:16.771  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:57:16.771  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 13:57:16.781  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.781  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.781  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:57:16.781  7249  7249 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 13:57:16.781  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:16.781  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:16.781  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:57:16.781  7249  7249 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
09-12 13:57:16.781  7249  7249 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 13:57:16.791  1018  1952 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:16.791  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.791  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:16.791  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 13:57:16.791  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:57:16.801  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:57:16.801  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:16.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:16.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:57:16.801  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:16.801  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:57:16.801  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:16.801  2778  7447 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:57:16.801  2778  7447 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:16.811  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:16.811  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:57:16.811  6994  6994 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:57:16.811  2778  7447 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-12 13:57:16.811  2778  7447 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:16.811  2778  7447 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:16.811  2778  7447 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ce02274
,09-12 13:57:16.811  2778  7447 D BluetoothSocket: channel: 12
09-12 13:57:16.811  2778  7447 I BtOppRfcommListener: Accept thread started.
,09-12 13:57:16.811  7012  7012 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:16.821  1018  1308 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:16.821  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:16.821  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:16.821  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.821  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:16.821  1625  1625 I Hs20UtilService: Starting #14
,09-12 13:57:16.821  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:16.821  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:57:16.831  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:16.831  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:16.831  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:57:16.831  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:16.831  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:57:16.831  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:16.841  1018  1954 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:16.841  1018  1954 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:16.841  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:16.841  1018  1954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:16.841  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:16.841  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:57:16.841  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:16.841  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:57:16.841  1625  1625 I Hs20UtilService: Starting #15
09-12 13:57:16.841  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:16.851  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:16.971  7249  7249 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:57:17.061  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 13:57:17.061  1018  1488 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:17.061  1018  1488 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:17.061  1018  1488 D SecContentProvider2: mCursor = null
,09-12 13:57:17.061  1018  1488 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:17.061  1018  1488 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:17.061  1018  1488 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:17.061  1018  1488 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972),
09-12 13:57:17.061  1018  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216),
09-12 13:57:17.061  1018  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204),
09-12 13:57:17.061  1018  1488 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223),
09-12 13:57:17.061  1018  1488 W WifiService: 	,at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:17.061  1018  1488 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:17.061  1018  1488 D SettingsProvider: name = wifi_on
,09-12 13:57:17.071  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-12 13:57:17.071  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:17.071  1018  1030 D SecContentProvider2: mCursor = null
,09-12 13:57:17.071  1018  1030 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:17.071  1018  1030 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:17.071  1018  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:17.071  1018  1030 W WifiService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:17.071  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:17.071  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:17.071  1018  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223),
09-12 13:57:17.071  1018  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:17.071  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:17.071  1018  1030 D SettingsProvider: name = wifi_on
,09-12 13:57:17.111   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:57:17.111  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:17.111  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:17.111  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:17.111  7249  7249 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 13:57:17.211  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 13:57:17.211  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:57:17.211  7044  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:17.221  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
,09-12 13:57:17.231  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:57:17.231  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:17.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:17.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:17.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:57:17.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:17.231  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:17.231  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-12 13:57:17.231  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:17.231  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:57:17.231  1176  1176 D HotspotTile: onReceive : 1, 0
,09-12 13:57:17.231  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:17.241  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:17.241  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:17.241  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:17.251  1679  2177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:17.251  1018  1454 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:17.251  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:17.251  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:17.251  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:17.251  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:17.251  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:57:17.261  1625  1625 I Hs20UtilService: Starting #16
09-12 13:57:17.261  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:17.261  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:57:17.261  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:17.261  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:17.571  1018  1487 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:17.571  1018  1487 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:17.571  1018  1487 D SecContentProvider2: mCursor = null
,09-12 13:57:17.571  1018  1487 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:17.571  1018  1487 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:17.581  1018  1487 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:17.581  1018  1487 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:17.581  1018  1487 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:17.581  1018  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:17.581  1018  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:17.581  1018  1487 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:17.581  1018  1487 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:17.581  1018  1487 D SettingsProvider: name = wifi_on
,09-12 13:57:17.581  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:17.921  1018  1045 D Tethering: interfaceRemoved wlan0
,09-12 13:57:17.921  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 13:57:18.041  1018  1045 D Tethering: interfaceRemoved p2p0
,09-12 13:57:18.041  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:57:18.091  1018  1442 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:18.091  1018  1442 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:18.091  1018  1442 D SecContentProvider2: mCursor = null
,09-12 13:57:18.091  1018  1442 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:18.091  1018  1442 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:18.091  1018  1442 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:18.091  1018  1442 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:18.091  1018  1442 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:18.091  1018  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:18.091  1018  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:18.091  1018  1442 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:18.091  1018  1442 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:18.091  1018  1442 D SettingsProvider: name = wifi_on
,09-12 13:57:18.091  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
09-12 13:57:18.091  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:18.091   287   287 E SMD     : DCD OFF
,09-12 13:57:18.091   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:18.091   277  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-12 13:57:18.101  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:18.101  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:18.101  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 13:57:18.101   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:57:18.591  1018  1329 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:18.591  1018  1329 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:18.591  1018  1329 D SecContentProvider2: mCursor = null
,09-12 13:57:18.591  1018  1329 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:18.591  1018  1329 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:18.591  1018  1329 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:18.591  1018  1329 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:18.591  1018  1329 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:18.591  1018  1329 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:18.591  1018  1329 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:18.591  1018  1329 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:18.591  1018  1329 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:57:18.591  1018  1329 D SettingsProvider: name = wifi_on
,09-12 13:57:18.591  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:18.821  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:57:18.821  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 13:57:19.091  1018  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:57:19.091  1018  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:19.091  1018  1489 D SecContentProvider2: mCursor = null
,09-12 13:57:19.091  1018  1489 D WifiService: setWifiEnabled: true pid=6625, uid=10170
,09-12 13:57:19.091  1018  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:57:19.091  1018  1489 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:19.091  1018  1489 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:19.091  1018  1489 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:19.091  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:19.091  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:19.091  1018  1489 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:19.091  1018  1489 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:57:19.091  1018  1489 D SettingsProvider: name = wifi_on
,09-12 13:57:19.101  1018  1128 E WifiController: illegal state found both WifiController and WifiStateMachine
,09-12 13:57:19.101   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-12 13:57:19.161  1018  1045 D Tethering: interfaceAdded wlan0
,09-12 13:57:19.161  1018  1132 E Tethering: No numeric data
,09-12 13:57:19.161  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:57:19.161  1018  1132 D Tethering: clearTetheredNotification()
,09-12 13:57:19.161  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:19.161  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:19.171  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-12 13:57:19.171  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:57:19.171  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-12 13:57:19.171  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:57:19.171  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:57:19.171  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:57:19.171  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:19.181  1018  1132 D Tethering: InitialState.processMessage what=4
09-12 13:57:19.181  1018  1124 V NetworkStats: performPollLocked() took 13ms
09-12 13:57:19.181  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:19.181  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:19.181  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:19.181  1018  1132 E Tethering: No numeric data
09-12 13:57:19.181  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:57:19.181  1018  1132 D Tethering: clearTetheredNotification()
09-12 13:57:19.181  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:19.181  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:19.191  1018  1045 D Tethering: interfaceAdded p2p0
,09-12 13:57:19.191  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:19.191  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-12 13:57:19.191  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:57:19.191  1176  1176 D HotspotTile: updateTetherState():false, false
09-12 13:57:19.191  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-12 13:57:19.191  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:57:19.201  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:19.201  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:19.201   277  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:57:19.201  1018  1124 V NetworkStats: performPollLocked() took 13ms
09-12 13:57:19.201  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:19.201   277  1017 D SoftapController: Softap fwReload - Ok
,09-12 13:57:19.201  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:19.201  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:19.201   277  1017 D CommandListener: Setting iface cfg
09-12 13:57:19.201   277  1017 D CommandListener: Trying to bring down wlan0
,09-12 13:57:19.201   277  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:57:19.211  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 13:57:19.251  7461  7461 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:57:19.251  7461  7461 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 13:57:19.251  7461  7461 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 13:57:19.271  7461  7461 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-12 13:57:19.281   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7461
,09-12 13:57:19.281   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 13:57:19.281  7461  7461 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:57:19.281  7461  7461 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:19.281  7461  7461 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:57:19.281  7461  7461 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 13:57:19.281   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7461
09-12 13:57:19.281   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-12 13:57:19.311  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 13:57:19.321  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:19.321  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:19.321  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:57:19.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:19.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:19.321  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:57:19.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:19.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 13:57:19.321  1176  1176 D HotspotTile: onReceive : 2, 0
,09-12 13:57:19.321  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:19.321  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:19.331  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:19.331  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:19.331  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:19.331  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:19.331  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:19.341  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:57:19.341  1625  1625 I Hs20UtilService: Starting #17
,09-12 13:57:19.341  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:19.341  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:19.341  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:19.341  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:19.441   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-12 13:57:19.441  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-12 13:57:19.481  7461  7461 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:57:19.481  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:57:19.491  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-12 13:57:19.491   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7461
09-12 13:57:19.491   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 13:57:19.491  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:57:19.491  7461  7461 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:19.491  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:57:19.491  7461  7461 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:19.491  7461  7461 E wpa_supplicant: SIM READ ERROR
09-12 13:57:19.491  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:19.491  7461  7461 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:19.491  7461  7461 E wpa_supplicant: SIM READ ERROR
,09-12 13:57:19.491  7461  7461 I wpa_supplicant: Blacklist: Clear (all) 
09-12 13:57:19.501  7461  7461 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:57:19.501  7461  7461 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:57:19.501  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:19.501  7461  7461 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 13:57:19.501  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:57:19.501  7461  7461 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:57:19.501  7461  7461 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 13:57:19.501  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:57:19.501  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:19.501  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-12 13:57:19.581  7461  7461 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 13:57:19.601  1018  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-12 13:57:19.601  1018  1489 D WifiService: setWifiEnabled: true pid=6625, uid=10170
09-12 13:57:19.601  1018  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:57:19.601  1018  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
09-12 13:57:19.601  1018  1489 D SecContentProvider2: mCursor = null
09-12 13:57:19.601  1018  1489 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:57:19.601  1018  1489 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6625, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:57:19.601  1018  1489 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 13:57:19.601  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:57:19.601  1018  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:57:19.601  1018  1489 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:57:19.601  1018  1489 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:57:19.601  1018  1489 D SettingsProvider: name = wifi_on
,09-12 13:57:19.691  7461  7461 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-12 13:57:19.691  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-12 13:57:19.701  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 13:57:19.701   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7461
09-12 13:57:19.701   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-12 13:57:19.711  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:57:19.711  7461  7461 I wpa_supplicant: ssSupport state is = 1,
09-12 13:57:19.711  7461  7461 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:57:19.711  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:57:19.721  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 13:57:19.721   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7461
09-12 13:57:19.721   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-12 13:57:19.721  7461  7461 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:57:19.721  7461  7461 I wpa_supplicant: ssSupport state is = 1
09-12 13:57:19.721  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:57:19.731  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:57:19.721  7461  7461 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:19.721  7461  7461 E wpa_supplicant: SIM READ ERROR
09-12 13:57:19.721  7461  7461 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:57:19.721  7461  7461 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:57:19.721  7461  7461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:57:19.731  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:19.731  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:19.731  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:19.731  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-12 13:57:19.731  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:19.861  7461  7461 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 13:57:19.861  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:57:19.961  7461  7461 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 13:57:19.961  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 13:57:19.961  7461  7461 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:57:19.971  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-12 13:57:19.971  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:57:19.971  7461  7461 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 13:57:19.971  7461  7461 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:57:19.971  7461  7461 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:57:19.971  7461  7461 E wpa_supplicant: SIM READ ERROR
,09-12 13:57:19.971  7461  7461 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:57:19.991  7461  7461 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 13:57:20.001  7461  7461 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:57:20.001  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:57:20.011  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:20.011  4492  4492 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:57:20.011  1018  1127 E WifiConfigStore: Not a HS20
,09-12 13:57:20.011  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:20.011  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:57:20.011  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:20.011  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:20.011  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:20.021  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:20.021  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:20.021  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:57:20.021  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-12 13:57:20.021  1176  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:57:20.021  1176  1176 D HotspotTile: onReceive : 3, 0
,09-12 13:57:20.031  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 13:57:20.031  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:20.031  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:20.031  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:20.031  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:20.031  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:20.031  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:20.031  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:20.031  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 13:57:20.031  7461  7461 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:57:20.031  7461  7461 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 13:57:20.031  7461  7461 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:57:20.031  7461  7461 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:57:20.031  7461  7461 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:57:20.031  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:57:20.031  7461  7461 I wpa_supplicant: First Scan Start
09-12 13:57:20.031  7461  7461 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:57:20.041  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-12 13:57:20.041  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:57:20.041  1018  1127 I WifiNative-HAL: startHal
09-12 13:57:20.041  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ece188c
09-12 13:57:20.041  1018  1127 I WifiNative-HAL: Could not start hal
,09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:20.041  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:20.041  7044  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:57:20.041  1018  1127 E WifiNative-wlan0: do suspend true
,09-12 13:57:20.041  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 13:57:20.041  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 13:57:20.041  1625  1625 I Hs20UtilService: Starting #18
09-12 13:57:20.041  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:20.041   277  1017 D CommandListener: Setting iface cfg
09-12 13:57:20.041   277  1017 D CommandListener: Trying to bring up p2p0
,09-12 13:57:20.051  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:57:20.051  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:57:20.051  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:20.051  1018  1152 I WifiNative-HAL: startHal
09-12 13:57:20.051  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9d8ee9bc
09-12 13:57:20.051  1018  1152 I WifiNative-HAL: Could not start hal
09-12 13:57:20.051  1018  1152 E WifiScanningService: could not start HAL
09-12 13:57:20.051  1018  1126 D WifiP2pService: P2pEnablingState
09-12 13:57:20.051  1625  1662 I Hs20UtilService: Message received 5011
,09-12 13:57:20.051  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 13:57:20.051  1018  1126 D WifiP2pService: P2p socket connection successful
,09-12 13:57:20.051  1018  1126 D WifiP2pService: P2pEnabledState
,09-12 13:57:20.051  1018  1018 D RttService: SCAN_AVAILABLE : 3
,09-12 13:57:20.051  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:20.051  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:57:20.051  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:57:20.051  1018  1127 E WifiNative-wlan0: invaild command id : 215
,09-12 13:57:20.051  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:57:20.051  6861  6861 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:57:20.051  6861  6861 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:57:20.051  6861  6861 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:57:20.061  7461  7461 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:57:20.061  7461  7461 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-12 13:57:20.061  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 13:57:20.061  7461  7461 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-12 13:57:20.061  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:20.061  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:57:20.061  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:57:20.061  1018  1127 E WifiStateMachine: Failed to set frequency band 0
,09-12 13:57:20.061  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:20.061  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:20.061  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 13:57:20.061  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:20.061  1018  1048 D WifiDisplayController: disconnect,
09-12 13:57:20.061  1018  1048 D WifiDisplayController: updateConnection
09-12 13:57:20.061  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:57:20.061  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:57:20.071  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:20.071  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:57:20.071  1018  1329 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:57:20.071  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:57:20.071  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-12 13:57:20.071  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:57:20.081  1018  1127 E WifiNative-wlan0: invaild command id : 215
09-12 13:57:20.081  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 13:57:20.081  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:20.081  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:57:20.081  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:57:20.081  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
09-12 13:57:20.081  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:57:20.081  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-12 13:57:20.081  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:57:20.081  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 13:57:20.081  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
09-12 13:57:20.081  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:20.081  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:57:20.081  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  secondary type: null
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  wps: 0
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  grpcapab: 0
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  devcapab: 0
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  status: 3
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  wfdInfo: null
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-12 13:57:20.081  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-12 13:57:20.081  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:57:20.081  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:20.081  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:57:20.091  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:20.091  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:57:20.091  6994  6994 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 13:57:20.091  6994  6994 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:57:20.101  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 13:57:20.101  1018  1126 D WifiP2pService: InactiveState
,09-12 13:57:20.101  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:57:20.101  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:57:20.101  7461  7461 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:57:20.101  1018  1126 D WifiP2pService: InactiveState{ what=143376 },
09-12 13:57:20.101  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:57:20.101  7012  7012 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-12 13:57:20.101  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:20.111  6625  7469 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-12 13:57:20.111  6625  7469 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:57:20.181  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:57:20.181  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:57:20.181  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:57:20.621   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:20.621   277  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10170
,09-12 13:57:20.621  6625  7469 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-12 13:57:20.621  6625  7469 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:57:20.621  6625  7469 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:57:20.621  6625  7469 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:57:20.621  6625  7469 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 13:57:20.621  6625  7471 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 13:57:20.621  6625  7471 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:20.621  6625  7471 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:57:20.621  6625  7471 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:57:20.631  6625  7471 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 13:57:20.631  6625  7477 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1403, name: IncomingSocketThread/Receiver)
,09-12 13:57:20.631  6625  7475 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1401, name: OutgoingSocketThread/Receiver)
,09-12 13:57:20.631  6625  7475 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1401, thread name: OutgoingSocketThread/Receiver)
,09-12 13:57:20.631  6625  7476 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1402, name: IncomingSocketThread/Sender)
,09-12 13:57:20.631  6625  7474 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1400, name: OutgoingSocketThread/Sender)
,09-12 13:57:20.631  6625  7475 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-12 13:57:20.631  6625  7477 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1403, thread name: IncomingSocketThread/Receiver)
09-12 13:57:20.631  6625  7477 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 13:57:20.631  6625  7475 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1401, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 13:57:20.631  6625  7477 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1403, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207,
,09-12 13:57:21.101   287   287 E SMD     : DCD OFF,
,09-12 13:57:21.121  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 13:57:21.121  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:57:21.121  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@30cd728e Bundle[{}]
,09-12 13:57:21.121  6625  6774 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:57:21.121  6625  6774 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 13:57:21.121  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:57:21.121  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:57:21.131  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 13:57:21.131  6625  6774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:57:21.141  6625  7478 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-12 13:57:21.141  6625  7478 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:57:21.251  7461  7461 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
09-12 13:57:21.251  7461  7461 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 13:57:21.251  7461  7461 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-12 13:57:21.251  7461  7461 I wpa_supplicant: Trying to associate with  'G700',
,09-12 13:57:21.251  7461  7461 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-12 13:57:21.251  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
09-12 13:57:21.261  1018  7466 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-12 13:57:21.271  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:57:21.271  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:21.381  7461  7461 E wpa_supplicant: Cmd 35605 not handled
,09-12 13:57:21.381  7461  7461 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 13:57:21.381  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 13:57:21.381  7461  7461 I wpa_supplicant: Associated with F4.99.3E
,09-12 13:57:21.381  7461  7461 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:57:21.381  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:57:21.381  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:21.381  7461  7461 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 13:57:21.381  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:21.381  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 13:57:21.381  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-12 13:57:21.381  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:57:21.381  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-12 13:57:21.381  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:57:21.381  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:57:21.381  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:57:21.391  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:21.391  1018  1127 D SecContentProvider2: mCursor = null,
,09-12 13:57:21.391  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:57:21.391  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:21.391  7461  7461 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:57:21.391  7461  7461 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-12 13:57:21.391  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:57:21.391  7461  7461 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-12 13:57:21.391  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 13:57:21.391  7461  7461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:57:21.391  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:57:21.391  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:57:21.391  7461  7461 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 13:57:21.391  7461  7461 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-12 13:57:21.391  7461  7461 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 13:57:21.391  7461  7461 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-12 13:57:21.401  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-12 13:57:21.401  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:57:21.401  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:57:21.401  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:57:21.401  1018  1132 E Tethering: No numeric data
,09-12 13:57:21.401  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:57:21.411  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-12 13:57:21.411  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-12 13:57:21.411  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:21.411  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:57:21.421  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:57:21.421  1018  1132 D Tethering: clearTetheredNotification()
09-12 13:57:21.421  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:21.431  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:21.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:21.431  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:21.431  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:21.431  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:21.431  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:21.431  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-12 13:57:21.431  1176  1176 D HotspotTile: updateTetherState():false, false,
,09-12 13:57:21.431  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:21.431  1018  1124 V NetworkStats: performPollLocked() took 4ms,
09-12 13:57:21.431  1018  1442 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:21.431  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:21.441  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:21.441  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:21.441  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:57:21.441  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:57:21.441  1625  1625 I Hs20UtilService: Starting #19
,09-12 13:57:21.441  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:21.441  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:21.441  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:21.441  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:57:21.451  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:21.451  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:57:21.451   277  1017 D CommandListener: Setting iface cfg
,09-12 13:57:21.451  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:57:21.451  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
09-12 13:57:21.451  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:21.451  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:21.451  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:57:21.451  4492  4492 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:57:21.461  4492  4560 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:57:21.461  2778  2835 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:21.471  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:21.471  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:21.471  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:57:21.471  1018  1127 D SecContentProvider2: mCursor = null
,09-12 13:57:21.481  1018  1127 E WifiNative-wlan0: do suspend false
,09-12 13:57:21.481  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:57:21.481  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:57:21.641  6625  7484 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775,
09-12 13:57:21.641  6625  7484 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:21.641  6625  7484 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:21.641  6625  7484 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:21.641  6625  7484 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 13:57:21.641  6625  7478 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-12 13:57:21.641  6625  7478 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:57:21.641  6625  7478 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:21.641  6625  7478 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:57:21.641  6625  7478 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:57:21.651  6625  7489 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1417, name: OutgoingSocketThread/Receiver)
09-12 13:57:21.651  6625  7489 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1417, thread name: OutgoingSocketThread/Receiver)
09-12 13:57:21.651  6625  7489 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:57:21.651  6625  7489 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1417, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-12 13:57:21.651  6625  7487 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1415, name: IncomingSocketThread/Receiver)
09-12 13:57:21.651  6625  7487 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1415, thread name: IncomingSocketThread/Receiver)
09-12 13:57:21.651  6625  7487 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:57:21.651  6625  7487 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1415, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 13:57:21.651  6625  7488 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1416, name: OutgoingSocketThread/Sender)
,09-12 13:57:21.651  6625  7486 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1414, name: IncomingSocketThread/Sender)
,09-12 13:57:21.711  7490  7490 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-12 13:57:21.721  7490  7490 I dhcpcd  : version 5.5.6 starting,
,09-12 13:57:21.721  7490  7490 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-12 13:57:21.781  7490  7490 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-12 13:57:21.781  7490  7490 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
09-12 13:57:21.781  7490  7490 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 13:57:21.781  7490  7490 I dhcpcd  : bssid match,
09-12 13:57:21.781  7490  7490 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-12 13:57:21.891  7490  7490 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-12 13:57:21.961  7490  7490 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-12 13:57:22.151  6625  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1426),
09-12 13:57:22.151  6625  6774 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 13:57:22.151  6625  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1427)
,09-12 13:57:22.151  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:57:22.151  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f added. We now have 4 listener(s)
,09-12 13:57:22.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-12 13:57:22.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:57:22.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:57:22.151  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 13:57:22.151  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c added. We now have 4 listener(s)
09-12 13:57:22.151  6625  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:57:22.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:57:22.151  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:57:22.161  6625  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:57:22.161  6625  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:57:22.161  6625  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:57:22.161  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:22.161  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:22.171  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:22.171  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:57:22.171  6625  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f removed from the list
09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:22.171  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c removed from the list
09-12 13:57:22.171  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:57:22.171  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:22.171  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5,
09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-12 13:57:22.171  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:22.171  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:57:22.171  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
09-12 13:57:22.171  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:57:22.171  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:22.171  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:57:22.171  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:57:22.181  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:22.191  6625  7518 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:57:22.191  6625  7518 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:22.191  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:57:22.191  6625  7518 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
,09-12 13:57:22.191  6625  7518 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:22.191  6625  7518 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:22.191  6625  7518 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e3aa68b
09-12 13:57:22.191  6625  7518 D BluetoothSocket: channel: 6
09-12 13:57:22.191  6625  7518 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:57:22.191  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:22.201  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:57:22.201  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 13:57:22.201  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 75 41
09-12 13:57:22.201  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:22.201  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:22.201  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:22.201  2778  7336 D BtGatt.GattService: registerClient() - UUID=1f0f06a9-42ee-49f3-ac8d-18461891abae
,09-12 13:57:22.251  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=1f0f06a9-42ee-49f3-ac8d-18461891abae, clientIf=6
,09-12 13:57:22.251  6625  6639 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:22.251  2778  2887 D BtGatt.AdvertiseManager: message : 0
,09-12 13:57:22.261  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0
,09-12 13:57:22.261  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:22.261  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:22.261  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:22.271  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:22.271  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:22.271  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:22.271  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:22.271  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:22.271  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:57:22.271  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:22.281  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:22.281  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:22.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:22.281  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:57:22.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:57:22.281  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:57:22.281  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:22.291  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
09-12 13:57:22.291  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:22.311  1018  1127 E WifiNative-wlan0: do suspend true
,09-12 13:57:22.331  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:57:22.331  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:57:22.341  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-12 13:57:22.341  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:57:22.341  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.351  1018  1129 E ConnectivityService: updateNetworkInfo()
,09-12 13:57:22.351  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-12 13:57:22.351  1018  1129 D ConnectivityService: Adding iface wlan0 to network 503
,09-12 13:57:22.361  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-12 13:57:22.361  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-12 13:57:22.361  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:57:22.361  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 13:57:22.361  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 13:57:22.371  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:22.391  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-12 13:57:22.391  1018  1442 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:22.391  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:57:22.391  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-12 13:57:22.391  1018  1442 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:22.391  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.391  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.391  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:22.391  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:22.391  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-12 13:57:22.391  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-12 13:57:22.391  1625  1625 I Hs20UtilService: Starting #20
,09-12 13:57:22.391  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:57:22.391  1018  1129 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-12 13:57:22.391  1018  1129 D ConnectivityService: LTETest block dns file not exists
,09-12 13:57:22.401  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:22.401  1018  1129 V NetworkStats: updateIfacesLocked()
09-12 13:57:22.401  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.401  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:22.401  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:57:22.401  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:57:22.401  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:22.411  4492  4492 I NearbySettings: MountReceiver.onReceive - Keep current state
09-12 13:57:22.411  1018  1129 V NetworkStats: performPollLocked() took 9ms
09-12 13:57:22.411  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.411  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:57:22.421  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:57:22.421  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 13:57:22.421  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 13:57:22.421  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:22.421  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.421  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:57:22.421  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-12 13:57:22.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:57:22.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-12 13:57:22.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.431  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.441  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:22.441  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.441  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.441  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:22.441  1018  1129 E ConnectivityService: updateNetworkInfo()
09-12 13:57:22.441  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:57:22.441  1018  1129 V NetworkStats: updateIfacesLocked()
09-12 13:57:22.441  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:57:22.441  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.441  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:57:22.441  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:22.441  1018  1129 V NetworkStats: performPollLocked() took 3ms
,09-12 13:57:22.441  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.441  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.441  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-12 13:57:22.451  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:22.451  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.451  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:22.451  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 13:57:22.451  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:22.451  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-12 13:57:22.451  1018  7480 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:57:22.451   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:22.451   277  1013 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-12 13:57:22.451  1018  1129 D ConnectivityService:    accepting network in place of null
,09-12 13:57:22.451  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:57:22.451  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:57:22.451  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1,
09-12 13:57:22.451  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-12 13:57:22.451  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:57:22.451  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:57:22.451  1459  1459 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:57:22.461  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-12 13:57:22.461  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:22.461  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 13:57:22.461  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 13:57:22.461  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:57:22.461  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:57:22.461  1018  1124 V NetworkStats: updateIfacesLocked()
,09-12 13:57:22.461  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:22.461  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.461  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:57:22.471  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:22.471  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.471  1018  1124 V NetworkStats: performPollLocked() took 4ms
,09-12 13:57:22.471  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:57:22.471  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.471  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-12 13:57:22.471  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:22.471  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 13:57:22.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:22.481   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-12 13:57:22.481   277  1013 D Netd    : getNetworkForDns: using netid 503 for uid 10011
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:22.481  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:57:22.481  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:57:22.481  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:22.481  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.481  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:22.481  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:22.481  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:22.481  1625  1625 I Hs20UtilService: Starting #21
09-12 13:57:22.481  1625  1662 I Hs20UtilService: Message received 5007
09-12 13:57:22.491  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:57:22.491  4492  4492 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:57:22.491  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-12 13:57:22.491  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:57:22.491  4492  4492 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-12 13:57:22.491  4492  4492 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:57:22.491  1018  1329 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:57:22.491  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:57:22.501  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:22.501  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:22.501  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:57:22.501  4492  4492 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:57:22.501  1625  1625 I Hs20UtilService: Starting #22
,09-12 13:57:22.501  1625  1662 I Hs20UtilService: Message received 5007
,09-12 13:57:22.501  4492  4492 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:57:22.511  1018  1308 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 13:57:22.511  1018  1329 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-12 13:57:22.511  1018  1329 D SecContentProvider2: mCursor = null
,09-12 13:57:22.511  1018  1954 D SecContentProvider2: uri = 15 selection = getToastGravity,
09-12 13:57:22.511  1018  1954 D SecContentProvider2: mCursor = null
,09-12 13:57:22.521  1018  1442 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-12 13:57:22.521  1018  1442 D SecContentProvider2: mCursor = null
,09-12 13:57:22.521  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-12 13:57:22.521  1018  1031 D SecContentProvider2: mCursor = null
,09-12 13:57:22.521  1018  1454 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-12 13:57:22.521  1018  1454 D SecContentProvider2: mCursor = null
,09-12 13:57:22.521  1018  1488 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-12 13:57:22.521  1018  1488 D SecContentProvider2: mCursor = null
,09-12 13:57:22.551   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-12 13:57:22.551  1018  1954 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018,
,09-12 13:57:22.561  1018  7480 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:57:22.561  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-12 13:57:22.591  1018  2857 D SSRM:n  : SIOP:: AP = 370
,09-12 13:57:22.631  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:22 GMT], X-Android-Received-Millis=[1473681442640], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681442617]}
,09-12 13:57:22.631  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:22.631  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 13:57:22.631  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-12 13:57:22.631  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-12 13:57:22.631  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-12 13:57:22.631  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:22.631  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:57:22.631  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:57:22.631  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:57:22.631  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:57:22.631  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:57:22.631  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,09-12 13:57:22.641  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 13:57:22.641  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:57:22.641  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-12 13:57:22.641  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-12 13:57:22.641  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:57:22.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:57:22.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:57:22.781  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:22.781  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:22.781  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 13:57:22.791  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:57:22.791  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:57:22.791  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:57:22.951  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:22.971  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:22.981  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 13:57:22.981  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:22.981  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:22.981  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:22.981  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:22.991  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:22.991  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:23.001  7530  7530 E Zygote  : MountEmulatedStorage()
09-12 13:57:23.001  7530  7530 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:23.001  7530  7530 E Zygote  : v2
09-12 13:57:23.001  7530  7530 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:23.011  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:23.011  7530  7530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:23.011  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:57:23.011  7530  7530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:23.011  7530  7530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:23.021  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:57:23.021  6625  6625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:57:23.031  6625  6625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:57:23.051  7530  7530 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:23.051  7530  7530 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:23.081  7530  7530 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 13:57:23.081  7530  7530 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-12 13:57:23.081  7530  7530 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 13:57:23.101  7530  7530 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 13:57:23.101  7530  7530 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-12 13:57:23.101  7530  7530 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-12 13:57:23.101  7530  7530 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:23.111  1018  1489 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-12 13:57:23.111  1018  1489 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-12 13:57:23.111  1018  1489 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-12 13:57:23.111  1018  1489 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-12 13:57:23.111  1018  1489 I ActivityManager: Killing 7084:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-12 13:57:23.191  7102  7102 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:23.201  7102  7102 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
09-12 13:57:23.201  7102  7102 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-12 13:57:23.201  7102  7102 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-12 13:57:23.311  7117  7117 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-12 13:57:23.311  7117  7117 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-12 13:57:23.311  7117  7117 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-12 13:57:23.321  7117  7117 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-12 13:57:23.331  1018  1487 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-12 13:57:23.331  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.331  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.331  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:23.331  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 13:57:23.351  1018  1442 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,09-12 13:57:23.351  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:23.351  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:57:23.351  1900  1900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:57:23.351  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-12 13:57:23.351  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:57:23.351  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-12 13:57:23.351  1018  1952 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:57:23.351  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.361  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.361  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:23.361  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:57:23.361  1900  4765 I iu.UploadsManager: num queued entries: 0
,09-12 13:57:23.361  1900  4765 I iu.UploadsManager: num updated entries: 0
09-12 13:57:23.361  1900  4765 I iu.SyncManager: NEXT; no task
,09-12 13:57:23.361  1018  7480 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 13:57:23.361  1018  7480 I qtaguid : Tagging socket 396 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,09-12 13:57:23.371  1900  1900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:57:23.371  1900  1900 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-12 13:57:23.381  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:57:23 GMT+02:00 2016
,09-12 13:57:23.381  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 13:57:23.381  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.381  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.381  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:23.381  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:57:23.381  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:57:23.391  1018  7480 I qtaguid : Untagging socket 396
,09-12 13:57:23.391  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:57:23 GMT], X-Android-Received-Millis=[1473681443401], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681443377]}
09-12 13:57:23.391  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:57:23.391  1018  7480 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 13:57:23.391  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-12 13:57:23.391  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-12 13:57:23.391  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-12 13:57:23.391  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:23.391  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:57:23.391  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 13:57:23.391  2931  2931 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-12 13:57:23.391  1018  1454 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-12 13:57:23.401  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
09-12 13:57:23.401  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:23.401  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:23.401  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-12 13:57:23.401  2931  2931 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-12 13:57:23.411  2931  7551 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-12 13:57:23.411  2931  7551 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-12 13:57:23.421  2931  7551 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
09-12 13:57:23.421  2931  7551 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
09-12 13:57:23.431  2931  7551 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
09-12 13:57:23.431  2931  7551 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-12 13:57:23.441  2931  7551 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-12 13:57:23.441  3509  7557 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-12 13:57:23.441  3509  7557 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-12 13:57:23.441  7150  7150 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-12 13:57:23.451  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 13:57:23.451  3509  7557 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 13:57:23.451  7167  7167 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-12 13:57:23.451  7167  7167 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-12 13:57:23.451  7167  7167 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 13:57:23.451  7167  7167 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-12 13:57:23.451  7167  7167 I SA      : [OR] == isSIMCardReady false ==
,09-12 13:57:23.461  7167  7167 I SA      : [SCU] == networkStateCheck == true
,09-12 13:57:23.461  7167  7167 I SA      : [DM] getCountryCodeFromCSC : PL
09-12 13:57:23.461  7167  7167 I SA      : isChinaCountryCode : false
09-12 13:57:23.461  7167  7167 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-12 13:57:23.461  7167  7167 I SA      : [OR] == networkStateCheck true ==
,09-12 13:57:23.461  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 13:57:23.461  7167  7167 I SA      : [OR] GetMyCountryZoneTask
,09-12 13:57:23.461  7167  7167 I SA      : [OR] onReceive END
,09-12 13:57:23.471  7167  7558 I SA      : [SRS] prepareGetMyCountryZone
,09-12 13:57:23.471  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:23.481  1018  1454 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-12 13:57:23.481  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.481  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.481  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:23.481  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-12 13:57:23.481  3509  7557 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-12 13:57:23.491  1775  1775 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:23.491  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-12 13:57:23.491  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-12 13:57:23.491  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-12 13:57:23.491  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-12 13:57:23.491  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-12 13:57:23.501  3509  7557 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-12 13:57:23.501  1018  1031 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,09-12 13:57:23.501  3509  7557 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-12 13:57:23.501  1018  1031 D SecContentProvider2: mCursor = null
,09-12 13:57:23.501  2671  2686 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-12 13:57:23.501  1775  1775 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-12 13:57:23.501  1775  1775 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-12 13:57:23.511  1775  1775 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-12 13:57:23.511  1775  1775 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:23.511  7167  7558 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-12 13:57:23.511  3509  7557 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-12 13:57:23.511  7167  7558 I SA      : [SSP] query invoked
,09-12 13:57:23.511  1775  1775 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:57:23.511  1775  1775 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-12 13:57:23.521  3509  7557 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-12 13:57:23.521  1018  1031 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-12 13:57:23.521  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.531  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.531  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:23.531  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-12 13:57:23.531  7167  7558 I SA      : [TPMU] GetMccFromDB : null
09-12 13:57:23.531  7167  7558 I SA      : [SCU] getMccFromPreferece mcc = 260
09-12 13:57:23.531  7167  7558 I SA      : [LBE] isSupportCheckDomainRegion : false
09-12 13:57:23.531  7167  7558 I SA      : [TPM] isNoProxy(default) : true
,09-12 13:57:23.531  1018  1308 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-12 13:57:23.531  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.541  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:23.541  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:23.541  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:57:23.541  7167  7558 E File    : fail readDirectory() errno=2
,09-12 13:57:23.571  7044  7562 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-12 13:57:23.571  7044  7562 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 13:57:23.571  7044  7562 I System.out: (HTTPLog)-Static: isShipBuild true
09-12 13:57:23.571  7044  7562 I System.out: (HTTPLog)-Thread-1310-634611497: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-12 13:57:23.571  7044  7562 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:57:23.571  7294  7294 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:57:23.571  7294  7294 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-12 13:57:23.571  7294  7294 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 13:57:23.571   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:23.571   277  1013 D Netd    : getNetworkForDns: using netid 503 for uid 10102
,09-12 13:57:23.581  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:57:23.591  7355  7355 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-12 13:57:23.591  1018  1487 I art     : Explicit concurrent mark sweep GC freed 80957(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 3.051ms total 168.031ms
,09-12 13:57:23.611  7044  7562 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:57:23.661  7044  7562 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:57:23.671  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:23.741  1018  1329 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-12 13:57:23.751  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-12 13:57:23.751  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:23.751  1018  1329 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-12 13:57:23.751  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-12 13:57:23.761  7355  7355 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-12 13:57:23.761  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:23.761  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:23.761  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 13:57:23.761  7355  7355 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-12 13:57:23.761  7355  7355 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-12 13:57:23.761  7355  7355 D InitializeManagerStateMachine: exit::IDLE
09-12 13:57:23.761  7355  7355 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-12 13:57:23.771  7355  7355 D InitializeManagerStateMachine: entry::SUCCESS
09-12 13:57:23.771  7355  7355 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-12 13:57:23.771  7355  7355 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-12 13:57:23.771  7355  7355 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-12 13:57:23.781  7355  7355 D InitializeManagerStateMachine: exit::SUCCESS
09-12 13:57:23.781  7355  7355 D InitializeManagerStateMachine: entry::IDLE
,09-12 13:57:23.791  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8dbe8bb, channel: 6, state: CLOSED
,09-12 13:57:23.801  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23c4609b, channel: 6, state: CLOSED
,09-12 13:57:23.801  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1fa0b433, channel: 6, state: CLOSED
,09-12 13:57:23.801  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fd4c2d9, channel: 6, state: CLOSED
,09-12 13:57:23.801  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2be0d108, channel: 6, state: CLOSED
,09-12 13:57:23.801  6625  6635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35ec8702, channel: -1, state: CLOSED
,09-12 13:57:23.971  7167  7558 I SA      : [RC New] Execute method=[GET] start
,09-12 13:57:24.011  7167  7558 I SA      : [RC New] Security=[true]
,09-12 13:57:24.011  7167  7558 I System.out: Thread-1341(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-12 13:57:24.011  7167  7558 I System.out: Thread-1341(ApacheHTTPLog):isSBSettingEnabled false,
09-12 13:57:24.011  7167  7558 I System.out: Thread-1341(ApacheHTTPLog):isShipBuild true
09-12 13:57:24.011  7167  7558 I System.out: Thread-1341(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-12 13:57:24.011  7167  7558 I System.out: Thread-1341(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-12 13:57:24.011   277  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 13:57:24.011   277  1013 D Netd    : getNetworkForDns: using netid 503 for uid 10036
,09-12 13:57:24.021  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:24.021  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:24.021  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 13:57:24.091   287   287 E SMD     : DCD OFF
,09-12 13:57:24.621  7167  7558 I SA      : [RC New] [v2liruge] api execute + 610
,09-12 13:57:24.621  7167  7558 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-12 13:57:24.621  7167  7558 I System.out: AsyncTask #1 calls detatch()
,09-12 13:57:24.621  7167  7558 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-12 13:57:24.631  7167  7558 I SA      : [OCP] update openData : PL
,09-12 13:57:24.631  7167  7558 I SA      : [TPMU] getNetworkMcc : 260
,09-12 13:57:24.641  7167  7558 I SA      : [SCU] saveMccToPreferece Start
,09-12 13:57:24.641  7167  7558 I SA      : [SCU] RegionMCC : 260
,09-12 13:57:24.641  7167  7558 I SA      : [SSP] query invoked
,09-12 13:57:24.641  7167  7558 I SA      : [TPMU] GetMccFromDB : null
,09-12 13:57:24.641  7167  7558 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-12 13:57:24.651  7167  7558 I SA      : [SCU] saveMccToPreferece End
,09-12 13:57:24.651  7167  7558 I SA      : [RC New] executeRequest [v2liruge] end. 674
09-12 13:57:24.651  7167  7558 I SA      : [RC New] Execute end
,09-12 13:57:24.651  7167  7167 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-12 13:57:24.651  7167  7167 I SA      : [OR] GetMyCountryZoneTask Success
,09-12 13:57:25.301  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 13:57:25.301  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:25.301  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c100381, channel: 6, state: LISTENING
,09-12 13:57:25.301  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c100381, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e3aa68b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@aa8fc26mSocket: android.net.LocalSocket@322b2067 impl:android.net.LocalSocketImpl@36e65e14 fd:FileDescriptor[110]
,09-12 13:57:25.301  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@322b2067 impl:android.net.LocalSocketImpl@36e65e14 fd:FileDescriptor[110]
,09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:57:25.301  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:25.301  6625  7518 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c100381, channel: 6, state: CLOSED
09-12 13:57:25.301  6625  7518 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:25.301  6625  7518 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:25.301  6625  7518 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:57:25.301  6625  6774 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:57:25.301  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:25.301  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:57:25.301  2778  2887 D BtGatt.AdvertiseManager: message : 1
,09-12 13:57:25.301  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-12 13:57:25.301  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-12 13:57:25.301  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-12 13:57:25.311  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-12 13:57:25.311  2778  2837 D BtGatt.GattService: Client app is not null!
,09-12 13:57:25.311  2778  7420 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:25.321  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:25.321  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:57:25.321  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:57:25.321  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:57:25.321  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:57:25.321  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:25.321  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:57:25.321  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:25.331  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:25.331  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:57:25.331  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:57:25.331  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:57:25.331  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:25.331  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:25.331  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:25.331  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:25.331  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:25.331  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:25.331  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f not in the list
09-12 13:57:25.331  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:25.331  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c not in the list
09-12 13:57:25.331  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:25.331  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:25.331  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:25.331  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:25.331  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:25.331  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:57:25.331  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:57:25.331  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:25.331  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,09-12 13:57:25.341  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:25.341  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:25.341  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:25.351  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:57:25.351  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:57:25.351  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:57:25.351  2778  2792 D BtGatt.GattService: registerClient() - UUID=bcceb765-0d18-4c0c-b2aa-ec79d4a71bc5
,09-12 13:57:25.401  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=bcceb765-0d18-4c0c-b2aa-ec79d4a71bc5, clientIf=6
,09-12 13:57:25.401  6625  6633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:25.401  2778  2788 D BtGatt.GattService: start scan with filters
,09-12 13:57:25.401  2778  2888 D BtGatt.ScanManager: handling starting scan
,09-12 13:57:25.411  2778  2888 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c721860
,09-12 13:57:25.411  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:57:25.411  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:57:25.411  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:57:25.411  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:57:25.411  2778  2837 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:57:25.411  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:25.411  2778  2888 D BtGatt.ScanManager: allow scan with filters
,09-12 13:57:25.421  2778  2888 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:57:25.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:57:25.421  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:25.421  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:57:25.421  2778  2888 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 13:57:25.421  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:25.421  2778  2837 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:57:25.431  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:25.431  2778  2888 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:57:25.431  2778  2888 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-12 13:57:25.431  2778  2837 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:57:25.431  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-12 13:57:25.441  2778  2837 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-12 13:57:25.441  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:57:25.441  1018  1151 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-12 13:57:25.461  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 13:57:25.461  1018  1129 V NetworkStats: updateIfacesLocked()
,09-12 13:57:25.461  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:25.461  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:57:25.461  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:57:25.461  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:25.471  1018  1129 V NetworkStats: performPollLocked() took 6ms
09-12 13:57:25.471  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:25.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:25.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:25.471  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:25.471  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-12 13:57:25.471  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-12 13:57:25.481  1176  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-12 13:57:25.751  1018  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:57:25.931  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 13:57:25.931  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:57:25.931  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:57:25.941  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:25.941  2778  2778 D BtGatt.ScanManager: awakened up at time 135695
,09-12 13:57:25.941  2778  2778 D BtGatt.ScanManager: awakened up at time 135698
,09-12 13:57:25.951  7490  7490 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-12 13:57:25.961  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:57:25.961  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=5
,09-12 13:57:25.961  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:25.971  2778  2837 D BtGatt.GattService: current time is 135720207134
,09-12 13:57:25.971  2778  2837 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, -37, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -72, -65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -70, -1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -73, 109, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, -119, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 13:57:25.981  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-12 13:57:25.981  2778  2837 D ScanRecord: parseFromBytes
,09-12 13:57:25.981  2778  2837 D ScanRecord: first manudata for manu ID
,09-12 13:57:25.981  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:57:25.981  2778  2837 D ScanRecord: parseFromBytes
09-12 13:57:25.981  2778  2837 D ScanRecord: first manudata for manu ID
,09-12 13:57:25.981  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 13:57:25.981  2778  2837 D ScanRecord: parseFromBytes
09-12 13:57:25.981  2778  2837 D ScanRecord: first manudata for manu ID
,09-12 13:57:25.981  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 13:57:25.981  2778  2837 D ScanRecord: parseFromBytes
09-12 13:57:25.981  2778  2837 D ScanRecord: first manudata for manu ID
,09-12 13:57:25.981  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92],
09-12 13:57:25.981  2778  2837 D ScanRecord: parseFromBytes
,09-12 13:57:25.981  2778  2837 D ScanRecord: first manudata for manu ID
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-70, mTimestampNanos=122974637707},
09-12 13:57:25.991  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=126174637707}
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-73, mTimestampNanos=117474637707}
09-12 13:57:25.991  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=116074637707}
09-12 13:57:25.991  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:57:25.991  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=111974637707}
09-12 13:57:25.991  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:57:25.991  6625  6639 D ScanRecord: parseFromBytes
09-12 13:57:25.991  6625  6639 D ScanRecord: first manudata for manu ID
09-12 13:57:25.991  6625  6639 D ScanRecord: parseFromBytes
09-12 13:57:25.991  6625  6639 D ScanRecord: first manudata for manu ID
09-12 13:57:25.991  6625  6639 D ScanRecord: parseFromBytes
09-12 13:57:25.991  6625  6639 D ScanRecord: first manudata for manu ID
09-12 13:57:25.991  6625  6639 D ScanRecord: parseFromBytes
09-12 13:57:25.991  6625  6639 D ScanRecord: first manudata for manu ID
09-12 13:57:25.991  6625  6639 D ScanRecord: parseFromBytes
09-12 13:57:25.991  6625  6639 D ScanRecord: first manudata for manu ID
,09-12 13:57:26.041   257  1102 I SurfaceFlinger: id=14 Removed Uoast (8/9),
09-12 13:57:26.041  1018  1952 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 135794
09-12 13:57:26.041   257  1889 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,09-12 13:57:26.041  1018  1952 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0),
09-12 13:57:26.041  1018  1952 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3488)
,09-12 13:57:26.371  1018  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-12 13:57:26.371  1018  1329 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 13:57:26.371  1018  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-12 13:57:26.371  1018  1329 D BatteryService: stay LED for charging
09-12 13:57:26.371  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:57:26.381  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:57:26.381  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:57:26.381  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:57:26.381  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 13:57:26.391  1018  1018 I MotionRecognitionService: Plugged
09-12 13:57:26.391  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:57:26.391  2778  2778 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:57:26.391  2778  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:57:26.401  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:26.411  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:26.411  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 13:57:26.451  1018  1308 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-12 13:57:26.451  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-12 13:57:26.451  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:26.451  1018  1308 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 13:57:26.451  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-12 13:57:26.471  1018  1096 V AlarmManager: waitForAlarm result :4,
,09-12 13:57:26.511  2778  2778 D BtGatt.ScanManager: awakened up at time 136267
,09-12 13:57:26.521  2778  2778 D BtGatt.ScanManager: awakened up at time 136270
09-12 13:57:26.521  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:57:26.521  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
09-12 13:57:26.521  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:26.521  2778  2837 D BtGatt.GattService: current time is 136276229894
09-12 13:57:26.521  2778  2837 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -92, 21, 2, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 13:57:26.521  2778  2837 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 13:57:26.521  2778  2837 D ScanRecord: parseFromBytes
09-12 13:57:26.521  2778  2837 D ScanRecord: first manudata for manu ID
09-12 13:57:26.521  2778  2837 D BtGatt.GattService: result: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-92, mTimestampNanos=109626361301}
09-12 13:57:26.521  2778  2837 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:57:26.521  6625  6633 D ScanRecord: parseFromBytes
09-12 13:57:26.521  6625  6633 D ScanRecord: first manudata for manu ID
,09-12 13:57:27.021  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:27.031  2778  2778 D BtGatt.ScanManager: awakened up at time 136782
09-12 13:57:27.031  2778  2778 D BtGatt.ScanManager: awakened up at time 136783
,09-12 13:57:27.031  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:57:27.031  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:57:27.031  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:27.091   287   287 E SMD     : DCD OFF,
,09-12 13:57:27.321  1018  1050 I PowerManagerService: [PWL] Off : 75s ago
,09-12 13:57:27.321  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-12 13:57:27.321  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-12 13:57:27.321  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2778, ws=null) (elapsedTime=796),
,09-12 13:57:27.541  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:27.541  2778  2778 D BtGatt.ScanManager: awakened up at time 137292
,09-12 13:57:27.541  2778  2778 D BtGatt.ScanManager: awakened up at time 137295,
,09-12 13:57:27.541  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,09-12 13:57:27.551  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:57:27.551  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:27.991  1018  1307 E Watchdog: !@Sync 4
,09-12 13:57:28.051  1018  1096 V AlarmManager: waitForAlarm result :4
,09-12 13:57:28.051  2778  2778 D BtGatt.ScanManager: awakened up at time 137808
,09-12 13:57:28.061  2778  2778 D BtGatt.ScanManager: awakened up at time 137811
,09-12 13:57:28.061  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:57:28.061  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:57:28.061  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:28.121  7530  7530 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected,
,09-12 13:57:28.131  7530  7577 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-12 13:57:28.151  7530  7577 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-12 13:57:28.161  7530  7577 I ReactiveServiceManager: Supported : 1,
09-12 13:57:28.161  1018  1442 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
09-12 13:57:28.161  1018  1442 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 13:57:28.171  1018  1442 D QSEECOMAPI: : Loaded image: APP id = 12
,09-12 13:57:28.181  1018  1442 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-12 13:57:28.181  1018  1442 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
,09-12 13:57:28.181  1018  1442 E terrier : handleString: Failed to handle string(-4)
,09-12 13:57:28.181  1018  1442 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-12 13:57:28.181  7530  7577 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-12 13:57:28.181  7530  7577 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-12 13:57:28.181  7530  7577 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 13:57:28.181  7530  7577 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 13:57:28.181  7530  7577 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-12 13:57:28.181  7530  7577 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:28.441  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:57:28.441  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f not in the list
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:57:28.441  2778  7336 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:57:28.441  2778  2792 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:28.441  2778  2888 D BtGatt.ScanManager: filter size is 1,
09-12 13:57:28.441  2778  2888 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
09-12 13:57:28.441  2778  2837 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 13:57:28.441  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:57:28.441  2778  2888 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:28.441  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c not in the list
09-12 13:57:28.441  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:28.441  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:57:28.441  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:28.441  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:28.441  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:28.441  6625  6774 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-12 13:57:28.441  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:28.441  6625  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-12 13:57:28.441  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:57:28.441  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:57:28.451  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:57:28.451  2778  2837 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 13:57:28.451  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:57:28.451  2778  2888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:57:28.451  2778  2837 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:57:28.451  2778  2837 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:57:28.451  6625  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:57:28.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:57:28.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:57:28.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:57:28.461  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 13:57:28.461  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 75 41
,09-12 13:57:28.471  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:57:28.471  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:57:28.471  6625  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:57:28.471  6625  7579 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:57:28.471  6625  7579 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:57:28.471  6625  7579 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-12 13:57:28.471  6625  7579 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:57:28.471  6625  7579 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:57:28.471  6625  7579 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17d1b55f
09-12 13:57:28.471  6625  7579 D BluetoothSocket: channel: 6
09-12 13:57:28.471  6625  7579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:57:28.471  2778  2792 D BtGatt.GattService: registerClient() - UUID=12ccf897-778d-4b69-80bd-947d179de269
,09-12 13:57:28.521  2778  2837 D BtGatt.GattService: onClientRegistered() - UUID=12ccf897-778d-4b69-80bd-947d179de269, clientIf=6
,09-12 13:57:28.521  6625  6633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-12 13:57:28.521  2778  2887 D BtGatt.AdvertiseManager: message : 0
,09-12 13:57:28.521  2778  2887 D BtGatt.AdvertiseManager: number of adv instance running0
,09-12 13:57:28.521  2778  2887 D BtGatt.AdvertiseManager: size of list is =0
,09-12 13:57:28.521  2778  2887 D BtGatt.AdvertiseManager: starting advertising
,09-12 13:57:28.521  2778  2887 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-12 13:57:28.531  2778  2837 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-12 13:57:28.531  2778  2887 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:57:28.531  2778  2837 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-12 13:57:28.531  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-12 13:57:28.531  2778  2887 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-12 13:57:28.531  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:57:28.531  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:57:28.541  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:57:28.541  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:57:28.541  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:57:28.541  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:57:28.541  6625  6625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 13:57:28.541  6625  6625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:57:28.541  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:57:28.551  6625  6625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:57:28.551  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:57:29.061  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:57:29.061  6625  6625 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:57:29.061  6625  6625 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:57:29.111   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:29.961  7490  7490 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-12 13:57:30.101   287   287 E SMD     : DCD OFF
,09-12 13:57:30.111   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:31.111   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:31.811  1018  1969 V SAMP_SPCM_test: CSC File load.. ,
,09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-12 13:57:31.821  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,09-12 13:57:31.831  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-12 13:57:31.861  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 13:57:31.871  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail,
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 13:57:31.881  1018  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-12 13:57:31.891  1018  1969 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,09-12 13:57:31.891  1018  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:57:31.891  1018  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:31.891  1018  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:31.891  1018  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:31.901  1018  1969 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7584 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:31.901  7584  7584 E Zygote  : MountEmulatedStorage(),
09-12 13:57:31.901  7584  7584 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:31.901  7584  7584 E Zygote  : v2
09-12 13:57:31.901  7584  7584 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:31.901  7584  7584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:31.911  7584  7584 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:31.911  7584  7584 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:31.931  7584  7584 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:31.931  7584  7584 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:31.941  7584  7584 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:57:31.981  1018  1969 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-12 13:57:31.981  1018  1018 I ActivityManager: Killing 7339:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:57:32.051  6625  6774 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30075bac, channel: 6, state: LISTENING
09-12 13:57:32.051  6625  6774 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30075bac, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17d1b55f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@418a075mSocket: android.net.LocalSocket@ede280a impl:android.net.LocalSocketImpl@686487b fd:FileDescriptor[109]
09-12 13:57:32.051  6625  6774 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ede280a impl:android.net.LocalSocketImpl@686487b fd:FileDescriptor[109]
09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:57:32.051  6625  7579 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30075bac, channel: 6, state: CLOSED
09-12 13:57:32.051  6625  6625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:57:32.051  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f not in the list
09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:57:32.051  6625  7579 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:57:32.051  6625  7579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:57:32.051  6625  7579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:57:32.051  6625  6774 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:57:32.051  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:57:32.051  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:57:32.051  2778  2887 D BtGatt.AdvertiseManager: message : 1
,09-12 13:57:32.051  2778  2887 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-12 13:57:32.051  2778  2887 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-12 13:57:32.061  2778  2887 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-12 13:57:32.061  2778  2837 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-12 13:57:32.071  2778  2837 D BtGatt.GattService: Client app is not null!
,09-12 13:57:32.071  2778  2792 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:57:32.071  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:57:32.071  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:57:32.071  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:57:32.071  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:57:32.071  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:57:32.071  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:32.071  6625  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:57:32.071  6625  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:57:32.081  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:32.081  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:57:32.081  6625  6625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:57:32.081  6625  6625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:57:32.081  6625  6625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:57:32.081  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c not in the list
09-12 13:57:32.081  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:32.081  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:32.081  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:32.081  6625  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:57:32.081  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:57:32.081  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:32.081  6625  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b41526f not in the list
09-12 13:57:32.081  6625  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:57:32.081  6625  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c81b7c not in the list
09-12 13:57:32.081  6625  6774 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:57:32.081  6625  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:57:32.081  6625  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:57:32.081  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-12 13:57:32.081  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:57:32.091  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:57:32.091  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:57:32.091  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:57:32.091  6625  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:57:32.101  6625  7599 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1447, name: My test thread name)
,09-12 13:57:32.111   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:32.591  6625  6625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-12 13:57:32.631  1018  2857 D SSRM:n  : SIOP:: AP = 340,
,09-12 13:57:33.101   287   287 E SMD     : DCD OFF,
,09-12 13:57:33.121   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:57:33.771  1018  1488 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:57:33.771  1018  1488 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-12 13:57:33.771  1018  1488 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 13:57:33.771  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0,
09-12 13:57:33.771  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-12 13:57:33.781  7355  7355 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-12 13:57:33.781  7355  7355 D PreloadUpdateManagerStateMachine: exit::IDLE
,09-12 13:57:33.781  7355  7355 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-12 13:57:33.791  7355  7355 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,09-12 13:57:33.791  7355  7355 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-12 13:57:33.791  7355  7355 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-12 13:57:33.791  7355  7355 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-12 13:57:33.791  7355  7355 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-12 13:57:33.961  7490  7490 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-12 13:57:33.961  7490  7490 I dhcpcd  : wlan0: no IPv6 Routers available
,09-12 13:57:34.101  6625  6774 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1447
,09-12 13:57:34.101  6625  6774 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1447, name: My test thread name)
,09-12 13:57:34.101  6625  7600 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1448, name: My test thread name)
,09-12 13:57:34.101  6625  7600 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1448, thread name: My test thread name)
09-12 13:57:34.101  6625  7600 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 13:57:34.101  6625  6774 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:57:34.101  6625  7601 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1452, name: My test thread name)
,09-12 13:57:34.101  6625  7601 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1452, thread name: My test thread name): Test exception.
,09-12 13:57:34.101  6625  7601 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
,09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: Proper state of WIFI is set when switched on
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Proper state of WIFI is set when switched on
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:188)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner,s.ParentRunner$2.evaluate(ParentRunner.java:268)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:34.111  6625  6774 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-12 13:57:34.111   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-12 13:57:34.111  6625  6774 I jxcore-log: Total number of executed tests:  82
09-12 13:57:34.111  6625  6774 I jxcore-log: 
,09-12 13:57:34.111  6625  6774 I jxcore-log: Number of passed tests:  81
09-12 13:57:34.111  6625  6774 I jxcore-log: 
,09-12 13:57:34.111  6625  6774 I jxcore-log: Number of failed tests:  1
09-12 13:57:34.111  6625  6774 I jxcore-log: 
,09-12 13:57:34.121  6625  6774 I jxcore-log: Number of ignored tests:  0
09-12 13:57:34.121  6625  6774 I jxcore-log: 
,09-12 13:57:34.121  6625  6774 I jxcore-log: Total duration:  24015
09-12 13:57:34.121  6625  6774 I jxcore-log: 
,09-12 13:57:34.121  6625  6774 I jxcore-log: Failed to execute UT.
09-12 13:57:34.121  6625  6774 I jxcore-log: 
,09-12 13:57:34.121  6625  6774 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-12 13:57:34.121  6625  6774 I jxcore-log: 
,09-12 13:57:34.121  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.121  6625  6774 I jxcore-log: 
09-12 13:57:34.131  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.131  6625  6774 I jxcore-log: 
09-12 13:57:34.131  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.131  6625  6774 I jxcore-log: 
09-12 13:57:34.131  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:57:34.131  6625  6774 I jxcore-log: 
09-12 13:57:34.131  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:57:34.131  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.141  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.141  6625  6774 I jxcore-log: 
09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
,09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
,09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
,09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
,09-12 13:57:34.151  6625  7599 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-12 13:57:34.151  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.151  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.161  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.161  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.171  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:57:34.171  6625  6774 I jxcore-log: 
,09-12 13:57:34.181  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 13:57:34.181  6625  6774 I jxcore-log: 
,09-12 13:57:34.181  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:57:34.181  6625  6774 I jxcore-log: 
,09-12 13:57:34.181  6625  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:57:34.181  6625  6774 I jxcore-log: 
,09-12 13:57:34.401  7602  7602 D AndroidRuntime: 
09-12 13:57:34.401  7602  7602 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 13:57:34.401  7602  7602 D AndroidRuntime: CheckJNI is OFF,
09-12 13:57:34.401  7602  7602 D AndroidRuntime: readGMSProperty: start
09-12 13:57:34.401  7602  7602 D AndroidRuntime: readGMSProperty: already setted!!,
09-12 13:57:34.401  7602  7602 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:57:34.401  7602  7602 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:57:34.401  7602  7602 D AndroidRuntime: readGMSProperty: end
09-12 13:57:34.401  7602  7602 D AndroidRuntime: addProductProperty: start
,09-12 13:57:34.521  7602  7602 E AffinityControl: AffinityControl: registerfunction enter,
,09-12 13:57:34.551  7602  7602 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-12 13:57:34.561  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-12 13:57:34.561  1018  1030 D PackageManager: START PACKAGE DELETE: observer{867066580}
09-12 13:57:34.561  1018  1030 D PackageManager: pkg{<packageName>}
09-12 13:57:34.561  1018  1030 D PackageManager: user{0}
09-12 13:57:34.561  1018  1030 D PackageManager: caller{2000}
09-12 13:57:34.561  1018  1030 D PackageManager: flags{2}
09-12 13:57:34.561  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-12 13:57:34.561  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-12 13:57:34.561  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 13:57:34.561  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-12 13:57:34.571  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
09-12 13:57:34.571  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-12 13:57:34.571  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-12 13:57:34.571  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-12 13:57:34.571  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-12 13:57:34.571  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-12 13:57:34.571  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
09-12 13:57:34.571  1018  1043 I ActivityManager: Killing 6625:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-12 13:57:34.571  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{1a9d96b4 u0 com.test.thalitest/.MainActivity t163},
,09-12 13:57:34.631  1018  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:57:34.631  1018  1043 D InputDispatcher: Focus left window: 6625
,09-12 13:57:34.631   257   451 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-12 13:57:34.631   257   444 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-12 13:57:34.651  1018  1043 D InputDispatcher: Focused application released,
09-12 13:57:34.651  1018  1048 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-12 13:57:34.651  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:57:34.651  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:57:34.731  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-12 13:57:34.751  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 13:57:34.771  6065  6065 I art     : Explicit concurrent mark sweep GC freed 2683(159KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 719us total 22.654ms
,09-12 13:57:34.791  1869  1869 E SamsungIME: mOCRHelper is null
,09-12 13:57:34.791  1679  2011 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:57:34.801  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:57:34.821  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:57:34 GMT+02:00 2016
,09-12 13:57:34.831  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-12 13:57:34.831  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-12 13:57:34.831  1018  1042 W TextServicesManagerService: no available spell checker services found
,09-12 13:57:34.831  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:57:34.831  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:34.841  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-12 13:57:34.841  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:57:34.841  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
,09-12 13:57:34.841  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:57:34.841  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:57:34.841  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:34.851  1018  1488 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 13:57:34.851  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:57:34.851  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:34.851  1018  1124 V NetworkStats: performPollLocked() took 13ms
09-12 13:57:34.851  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:34.851  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:57:34.851  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:57:34.851  1446  1446 D RegisteredServicesCache: empty dynamic service
,09-12 13:57:34.861  2931  2931 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:57:34.861  1018  1137 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-12 13:57:34.861  1018  1137 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 13:57:34.861  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 13:57:34.861  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.861  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.861  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.861  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:34.871  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:34.871  7614  7614 E Zygote  : MountEmulatedStorage(),
09-12 13:57:34.871  7614  7614 I libpersona: KNOX_SDCARD checking this for 10090
09-12 13:57:34.871  7614  7614 E Zygote  : v2
09-12 13:57:34.871  7614  7614 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:34.881  7614  7614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 13:57:34.881  1018  1137 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7614 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-12 13:57:34.881  7614  7614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:34.881  1446  1446 D RegisteredComponentCache: Collect Tech packages for Knox
09-12 13:57:34.881  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:57:34.891  7614  7614 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:34.891  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-12 13:57:34.891  2931  2931 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:57:34.911  2931  2931 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:57:34.911  7614  7614 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:34.911  7614  7614 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:34.921  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:34.931  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 13:57:34.931  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:34.931  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:57:34.931  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-12 13:57:34.941  1018  1137 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-12 13:57:34.941  1018  1137 D SecContentProvider2: mCursor = null
,09-12 13:57:34.941  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.941  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.941  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.941  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:34.951  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-12 13:57:34.951  1018  1018 I art     : Explicit concurrent mark sweep GC freed 38349(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 4.291ms total 203.750ms
,09-12 13:57:34.961  1018  1058 I art     : WaitForGcToComplete blocked for 135.109ms for cause Explicit
,09-12 13:57:34.961  7629  7629 E Zygote  : MountEmulatedStorage(),
09-12 13:57:34.961  7629  7629 I libpersona: KNOX_SDCARD checking this for 10052
09-12 13:57:34.961  7629  7629 E Zygote  : v2
09-12 13:57:34.961  7629  7629 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:34.961  7629  7629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:34.961  7629  7629 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:34.971  7629  7629 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:57:34.971  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-12 13:57:34.971  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7629 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-12 13:57:34.971  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-12 13:57:34.971  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-12 13:57:34.971  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.971  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.971  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:34.971  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:34.991  7642  7642 E Zygote  : MountEmulatedStorage()
,09-12 13:57:34.991  7642  7642 E Zygote  : v2
09-12 13:57:34.991  7642  7642 I libpersona: KNOX_SDCARD checking this for 10098
09-12 13:57:34.991  7642  7642 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:34.991  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:34.991  7629  7629 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.001  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.001  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7642 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 13:57:35.001  7629  7629 D ActivityThread: Added TimaKeyStore provider
09-12 13:57:35.001  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:35.001  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 13:57:35.011  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.011  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.011  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.011  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.031  7656  7656 E Zygote  : MountEmulatedStorage(),
09-12 13:57:35.031  7614  7614 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-12 13:57:35.031  7656  7656 E Zygote  : v2
,09-12 13:57:35.031  7656  7656 I libpersona: KNOX_SDCARD checking this for 10032
09-12 13:57:35.031  1018  1489 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7656 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:57:35.031  7656  7656 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:35.031  7656  7656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.041  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:35.041  7642  7642 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.041  7656  7656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:35.041  7614  7614 D elm:15121: ELMEngine.ELMEngine( context ).
09-12 13:57:35.041  7656  7656 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 13:57:35.041  7614  7614 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-12 13:57:35.051  1018  1454 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-12 13:57:35.051  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.061  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:35.061  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:35.061  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 13:57:35.071  7614  7614 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 13:57:35.081  7656  7656 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.081  7656  7656 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.081  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 13:57:35.091  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-12 13:57:35.101  7614  7614 D elm:15121: ElmAgentService : onCreate()
,09-12 13:57:35.101  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.101  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.101  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.101  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.101  7614  7674 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-12 13:57:35.101  7614  7674 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-12 13:57:35.101  7614  7674 D elm:15121: MDMBridge.getInstance()
09-12 13:57:35.101  7614  7674 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:57:35.111  7675  7675 E Zygote  : MountEmulatedStorage(),
09-12 13:57:35.111  7675  7675 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:35.111  7675  7675 E Zygote  : v2
09-12 13:57:35.111  7675  7675 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.111  7675  7675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.121  7675  7675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 13:57:35.121  7614  7674 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:57:35.121  7675  7675 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:35.121  2931  7613 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 13:57:35.121  1018  1954 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7675 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:35.121  1018  1954 I ActivityManager: Killing 7385:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
09-12 13:57:35.121  2931  7613 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 13:57:35.131  2931  2931 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 13:57:35.151  7614  7614 D elm:15121: ElmAgentService : onDestroy().
,09-12 13:57:35.151  1018  1489 I ActivityManager: Killing 7405:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-12 13:57:35.151  7675  7675 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.151  7675  7675 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.201  7656  7691 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 13:57:35.201  7656  7691 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 13:57:35.211  1018  1308 I ActivityManager: Killing 6861:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-12 13:57:35.221  7656  7691 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:57:35.221  7656  7691 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:57:35.221  7656  7691 D SPPClientService: ============PushLog. stop!
,09-12 13:57:35.231  1018  1442 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-12 13:57:35.231  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
09-12 13:57:35.231  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 13:57:35.231  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.231  1018  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:35.231  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-12 13:57:35.241  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.251  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-12 13:57:35.251  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,09-12 13:57:35.251  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.251  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.251  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.251  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.251  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.251  1018  1058 I art     : Explicit concurrent mark sweep GC freed 7953(397KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 10.862ms total 297.502ms
,09-12 13:57:35.261  7694  7694 E Zygote  : MountEmulatedStorage(),
09-12 13:57:35.261  7694  7694 E Zygote  : v2
09-12 13:57:35.261  7694  7694 I libpersona: KNOX_SDCARD checking this for 1000,
,09-12 13:57:35.261  7694  7694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.261  7694  7694 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.261  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0,
,09-12 13:57:35.271  7694  7694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.271  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-12 13:57:35.271  1018  1030 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 13:57:35.271  7694  7694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:35.271  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-12 13:57:35.271  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-12 13:57:35.271  1018  1030 I ActivityManager: Killing 6994:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-12 13:57:35.271  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.281  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-12 13:57:35.281  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.281  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.281  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.281  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.301  7708  7708 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.301  7708  7708 E Zygote  : v2
09-12 13:57:35.301  7708  7708 I libpersona: KNOX_SDCARD checking this for 10039
09-12 13:57:35.301  7708  7708 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.301  7708  7708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.301  7708  7708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.301  1018  1489 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7708 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-12 13:57:35.301  7708  7708 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:57:35.301  7694  7694 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:35.311  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter,
,09-12 13:57:35.311  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-12 13:57:35.311  7694  7694 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.311  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 13:57:35.311  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.311  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.311  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.311  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 13:57:35.321  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:57:35.321  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:35.321  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:57:35.331  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.331  7708  7708 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.331  7708  7708 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.341  1018  1058 D PackageManager: delete codoeFile: 
,09-12 13:57:35.351  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-12 13:57:35.351  1018  1489 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 13:57:35.351  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-12 13:57:35.351  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-12 13:57:35.351  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:57:35.351  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.351  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.351  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 13:57:35.361  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:57:35.361  1018  1058 D PackageManager: result of delete: 1{867066580}
,09-12 13:57:35.361  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.361  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:57:35.371  1018  1954 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-12 13:57:35.371  7602  7602 D AndroidRuntime: Shutting down VM
09-12 13:57:35.371  7694  7694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-12 13:57:35.381  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.381  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.381  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.381  1018  1954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.391  7725  7725 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:57:35.391  7708  7708 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
09-12 13:57:35.391  7725  7725 E Zygote  : v2
,09-12 13:57:35.391  7725  7725 I libpersona: KNOX_SDCARD checking this for 10055
09-12 13:57:35.391  7725  7725 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.391  7725  7725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.401  1018  1954 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7725 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-12 13:57:35.401  7725  7725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.401  7725  7725 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:35.411  1018  1030 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-12 13:57:35.411  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.411  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:35.411  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:35.411  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-12 13:57:35.411  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.421  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:57:35.421  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:57:35.431  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-12 13:57:35.431  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.431  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.431  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.431  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.431  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.431  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:57:35.431  7725  7725 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.431  7725  7725 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.441  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:57:35.441  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 13:57:35.441  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicy: uID is 10170
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-12 13:57:35.441  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 13:57:35.441  7741  7741 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.441  7741  7741 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:35.441  7741  7741 E Zygote  : v2
09-12 13:57:35.441  7741  7741 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.441  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.451  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.451  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:35.471  1018  1137 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 13:57:35.471  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicy: uID is 10170
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 13:57:35.471  1018  2857 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-12 13:57:35.471  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 13:57:35.491   309   309 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 19.403ms
,09-12 13:57:35.501  1018  1489 I ActivityManager: Killing 7012:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
09-12 13:57:35.501  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.501  7741  7741 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.501   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.773ms
09-12 13:57:35.501  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-12 13:57:35.511  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-12 13:57:35.521  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-12 13:57:35.521  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-12 13:57:35.521   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.497ms
,09-12 13:57:35.541  1698  1698 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-12 13:57:35.541  1698  1698 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-12 13:57:35.551  7725  7725 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 13:57:35.551  1018  1454 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 13:57:35.551  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.551  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:35.551  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.551  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.561  1900  7760 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-12 13:57:35.571  1900  7760 D AccountUtils: Clearing selected account for com.test.thalitest
,09-12 13:57:35.581  7741  7762 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-12 13:57:35.581  7741  7762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-12 13:57:35.581  1018  1952 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-12 13:57:35.581  7602  7602 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-12 13:57:35.581  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.581  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:57:35.591  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:57:35.591  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-12 13:57:35.591  7725  7725 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 13:57:35.601  7741  7741 D AcmsService: Enter Oncreate
,09-12 13:57:35.601  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:35.601  7741  7741 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:57:35.601  7741  7741 D AcmsService: creating AcmsCore
,09-12 13:57:35.601  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.601  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.601  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.601  1018  1308 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-12 13:57:35.601  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-12 13:57:35.601  7725  7725 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 13:57:35.601  7725  7725 D UserAnalysis: Create SecureDbHelper
,09-12 13:57:35.601  7741  7741 D AcmsCore: AcmsCore.getAcmsCore() - Enter
,09-12 13:57:35.611  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.611  7741  7741 D AcmsCore: AcmsCore
09-12 13:57:35.611  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:35.611  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-12 13:57:35.611  1018  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:57:35.611  7741  7741 D AcmsCore: init
09-12 13:57:35.611  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
09-12 13:57:35.611  7741  7741 D AcmsCore: Looper handler is not null
09-12 13:57:35.611  7741  7741 D AcmsCore: Post to AcmsCoreHandler
09-12 13:57:35.611  7741  7741 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:57:35.611  7741  7741 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-12 13:57:35.611  7741  7741 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-12 13:57:35.611  7725  7725 D IntelligenceServiceApplication: onCreate()
09-12 13:57:35.611  7741  7741 D AcmsService: onStartCommand
09-12 13:57:35.611  7741  7741 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-12 13:57:35.611  7741  7741 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-12 13:57:35.611  7741  7741 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-12 13:57:35.611  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.611  7741  7741 D AcmsService: Incremented Counter Value : onStartCommand
09-12 13:57:35.611  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.611  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.611  7725  7725 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-12 13:57:35.621  1018  1952 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-12 13:57:35.621  7741  7765 D AcmsCertificateMngr: AcmsCertificateMngr
,09-12 13:57:35.631  7741  7765 D AcmsRevocationMngr: AcmsRevocationMngr
,09-12 13:57:35.631  7741  7741 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-12 13:57:35.631  1018  1954 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:35.631  7725  7725 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-12 13:57:35.631  1018  1954 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.631  1018  1954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:35.631  1018  1954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.641  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-12 13:57:35.641  1018  1058 D PackageManager: userId{-1}
09-12 13:57:35.641  1018  1058 D PackageManager: andCode{true}
,09-12 13:57:35.641  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 13:57:35.651  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.651  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 13:57:35.651  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-12 13:57:35.651  7708  7708 D NearbySource: Nearby Source Create!
,09-12 13:57:35.651  7708  7708 D NearbyContext: Nearby Context Create!
,09-12 13:57:35.661  1900  7760 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-12 13:57:35.661  7741  7741 D AcmsService: Inside handle Intent
09-12 13:57:35.671  7741  7741 D AcmsService: App removed - package name: com.test.thalitest
09-12 13:57:35.671  7741  7741 D AcmsCore: Post to AcmsCoreHandler
09-12 13:57:35.671  7741  7741 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:57:35.671  7741  7741 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-12 13:57:35.671  7741  7741 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-12 13:57:35.671  7741  7741 D AcmsService: Decremented Counter Value : handleStartIntent
09-12 13:57:35.671  7741  7741 D AcmsServiceMonitor: Decrementing - Counter value: 2
,09-12 13:57:35.671  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.671  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.671  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.671  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.681  7772  7772 E Zygote  : MountEmulatedStorage()
,09-12 13:57:35.681  7772  7772 E Zygote  : v2
09-12 13:57:35.681  7772  7772 I libpersona: KNOX_SDCARD checking this for 10003
09-12 13:57:35.681  7772  7772 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:35.681  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 13:57:35.681  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:35.691  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7772 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-12 13:57:35.691  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:57:35.691  1018  1487 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-12 13:57:35.691  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.691  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.691  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.691  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.701  1018  1442 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-12 13:57:35.701  1018  1442 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-12 13:57:35.701  1018  1489 D LocationManagerService: getProviders()=[passive, gps]
,09-12 13:57:35.701   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-12 13:57:35.701   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:57:35.701  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.701  1018  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.701  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-12 13:57:35.701  7708  7708 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-12 13:57:35.701  7708  7708 D SLinkSource: Samsung link source created
,09-12 13:57:35.711  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-12 13:57:35.721  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.721  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.721  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.721  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.721  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.721  7772  7772 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.731  7791  7791 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.731  7791  7791 E Zygote  : v2
09-12 13:57:35.731  7791  7791 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:57:35.731  7791  7791 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.731  7791  7791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:35.731  1018  1454 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-12 13:57:35.741  1018  1442 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:35.741  7791  7791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 13:57:35.741  7791  7791 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:57:35.741  1018  1442 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.741  1018  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:57:35.741  1018  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.751  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:57:35.751  1900  1900 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 13:57:35.751  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
09-12 13:57:35.751  1900  1900 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 13:57:35.751  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.751  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.751  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.751  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-12 13:57:35.761  1900  7782 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
09-12 13:57:35.761  1900  7782 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,09-12 13:57:35.761  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-12 13:57:35.771  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.771  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.771  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.771  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.771  1900  7782 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
09-12 13:57:35.771  1900  7782 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,09-12 13:57:35.781  7584  7770 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
09-12 13:57:35.781  7791  7791 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:35.781  7791  7791 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.781  7584  7770 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-12 13:57:35.791  7584  7770 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-12 13:57:35.791  1900  7782 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
09-12 13:57:35.791  1900  7782 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,09-12 13:57:35.791  1900  7782 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false,
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-12 13:57:35.791  7807  7807 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-12 13:57:35.791  7807  7807 E Zygote  : v2
09-12 13:57:35.791  7807  7807 I libpersona: KNOX_SDCARD checking this for 10011
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-12 13:57:35.791  7807  7807 I libpersona: KNOX_SDCARD not a persona
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 13:57:35.791  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,09-12 13:57:35.801  1018  1137 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7807 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-12 13:57:35.801  1018  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-12 13:57:35.801  7807  7807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0,
09-12 13:57:35.801  1900  7782 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,09-12 13:57:35.811  7807  7807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 13:57:35.811  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.,
09-12 13:57:35.811  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false,
,09-12 13:57:35.811  7807  7807 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-12 13:57:35.821  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.821  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.821  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:57:35.821  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:57:35.821  7725  7725 D BluetoothAdapter: cancelDiscovery
,09-12 13:57:35.831  7584  7770 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-12 13:57:35.831  7584  7584 I art     : Explicit concurrent mark sweep GC freed 3341(185KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 771us total 69.588ms
,09-12 13:57:35.841  7584  7584 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 13:57:35.841  7584  7584 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/seatbelt.db'.
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.a(ApkManager.java:36)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:174)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.841  7584  7584 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:57:35.841  7826  7826 E Zygote  : MountEmulatedStorage()
09-12 13:57:35.841  7826  7826 E Zygote  : v2
09-12 13:57:35.841  7826  7826 I libpersona: KNOX_SDCARD checking this for 10014
09-12 13:57:35.841  7826  7826 I libpersona: KNOX_SDCARD not a persona
,09-12 13:57:35.851  1018  1487 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7826 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-12 13:57:35.851  1018  1454 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:57:35.851  7826  7826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 13:57:35.851  7584  7584 D AndroidRuntime: Shutting down VM
09-12 13:57:35.851  7584  7584 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:57:35.851  7584  7584 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7584
09-12 13:57:35.851  7584  7584 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.,samsung.android.sm.common.security.b.a(ApkManager.java:36)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:174)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 13:57:35.851  7584  7584 E AndroidRuntime: 	... 9 more
09-12 13:57:35.851  7584  7770 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
09-12 13:57:35.851  7826  7826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/seatbelt.db'.
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2240)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
09-12 13:57:35.851  7584  7770 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:57:35.851  7584  7770 I Process : Sending signal. PID: 7584 SIG: 9
09-12 13:57:35.851  7826  7826 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:57:35.851  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:57:35.851  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:57:35.851  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:57:35.861  7807  7807 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:57:35.861  7807  7807 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.871  7708  7708 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 13:57:35.871  7826  7826 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:57:35.871  7826  7826 D ActivityThread: Added TimaKeyStore provider
,09-12 13:57:35.881  1900  1900 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-12 13:57:35.881  1900  1900 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 13:57:35.891  2778  2886 D BluetoothAdapterProperties: mDiscovering is false
09-12 13:57:35.891  2778  2886 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-12 13:57:35.891  7725  7725 D BluetoothAdapter: cancelDiscovery = true
,09-12 13:57:35.891  1018  7814 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
09-12 13:57:35.891  7725  7725 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-12 13:57:35.891  1018  7824 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 13:57:35.891  7708  7708 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.891  7708  7708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:57:35.891  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 13:57:35.891  7725  7725 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 13:57:35.901  1018  1442 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: Couldn't open local.db for writing (will try read-only):
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.901  7708  7708 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:57:35.901  7708  7708 W SQLiteOpenHelper: Opened local.db in read-only mode
,09-12 13:57:35.901  7725  7725 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 13:57:35.911  1018  7845 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 13:57:35.911  1018  7845 E DropBoxManagerService: 	... 5 more
,09-12 13:57:35.911  7725  7725 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:35.911  7725  7725 E UserAnalysis: It failed to get the database for dump_log
09-12 13:57:35.911  7725  7725 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 13:57:35.911  1018  1308 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:57:35.911  7725  7725 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:57:35.911  7725  7725 E UserAnalysis: It failed to get the database for dump_log

```
