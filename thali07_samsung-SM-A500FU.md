#### Test 52383621d5a0cb8_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
,D/TimaKeyStoreProvider( 6020): TimaSignature is unavailable
D/ActivityThread( 6020): Added TimaKeyStore provider
D/Mms/DownloadManager( 5844): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5844): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5844): getSubId is called
D/Mms/TelephonyUtils( 5844): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5844): getTelephonyProperty is called
D/Mms/DownloadManager( 5844): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5844): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5844): auto download without roaming -> true
D/Mms/DownloadManager( 5844): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5844): mAutoDownload ------> true
D/BadgeProvider( 6020): onCreate
D/BadgeProvider( 6020): DatabaseHelper
I/DBG_POLICYDM( 5913): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/Mms/MessagingNotification( 5844): checkBadgeCount unreadCount=0 badgeCount=0
I/DBG_POLICYDM( 5913): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TP/SmsProvider( 1483): query,matched:26, calling pid = 5844
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1483): match 26:Elapsed time : 2.246 ms
D/PackageBroadcastService( 1859): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1859): Loading module com.google.android.gms.games from APK com.google.android.play.games
--------- beginning of system
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
D/ChimeraModuleLdr( 1859): Loading module APK com.google.android.play.games
D/Mms/FreeMessageStatusReceiver( 5844): onReceive, action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6042): MountEmulatedStorage()
E/Zygote  ( 6042): v2
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6042 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/libpersona( 6042): KNOX_SDCARD checking this for 10047
I/libpersona( 6042): KNOX_SDCARD not a persona
I/SELinux ( 6042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6042): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1016): Killing 3957:com.google.android.talk/u0a104 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1483): query,matched:6, calling pid = 5844
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1483): match 6:Elapsed time : 3.661 ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6042): TimaSignature is unavailable
D/ActivityThread( 6042): Added TimaKeyStore provider
E/Zygote  ( 6057): MountEmulatedStorage()
I/libpersona( 6057): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6057): v2
I/libpersona( 6057): KNOX_SDCARD not a persona
I/SELinux ( 6057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6057 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 6057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiverService( 5844): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5844): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1016): Killing 5538:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/ResourcesManager( 6042): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6042): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6042): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6057): TimaSignature is unavailable
D/ActivityThread( 6057): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 5553:com.sec.knox.bridge/1000 (adj 15): empty #31
I/PowerManagerService( 1016): [PWL] Off : 5s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1859, ws=null) (elapsedTime=47758)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=614)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1859, ws=null) (elapsedTime=101)
W/ResourcesManager( 6057): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_3957/cgroup.procs: No such file or directory
I/OMACP   ( 6057): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5538/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5553/cgroup.procs: No such file or directory
D/Mms/Omacp( 5844): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/MyFiles ( 6042): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1016): Killing 5569:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/DBG_POLICYDM( 5913): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/TactileAssist( 1016): List of disabled apps :
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6079): MountEmulatedStorage()
E/Zygote  ( 6079): v2
I/libpersona( 6079): KNOX_SDCARD checking this for 10053
I/libpersona( 6079): KNOX_SDCARD not a persona
I/SELinux ( 6079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/AndroidRuntime( 6069): 
D/AndroidRuntime( 6069): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6079 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6069): CheckJNI is OFF
D/AndroidRuntime( 6069): readGMSProperty: start
D/AndroidRuntime( 6069): readGMSProperty: already setted!!
D/AndroidRuntime( 6069): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6069): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6069): readGMSProperty: end
D/AndroidRuntime( 6069): addProductProperty: start
I/SL_DEBUG( 5951): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5951): isLoggable:: SL_DEBUG_EXIST = false
I/SELinux ( 6079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6079): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6079): TimaSignature is unavailable
D/ActivityThread( 6079): Added TimaKeyStore provider
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/OMACP   ( 6057): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1859): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5569/cgroup.procs: No such file or directory
I/ConfigFetchService( 1859): launchTask
W/ResourcesManager( 6079): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1859): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1859): Module APK com.google.android.play.games already loaded
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
V/ConfigFetchTask( 1859): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xb6lThwGRP33Z_elVkOsy9F384cOcJftXKWOEa8DkjK9ZzmtoDh0eVr5SSQgIeJF7T7DqAYpscHo4fLYerJ61l29u4tU--G73ehaRtCvAQuoFbhuOl2Q3Mv2dwowLpTtr9y3nudtN4SVW35T1hWcaHGDKVp02J1QtgyRMrqBmI8YIu5hXWU5plm3lbhqvKhpCmml0UigYKG0a6uZX9xof6N8qy7Fxl2ZOmPpJlXCxPxEvZ1trlL9pP6VxUvy5h5Wqh4I3Hb__TBW_0JtrR9F2dprZHJRDhPRi6iH8VPOokhDp-XQg
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 1859): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
I/PeopleContactsSync( 1859): CP2 sync disabled
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1859): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1859): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1859): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1859): No vision deps
D/Compatibility( 6079): onReceive() it will make start service
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/AffinityControl( 6069): AffinityControl: registerfunction enter
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6079): onHandleIntent()
E/Zygote  ( 6109): MountEmulatedStorage()
E/Zygote  ( 6109): v2
I/libpersona( 6109): KNOX_SDCARD checking this for 1000
I/libpersona( 6109): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Compatibility( 6079): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/AndroidRuntime( 6069): Calling main entry com.android.commands.am.Am
D/Compatibility( 6079): found: 2
D/Compatibility( 6079): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6079): skipping ResolveInfo{23f80cf1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6079): considering ResolveInfo{17f520d6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6079): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6079): enabling receiver ResolveInfo{1ee45f57 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/Compatibility( 6079): enabling receiver ResolveInfo{10934a44 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5913): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/Compatibility( 6079): enabling receiver ResolveInfo{23ef872d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6079): enabling receiver ResolveInfo{1fa7462 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6079): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6109): TimaSignature is unavailable
D/ActivityThread( 6109): Added TimaKeyStore provider
W/ActivityManager( 1016): mDVFSHelper.acquire()
I/DBG_POLICYDM( 5913): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/System.out( 1859): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1859): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1859): (HTTPLog)-Static: isShipBuild true
I/System.out( 1859): (HTTPLog)-Thread-269-402827951: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1859): (HTTPLog)-Static: isSBSettingEnabled false
E/Zygote  ( 6130): MountEmulatedStorage()
I/libpersona( 6130): KNOX_SDCARD checking this for 10175
E/Zygote  ( 6130): v2
I/libpersona( 6130): KNOX_SDCARD not a persona
I/SELinux ( 6130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6130): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6130 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
D/TimaKeyStoreProvider( 6130): TimaSignature is unavailable
D/ActivityThread( 6130): Added TimaKeyStore provider
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 2977
D/AndroidRuntime( 6069): Shutting down VM
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/System.out( 1859): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/PersonaManager( 1016): isKioskContainerExistOnDevice
I/qtaguid ( 1859): Tagging socket 84 with tag 40b00000000{1035,0} for uid -1, pid: 1859, getuid(): 10012
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (-2/9)
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
W/ContextImpl( 6109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
V/ActivityThread( 2977): updateVisibility : ActivityRecord{3c3e0add token=android.os.BinderProxy@1783a02a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/GAv4    ( 5880): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5880):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5880):   adb logcat -s GAv4
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6151): MountEmulatedStorage()
E/Zygote  ( 6151): v2
I/libpersona( 6151): KNOX_SDCARD checking this for 1000
I/libpersona( 6151): KNOX_SDCARD not a persona
I/SELinux ( 6151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/qtaguid ( 1859): Tagging socket 108 with tag 40b00000000{1035,0} for uid -1, pid: 1859, getuid(): 10012
E/SELinux ( 6151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAv4    ( 5880): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager( 1016): Killing 5629:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/TimaKeyStoreProvider( 6151): TimaSignature is unavailable
D/ActivityThread( 6151): Added TimaKeyStore provider
W/GAv4    ( 5880): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5951): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
I/WebViewFactory( 6130): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
W/GAv4    ( 5880): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/art     ( 6069): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,W/ResourcesManager( 6151): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/LibraryLoader( 6130): Time to load native libraries: 3 ms (timestamps 4661-4664)
I/LibraryLoader( 6130): Expected native library version number "",actual native library version number ""
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_5629/cgroup.procs: No such file or directory
W/BaseAppContext( 1859): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5951): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/qtaguid ( 1859): Untagging socket 84
W/AnalyticsTrackerProxyImpl( 5880): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6172): MountEmulatedStorage()
E/Zygote  ( 6172): v2
I/libpersona( 6172): KNOX_SDCARD checking this for 1000
I/libpersona( 6172): KNOX_SDCARD not a persona
I/SELinux ( 6172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6172 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6172): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5473:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/ConfigFetchService( 1859): fetch service done; releasing wakelock
I/ConfigFetchService( 1859): stopping self
I/art     (  305): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 26.693ms
D/TimaKeyStoreProvider( 6172): TimaSignature is unavailable
D/ActivityThread( 6172): Added TimaKeyStore provider
V/WebViewChromiumFactoryProvider( 6130): Binding Chromium to main looper Looper (main, tid 1) {23ef872d}
I/LibraryLoader( 6130): Expected native library version number "",actual native library version number ""
I/chromium( 6130): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourcesManager( 6172): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 824us total 22.303ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 18.151ms
I/BrowserStartupController( 6130): Initializing chromium process, singleProcess=true
W/art     ( 6130): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6130): ApplicationContext is null in ApplicationStatus
E/Zygote  ( 6192): MountEmulatedStorage()
E/Zygote  ( 6192): v2
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6192 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4977:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/libpersona( 6192): KNOX_SDCARD checking this for 10041
I/libpersona( 6192): KNOX_SDCARD not a persona
I/SELinux ( 6192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6192): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/chromium( 6130): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6130): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6130): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6130): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6130): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6130): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6130): Local Branch: 
I/Adreno-EGL( 6130): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6130): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6130):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/TimaKeyStoreProvider( 6192): TimaSignature is unavailable
D/ActivityThread( 6192): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5473/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4977/cgroup.procs: No such file or directory
W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{10ee983e u0 com.test.thalitest/.MainActivity t229}
I/SA      ( 6192): [SSP] onCreated
I/SA      ( 6192): [TPM] There is no property file
I/SA      ( 6192): [SCU] isHaveSA() - false
I/SA      ( 6192): [TPM] getModelProperty : null
I/SA      ( 6192): [TPM] getCSCProperty : null
I/SA      ( 6192): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6192): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6192): [DM] TFT FEATURE: false
I/SA      ( 6192): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6192): [DM] init START
I/SA      ( 6192): [DM] This device is not a Vodafone
I/ActivityManager( 1016): Killing 4847:com.android.calendar/u0a135 (adj 15): empty #31
W/ResourceType( 6192): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6192): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6192): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6192): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6192): [SCU] isHaveSA() - false
I/SA      ( 6192): support phone number id : false
I/SA      ( 6192): [DM] Supports Ref Jpn : true
I/SA      ( 6192): [DM] init END
I/SA      ( 6192): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6192): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5064:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5880): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6233): MountEmulatedStorage()
E/Zygote  ( 6233): v2
I/libpersona( 6233): KNOX_SDCARD checking this for 10120
I/libpersona( 6233): KNOX_SDCARD not a persona
I/SELinux ( 6233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6233): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6233 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5690:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6233): TimaSignature is unavailable
D/ActivityThread( 6233): Added TimaKeyStore provider
E/SMD     (  287): DCD OFF
W/ResourcesManager( 6233): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5880): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5880): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_4847/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5064/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5690/cgroup.procs: No such file or directory
W/art     ( 6130): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 1016): Explicit concurrent mark sweep GC freed 220865(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.926ms total 185.584ms
W/AwContents( 6130): onDetachedFromWindow called when already detached. Ignoring
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PhoneWindow( 6130): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6130): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6130): CordovaWebView is running on device made by: samsung
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/art     ( 6130): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6130): Attempt to remove local handle scope entry from IRT, ignoring
V/JNIHelp ( 5880): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/OpenGLRenderer( 6130): Render dirty regions requested: true
W/ActivityThread( 5880): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5880): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17dcd871: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5880): Installed default security provider GmsCore_OpenSSL
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
W/chromium( 6130): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6130): updateVisibility : ActivityRecord{118655e token=android.os.BinderProxy@38873be0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/PhoneWindow( 6130): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6130): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/InputDispatcher( 1016): Focus entered window: 6130
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6130): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6130): Initialized EGL, version 1.4
D/OpenGLRenderer( 6130): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6130): Enabling debug mode 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PanelView( 1172): There is/are notification(s) 
W/IInputConnectionWrapper( 6130): showStatusIcon on inactive InputConnection
I/Timeline( 6130): Timeline: Activity_idle id: android.os.BinderProxy@38873be0 time:85612
I/ActivityManager( 1016): Displayed Component not be shown by security: +1s135ms (total +1s229ms)
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{10ee983e u0 com.test.thalitest/.MainActivity t229} time:85613
W/ActivityManager( 1016): mDVFSHelper.release()
I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
I/SamsungIME( 1794): getCurrentCandidateView
D/ChimeraCfgMgr( 1859): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1859): Module APK com.google.android.play.games already loaded
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/Mms/MmsApp( 5844):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5844): [start]    fillCache consume time = 1957.821509
D/Mms/ComposeMessageFragment( 5844): fillCache, easy = false
E/Zygote  ( 6277): MountEmulatedStorage()
E/Zygote  ( 6277): v2
I/libpersona( 6277): KNOX_SDCARD checking this for 10057
I/libpersona( 6277): KNOX_SDCARD not a persona
I/SELinux ( 6277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6277): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6277 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5043:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/TimaKeyStoreProvider( 6277): TimaSignature is unavailable
D/ActivityThread( 6277): Added TimaKeyStore provider
D/SamsungIME( 1794): Dismiss ExpandCandiate
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_5043/cgroup.procs: No such file or directory
D/AbsListView( 5844): Get MotionRecognitionManager
D/MotionRecognitionService( 1016):  ssp status : false
I/SamsungIME( 1794): getDebugLevel  : 0x4f4c
D/Mms/ComposeMessageFragment( 5844): [end]    fillCache consume time = 125.86349
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/BindingManager( 6130): Cannot call determinedVisibility() - never saw a connection for the pid: 6130
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6298): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6298 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 6298): v2
I/libpersona( 6298): KNOX_SDCARD checking this for 10010
I/libpersona( 6298): KNOX_SDCARD not a persona,
,I/SELinux ( 6298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,D/Mms/BubbleViewCache( 5844): fillCache bubble = 1
,I/SELinux ( 6298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6298): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1794): getDebugLevel  : 0x4f4c
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/TimaKeyStoreProvider( 6298): TimaSignature is unavailable
,D/ActivityThread( 6298): Added TimaKeyStore provider
,I/SamsungIME( 1794): KeybaordView init() : load resources
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4176, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
I/SamsungIME( 1794): getCurrentKeyboard
I/SamsungIME( 1794): getTextKeyboard
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SamsungIME( 1794): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5712:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,D/JsMessageQueue( 6130): Set native->JS mode to OnlineEventsBridgeMode
,D/LocationManagerService( 1016): getProviders()=[passive]
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5712/cgroup.procs: No such file or directory
,D/jxcore_app_log( 6130): JniHelper::setJavaVM(0xb84e0450), pthread_self() = -1197233240
,D/JX-Cordova( 6130): jxcore cordova android initializing
,I/UpdateIcingCorporaServi( 6277): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AcmsKeyStoreHelper( 5929):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5929): Key Store exist
I/AcmsKeyStoreHelper( 5929): Hence loading the keystore file
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsKeyStoreHelper( 5929):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5929): getKeyStoreForApplication success 
D/AcmsCore( 5929): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5929): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5929): Decrementing - Counter value: 1
D/AcmsCore( 5929): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5929): This is NOT a valid MirrorLink app
D/AcmsCore( 5929): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5929): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/AcmsServiceMonitor( 5929): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5929): Counter value is 0: Stopping ACMS service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsServiceMonitor( 5929): getSvcCounter - Counter value: 0
D/AcmsService( 5929): Enter onDestroy
I/AcmsService( 5929): cleanUp(): inside service clean up
D/AcmsCore( 5929): AcmsCore: inside DeInit
D/AcmsCore( 5929): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5929): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5929): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5929): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5929): AppEntryInterface: Inside CleanUp
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AcmsServiceMonitor( 5929): getSvcCounter - Counter value: 0
,D/AcmsService( 5929): killing acms process
I/Process ( 5929): Sending signal. PID: 5929 SIG: 9
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 6277): UpdateCorporaTask done [took 225 ms] updated apps [took 225 ms] 
,I/ActivityManager( 1016): Killing 5284:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/ActivityManager( 1016): Process ACMS.Process (pid 5929)(adj 0) has died(43,1059)
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5284/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6321): MountEmulatedStorage()
,E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD checking this for 10012
I/libpersona( 6321): KNOX_SDCARD not a persona
,I/SELinux ( 6321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6321 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/DBG_POLICYDM( 5913): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5913): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5913): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/ResourcesManager( 6321): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6321): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6321): VM with version 2.1.0 has multidex support
I/MultiDex( 6321): install
I/MultiDex( 6321): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6321): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6321): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6321): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b3edb04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6321): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/GCM     ( 1704): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1859): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4463): callingUid 10012, callindPid: 4463
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1663): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1859): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1859): Indexing 13A41D57DAFE2A1AC75C4231EB152071BBE04BC1 from com.google.android.googlequicksearchbox
,D/Icing   ( 1859): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1859): Indexing done 13A41D57DAFE2A1AC75C4231EB152071BBE04BC1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 6130): Initializing JXcore engine
W/jxcore-log( 6130): JXcore engine is ready
,W/jxcore-log( 6130): Starting JXcore engine
,E/audit   ( 1893): type=1400 msg=audit(1449056454.616:205): avc:  denied  { ioctl } for  pid=6130 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1893):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1893): type=1300 msg=audit(1449056454.616:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beeaad58 items=0 ppid=305 ppcomm=main pid=6130 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1893): type=1320 msg=audit(1449056454.616:205): 
,W/jxcore-log( 6130): Platform android
W/jxcore-log( 6130): 
W/jxcore-log( 6130): Process ARCH arm
W/jxcore-log( 6130): 
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6130): JXcore Cordova bridge is ready!
I/jxcore-log( 6130): 
,W/jxcore-log( 6130): JXcore engine is started
,I/chromium( 6130): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/jxcore  ( 6130): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 6130): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 6130): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1016): Focused application set to: xxxx
,I/ActivityManager( 1016): Killing 5185:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 18166(1011KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.108ms total 43.237ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focus left window: 6130
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,E/ViewRootImpl( 6130): sendUserActionEvent() mView == null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/SSRM:n  ( 1016): SIOP:: AP = 390
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 5
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_5185/cgroup.procs: No such file or directory
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
I/SurfaceFlinger(  256): id=15 createSurf (720x1280),1 flag=404, YUIInstallC
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 2977
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2977): log_dcs ThreadedRenderer::initialize entered! 
V/ActivityThread( 2977): updateVisibility : ActivityRecord{3c3e0add token=android.os.BinderProxy@1783a02a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6130): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1794): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PanelView( 1172): There is/are notification(s) 
,I/Timeline( 2977): Timeline: Activity_idle id: android.os.BinderProxy@1783a02a time:88858
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1016): mDVFSHelper.release()
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{107e15af u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t228} time:88883
,I/ConfigService( 1704): onDestroy
,V/AlarmManager( 1016): waitForAlarm result :4
,I/ActivityManager( 1016): Killing 5104:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6346): MountEmulatedStorage(),
E/Zygote  ( 6346): v2
,I/libpersona( 6346): KNOX_SDCARD checking this for 10075
I/libpersona( 6346): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6346 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6346): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6346): TimaSignature is unavailable
D/ActivityThread( 6346): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_5104/cgroup.procs: No such file or directory
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6346): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6346): Created application version: 3.6.9 (30609)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6346): Starting books sync for 61035162, extras: ade
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6346): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6346): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6346): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6346): Soft error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6346): Sync error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6346): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64556, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1016): Killing 5425:com.google.android.gm/u0a101 (adj 15): empty #31
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5425/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 5204:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=228_task.xml
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5204/cgroup.procs: No such file or directory
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1859, ws=null) (elapsedTime=57762)
,E/SMD     (  287): DCD OFF
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 4193:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_4193/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6346): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3772e173 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/SSRM:n  ( 1016): SIOP:: AP = 340
,E/SMD     (  287): DCD OFF,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5585): [924] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 32200(1755KB) AllocSpace objects, 13(228KB) LOS objects, 33% free, 27MB/40MB, paused 2.486ms total 154.342ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [924] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for charging,
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1016): SIOP:: AP = 320
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
D/SViewCoverWidget( 1172): cityId=
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5585): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5585): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/FactoryTest( 5669): Not factory mode,
W/ContextImpl( 5669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
D/FactoryTest( 5669): Not factory mode. isFactoryMode() returend false
,W/ContextImpl( 5669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
D/MTPRx   ( 5669): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5669): still no open session command from host, so toast
I/Timeline( 5669): Timeline: Activity_launch_request id:com.android.settings time:117685,
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): mDVFSHelper.acquire(),
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm,
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 2977
,E/MTPRx   ( 5669): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5669): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5669): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5669): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5669): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5669): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5669): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 2977
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@10fd851b attribute=null, token = android.os.BinderProxy@a98896f
,D/SettingsReceiverActivity( 5669): dev.kiessupport is : TRUE
,D/PhoneWindow( 5669): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5669): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 5
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 2977): Timeline: Activity_idle id: android.os.BinderProxy@1783a02a time:117947
,V/ActivityThread( 2977): updateVisibility : ActivityRecord{3c3e0add token=android.os.BinderProxy@1783a02a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,V/AlarmManager( 1016): waitForAlarm result :4,
,W/ActivityManager( 1016): mDVFSHelper.release(),
,E/SMD     (  287): DCD OFF,
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=228_task.xml
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5585): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5585): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5585): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6346): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
D/SViewCoverWidget( 1172): cityId=
,I/BooksConfig( 6346): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6346): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6346): Soft error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6346): Sync error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6346): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153328, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 5
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5585): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5585): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5585): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5585): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5585): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 6
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1704): Vacuum at: now=1449056572404 tag=VacuumService
,I/GoogleURLConnFactory( 1704): Using platform SSLCertificateSocketFactory
,W/Uploader( 1704): No account for auth token provided
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1704): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1704): (HTTPLog)-Static: isShipBuild true
I/System.out( 1704): (HTTPLog)-Thread-205-896627555: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1704): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,I/qtaguid ( 1704): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704):  no longer exists, so no auth token.
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 44326(2MB) AllocSpace objects, 44(724KB) LOS objects, 33% free, 27MB/40MB, paused 2.478ms total 163.473ms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1704): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1704): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Uploader( 1704): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1704): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 55954(3MB) AllocSpace objects, 48(2MB) LOS objects, 39% free, 10MB/18MB, paused 1.330ms total 68.458ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1704): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1704): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10012
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 8
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 1016): waitForAlarm result :4
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6346): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6346): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6346): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6346): Soft error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6346): Sync error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6346): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277824, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :4
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
,I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 10
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 11
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5585): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5585): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5585): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5585): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5585): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5585): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5585): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/System  ( 5585): Ignoring header User-Agent because its value was null.
,I/System.out( 5585): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5585): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5585): (HTTPLog)-Static: isShipBuild true
I/System.out( 5585): (HTTPLog)-Thread-948-85003572: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5585): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5585): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 12
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 13
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 14
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1016): stay LED for charging
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 15
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1016): [PWL] Off : 390s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 16
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=513057 batch.start=526652
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6346): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6346): GmsCore Version = 7.8.99 (2134222-436)
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6346): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6346): Soft error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6346): Sync error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6346): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 526652, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ResourcesManager( 2442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,E/Watchdog( 1016): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,E/Watchdog( 1016): !@Sync 18,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/Atfwd_Daemon(  314): Stop the daemon....,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 19,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 20,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 21
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 22,
,I/PowerManagerService( 1016): [PWL] Off : 600s ago,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 23,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 24,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 680s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 25
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 26
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 27,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 765s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 28
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 29,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 30,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
D/SViewCoverWidget( 1172): cityId=
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1859): Aggregate from 1449054950767 (log), 1449054950767 (data)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,I/GoogleURLConnFactory( 1704): Using platform SSLCertificateSocketFactory
D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1859): Message from null null,
E/GCM     ( 1859): Dropping message from null
,D/GCM     ( 1704): Message class com.google.f.a.a.i
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId -1 pkgname com.android.systemui
I/ValidateNoPeople( 1016): skipping global notification
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1172
I/PowerManagerService( 1016): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1016): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1016): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Display
V/KeyguardServiceDelegate( 1016): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@70c62fd)
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardViewMediator( 1172): onScreenTurnedOn, seq = 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardViewMediator( 1172): notifyScreenOnLocked
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController( 1016): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1016): sensor enabled
D/KeyguardViewMediator( 1172): handleNotifyScreenOn
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
D/StatusBarKeyguardViewManager( 1172): onScreenTurnedOn()
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1016): !@autosuspend_wakeup_count_disable
I/libsuspend( 1016): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1016): !@display_state: OFF -> ON
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb8f54690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
,D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb8c2ce38, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ActivityManager( 1016): Display changed displayId=0
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/KeyguardServiceDelegate( 1016): **** SHOWN CALLED ****
,D/DisplayPowerController( 1016): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController( 1016): Unblocked screen on after 40 ms
D/DisplayPowerState( 1016): !@ ColorFade exit
,D/StatusBarKeyguardViewManager( 1172): callback.onShown()
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/SurfaceFlinger(  256): id=12 Removed DolorFade (8/8)
,I/SurfaceFlinger(  256): id=12 Removed DolorFade (-2/8)
,E/libEGL  ( 1016): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1016): Excessive delay in ColorFade : dismiss: 16ms
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 5 +
D/lights  ( 1016): lcd : 5 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : true
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,D/BatteryMeterView( 1172): onDraw batteryColor : -1
,D/SamsungIME( 1794): showDlgMsgBox : false true true
,D/SensorService( 1016): [SO] currT = 931431637000, prevT = 78191228000, diff = 853240409000, [0.172 0.096 10.151]
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/NfcService( 1459): call the applyRouting
I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84cf7c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202915192),
,E/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1016): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
I/PalmMotion( 1016): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/PalmMotion( 1016): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/PalmMotion( 1016): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 5
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1016) 
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
E/lights  ( 1016): write_led_info failed to open -1
D/BatteryService( 1016): turn off LED
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/lights  ( 1016): write_led_info failed to open -1
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
E/lights  ( 1016): write_led_info failed to open -1
E/SmartFaceService( 1016): fail to set sysfs 1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): ,	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	,... 10 more
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1663): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 140ms
I/DBG_DM  ( 2977): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/PowerManagerService( 1016): Excessive delay in !@display_state: ON: 141ms
D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/SensorService( 1016): [SO] currT = 931501089000, prevT = 78191228000, diff = 853309861000, [0.172 0.057 10.113]
D/SensorService( 1016): [SO] 0.172 0.057 10.113
D/SensorService( 1016): [SO] [100 -> 255]
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : -1
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202915192) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84cf7c8
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/PhoneStatusBar( 1172): Icon Only
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
,D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on,
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
E/WifiNative-wlan0( 1016): do suspend false
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1016): Bridge Server is not available
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
I/wpa_supplicant( 2048): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2048): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2048): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2048): Scan requested (ret=0) - scan timeout 30 seconds
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0,
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0,
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
I/Timeline( 2977): Timeline: Activity_idle id: android.os.BinderProxy@1783a02a time:931575
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,E/SMD     (  287): DCD OFF,
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1016): Excessive delay in MISC setInteractive(true) while turning screen on: 164ms
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/PowerManagerService( 1016): Excessive delay in nativeSetInteractive(true): 166ms
,D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 310ms
D/lights  ( 1016): button : 1 +
,D/lights  ( 1016): button : 1 -,
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1016): waitForAlarm result :8,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH,
D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,I/NfcService( 1459): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
D/NfcService( 1459): call the applyRouting
D/accuweather( 1576): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1576): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1576): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1576): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1576): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1576): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1576): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1576): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/accuweather( 1576): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1576): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1576): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 55
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0,
D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,I/SamsungIME( 1794): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1016): button : 0 +
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/lights  ( 1016): button : 0 -
D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/daemonapp( 1286): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1286): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1286): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1286): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1286): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1286): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1449077940000
,D/daemonapp( 1286): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1449057300171
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1286): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1286): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1286): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1286): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1286): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 2048): nl80211: Received scan results (4 BSSes),
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,E/SMD     (  287): DCD OFF,
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/SensorService( 1016): [SO] 0.172 0.057 10.113
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4280, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2632): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 31
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/SensorService( 1016): [SO] 0.172 0.077 10.094
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1172 (0x0)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4281, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10,
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1016): lcd : 1 +
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 1 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): Nap time (uid 1000)...
D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1016): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
,I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 1016): WindowOrientationListener disabled
,D/SensorService( 1016): [SO] activate (ident=0xb8c2ce38, enabled=0)
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1016): handleSandman : startDream(true)
,E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1016): Sleeping (uid 1000)...
D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1016): unregisterListener ::   
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createSurface: 20ms
,D/KeyguardViewMediator( 1172): timeout : 5000,
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityThread( 2977): updateVisibility : ActivityRecord{3c3e0add token=android.os.BinderProxy@1783a02a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1172): handleNotifyScreenOff
D/VolumePanel( 1172): onScreenTurnedOff()
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOff
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,D/DisplayPowerController( 1016): ColorFade: onAnimationStart
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1794): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,E/WifiNative-wlan0( 1016): do suspend true
,D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,E/SMD     (  287): DCD OFF
,D/DisplayPowerState( 1016): !@ ColorFade entry
,D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1016): lcd : 0 +
,D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4282, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/lights  ( 1016): lcd : 0 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/DisplayManagerService( 1016): !@display_state: ON -> OFF
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb8f54690
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager( 1016): Display changed displayId=0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 255ms
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
,I/PowerManagerService( 1016): [PWL] Off : 0s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 267ms
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1435): [EmergencyStateReceiver] binteractive [false] why[3]
,D/NfcService( 1459): call the applyRouting
,D/accuweather( 1576): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1576): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1576): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,D/SViewCoverView( 1172): Move to page : HomePage
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
,D/accuweather( 1576): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1576): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1576): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1576): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LibSecureUISvc( 1954): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1576): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1576): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1576): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1576): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/accuweather( 1576): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1576): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1576): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4295, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,E/Watchdog( 1016): !@Sync 32
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,V/AlarmManager( 1016): waitForAlarm result :4
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 33
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,I/BooksSync( 6346): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
,I/BooksConfig( 6346): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6346): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6346): Soft error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6346): Sync error
E/BooksSync( 6346): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6346): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6346): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1023946, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 75s ago,
,E/Watchdog( 1016): !@Sync 34
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,V/AlarmManager( 1016): waitForAlarm result :8
,V/AlarmManager( 1016): waitForAlarm result :4,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 105s ago,
,E/Watchdog( 1016): !@Sync 35,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4296, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 36
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 37
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 38
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,E/Watchdog( 1016): !@Sync 39
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB,
I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1449057582805
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1449057583150
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 40
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 41
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 42
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 330s ago,
,V/AlarmManager( 1016): waitForAlarm result :8
V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=1293057 batch.start=1835097
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 43
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for fully charged
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 44,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 45
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 46
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 47,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 48,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/Watchdog( 1016): !@Sync 49
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 50
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 51
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 600s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 52,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 53,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 54
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 680s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 55
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 56
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 57
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 58
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 59
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 855s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 60
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
I/ActivityManager( 1016): Killing 5835:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5503:com.google.android.partnersetup/u0a15 (adj 15): empty #32
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
I/ActivityManager( 1016): Killing 5407:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #33
,I/ActivityManager( 1016): Killing 2860:com.samsung.android.providers.context/u0a3 (adj 15): SPC_empty #34
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService( 1016): Prepared write state in 16ms
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/NetworkStats( 1016): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/SViewCoverWidget( 1172): Weather changed action :android.intent.action.TIME_TICK
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 11ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/SViewCoverWidget( 1172): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/GpsStatusListenerHelper( 1016): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@31ef29b8
,W/ActivityManager( 1016): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3606910ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1172): getCheckCurrent: result = 0
,D/daemonapp( 1286): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1172): cityId=
,D/SViewCoverWidget( 1172): cityId=
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ProcessStatsService( 1016): Pruning old procstats: /data/system/procstats/state-2015-12-01-15-22-26.bin
W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_2860/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_5503/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5407/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_5835/cgroup.procs: No such file or directory
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1704): Message class com.google.f.a.a.i
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 1016): Killing 3780:com.sec.bcservice/1000 (adj 15): SPC_empty #31
,I/ActivityManager( 1016): Killing 3520:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #32
,I/ActivityManager( 1016): Killing 2675:com.sec.phone/1001 (adj 15): SPC_empty #31
,E/lowmemorykiller(  253): Error writing /proc/2675/oom_score_adj; errno=22
,W/ActivityManager( 1016): ProcessRecord{1581f5a6 2675:com.sec.phone/1001} is already killed
,E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1016): Exception when unbinding service com.sec.phone/.SecPhoneService,
W/ActivityManager( 1016): android.os.TransactionTooLargeException
W/ActivityManager( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1016): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1016): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1016): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18582)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6593)
,W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6806)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1606)
W/ActivityManager( 1016): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
W/ActivityManager( 1016): ProcessRecord{1581f5a6 2675:com.sec.phone/1001} is already killed
,W/ActivityManager( 1016): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 1000ms
,W/ActivityManager( 1016): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10992ms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3780/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1001/pid_2675/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10116/pid_3520/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7137): MountEmulatedStorage(),
I/libpersona( 7137): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7137): v2
I/libpersona( 7137): KNOX_SDCARD not a persona
,I/SELinux ( 7137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=7137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 7137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7137): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7137): TimaSignature is unavailable
,D/ActivityThread( 7137): Added TimaKeyStore provider
,W/ResourcesManager( 7137): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 7137): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 7137): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7152): MountEmulatedStorage()
,E/Zygote  ( 7152): v2
I/libpersona( 7152): KNOX_SDCARD checking this for 1001
I/libpersona( 7152): KNOX_SDCARD not a persona
I/SELinux ( 7152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=7152 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 7152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 7152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7152): TimaSignature is unavailable
,D/ActivityThread( 7152): Added TimaKeyStore provider
,W/ResourcesManager( 7152): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 7137): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 7137): default registerAction()
I/F_PHONE ( 7137): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 61
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7173): MountEmulatedStorage(),
E/Zygote  ( 7173): v2
I/libpersona( 7173): KNOX_SDCARD checking this for 10116
,I/libpersona( 7173): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=7173 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/SELinux ( 7173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 7173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 7173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7173): TimaSignature is unavailable
,D/ActivityThread( 7173): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3579:com.samsung.hs20settings/1000 (adj 15): SPC_empty #31
,I/PageBuddyNotiSvc( 7173): onCreate mCpBitFlag=0
,W/ActivityManager( 1016): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 1000ms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3579/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7189): MountEmulatedStorage(),
I/libpersona( 7189): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7189): v2
I/libpersona( 7189): KNOX_SDCARD not a persona
,I/SELinux ( 7189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=7189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7189): TimaSignature is unavailable
,D/ActivityThread( 7189): Added TimaKeyStore provider
,I/Hs20UtilService( 7189): onCreate
,I/Hs20UtilService( 7189): Starting #8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 62,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),D/SSRM:n  ( 1016): SIOP:: AP = 260
E/SMD     (  287): DCD OFF
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7228): 
D/AndroidRuntime( 7228): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7228): CheckJNI is OFF
D/AndroidRuntime( 7228): readGMSProperty: start
D/AndroidRuntime( 7228): readGMSProperty: already setted!!
D/AndroidRuntime( 7228): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7228): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7228): readGMSProperty: end
D/AndroidRuntime( 7228): addProductProperty: start
E/AffinityControl( 7228): AffinityControl: registerfunction enter
D/AndroidRuntime( 7228): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1016): START PACKAGE DELETE: observer{868344108}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 6130:com.test.thalitest/u0a175 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1016): Skipping PackageSetting{3dbf6fc6 com.example.hello/10174} due to missing metadata
I/ActivityManager( 1016): Killing 6233:com.google.android.apps.plus/u0a120 (adj 15): empty for 1813s
I/ActivityManager( 1016): Killing 6192:com.osp.app.signin/u0a41 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 6172:com.sec.knox.bridge/1000 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 5951:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 6151:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 6109:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 6079:com.sec.android.app.soundalive/u0a53 (adj 15): empty for 1814s
I/ActivityManager( 1016): Killing 6057:com.wsomacp/u0a25 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 6042:com.sec.android.app.myfiles/u0a47 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 5844:com.android.mms/u0a46 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 6020:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 5990:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 5962:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty for 1815s
I/ActivityManager( 1016): Killing 5913:com.policydm/1000 (adj 15): empty for 1816s
I/ActivityManager( 1016): Killing 5518:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty for 1816s
I/ActivityManager( 1016): Killing 5898:com.samsung.helphub/1000 (adj 15): empty for 1816s
I/ActivityManager( 1016): Killing 5880:com.google.android.apps.docs/u0a91 (adj 15): empty for 1816s
I/ActivityManager( 1016): Killing 5866:com.sec.pcw.device/1000 (adj 15): empty for 1816s
W/ActivityManager( 1016): Spurious death for ProcessRecord{303077f5 6130:com.test.thalitest/u0a175}, curProc for 6130: null
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
D/CountryDetector( 1016): No listener is left
I/art     ( 6277): Explicit concurrent mark sweep GC freed 693(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 732us total 32.233ms
I/art     ( 5169): Explicit concurrent mark sweep GC freed 2021(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 699us total 32.829ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1794): mOCRHelper is null
W/GeofencerStateMachine( 1663): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3614): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 13:11:06 GMT+01:00 2015
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1459): Collect Tech packages for Knox
D/PersonaManager( 1459): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3614): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1016): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7241): MountEmulatedStorage()
E/Zygote  ( 7241): v2
I/libpersona( 7241): KNOX_SDCARD checking this for 10094
I/libpersona( 7241): KNOX_SDCARD not a persona
I/SELinux ( 7241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7241 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3614): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3614): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/art     (  305): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 32.490ms
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 7241): TimaSignature is unavailable
D/ActivityThread( 7241): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1016): Explicit concurrent mark sweep GC freed 35939(2MB) AllocSpace objects, 37(680KB) LOS objects, 33% free, 27MB/41MB, paused 3.132ms total 192.739ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.965ms
I/art     ( 1016): WaitForGcToComplete blocked for 181.368ms for cause Explicit
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.095ms
D/PersonaManager( 1459): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1459): empty dynamic service
D/elm:15183( 7241): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 7241): ELMEngine.ELMEngine( context ).
D/elm:15183( 7241): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 7241): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 7241): ElmAgentService : onCreate()
D/elm:15183( 7241): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7241): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7241): MDMBridge.getInstance()
D/elm:15183( 7241): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7241): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7241): ElmAgentService : onDestroy().
I/ActivityManager( 1016): Killing 6298:com.sec.android.app.samsungapps/u0a10 (adj 15): empty for 1813s
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3614): KLMSIntentService(): onDestroy()
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10175
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1016): removeObsoleteFile: deleting file=229_task.xml
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10175
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7258): MountEmulatedStorage()
E/Zygote  ( 7258): v2
I/libpersona( 7258): KNOX_SDCARD checking this for 1000
I/libpersona( 7258): KNOX_SDCARD not a persona
I/SELinux ( 7258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7258 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7258): TimaSignature is unavailable
D/ActivityThread( 7258): Added TimaKeyStore provider
I/art     ( 1016): Explicit concurrent mark sweep GC freed 13132(751KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/40MB, paused 3.497ms total 223.847ms
I/PCWCLIENTTRACE_LOG( 7258): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7258): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7258): new DMDBOpenHelper instance
D/PackageManager( 1016): delete codoeFile: 
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10175 Target=com.test.thalitest
D/PackageManager( 1016): result of delete: 1{868344108}
D/AndroidRuntime( 7228): Shutting down VM
I/PCWCLIENTTRACE_PushUtil( 7258): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7258): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7258): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7258): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7273): MountEmulatedStorage()
E/Zygote  ( 7273): v2
I/libpersona( 7273): KNOX_SDCARD checking this for 10032
I/libpersona( 7273): KNOX_SDCARD not a persona
I/SELinux ( 7273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7273 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 6321:com.google.android.gms:car/u0a12 (adj 15): empty for 1812s
D/TimaKeyStoreProvider( 7273): TimaSignature is unavailable
D/ActivityThread( 7273): Added TimaKeyStore provider
I/FeatureConfig( 7273): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7290): MountEmulatedStorage()
E/Zygote  ( 7290): v2
I/libpersona( 7290): KNOX_SDCARD checking this for 10038
I/libpersona( 7290): KNOX_SDCARD not a persona
I/SELinux ( 7290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7290 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 6277:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty for 1812s
E/SELinux ( 7290): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5866/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_6057/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6151/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_5844/cgroup.procs: No such file or directory
W/ResourcesManager( 7273): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/ResourcesManager( 7273): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
W/ResourcesManager( 7273): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7290): TimaSignature is unavailable
D/ActivityThread( 7290): Added TimaKeyStore provider
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7273): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/art     ( 7228): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 7273): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7273): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/GalaxyFinderApplication( 7273): system/finder_cp/cpdata.xml file not found
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SL_DEBUG( 7290): isLoggable:: isProductShip = 1
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SL_DEBUG( 7290): isLoggable:: SL_DEBUG_EXIST = false
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5898/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6172/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_5990/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_6079/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5962/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_6192/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5913/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_6042/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5518/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_5880/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_6020/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6109/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_6233/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10038/pid_5951/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10010/pid_6298/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_6321/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_6277/cgroup.procs: No such file or directory
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7290): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7290): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7318): MountEmulatedStorage()
E/Zygote  ( 7318): v2
I/libpersona( 7318): KNOX_SDCARD checking this for 10041
I/libpersona( 7318): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7318 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7318): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL

```
